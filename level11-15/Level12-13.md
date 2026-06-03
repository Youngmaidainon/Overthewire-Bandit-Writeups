# Bandit Level 12 → 13

## Objective

Retrieve the password for the next level by unpacking a file that contains a hex dump and has been repeatedly compressed using different formats.

## Skills Learned

- Hex dump reversal (`xxd`)
- File type identification (`file`)
- Handling multiple compression formats (`gzip`, `bzip2`, `tar`)
- Working within temporary directories (`/tmp`)

## Commands Used

```bash
# 1. สร้างโฟลเดอร์ชั่วคราวใน /tmp เนื่องจากไดเรกทอรีโฮมไม่มีสิทธิ์ในการเขียนไฟล์ (Write Permission)
mkdir /tmp/my_workspace
cp data.txt /tmp/my_workspace/
cd /tmp/my_workspace/

# 2. แปลงไฟล์ Hex Dump กลับไปเป็นไฟล์ไบนารีดั้งเดิม
xxd -r data.txt > data.bin

# 3. ตรวจสอบประเภทไฟล์และทำการแตกไฟล์ซ้อนกันไปเรื่อยๆ ตามที่ระบบตรวจเจอ
file data.bin

# ตัวอย่างคำสั่งที่ใช้ตามประเภทไฟล์ที่ตรวจพบในแต่ละชั้น:
# ถ้าเป็น gzip:
mv data.bin data.gz && gzip -d data.gz
# ถ้าเป็น bzip2:
bzip2 -d data.bin
# ถ้าเป็น tar archive:
tar -xf data.bin