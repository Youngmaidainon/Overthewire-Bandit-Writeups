# Bandit Level 22 → 23

## Objective

Reverse engineer a cron script that computes a dynamic hidden filename using an MD5 hash of the username.

## Skills Learned

- Analyzing Shell Scripts
- MD5 Hashing

## Commands Used

cat /usr/bin/cronjob_bandit23.sh
echo -n "bandit23" | md5sum

## What I Learned

- วิธีการอ่านและวิเคราะห์ตรรกะชุดสคริปต์คำสั่ง เพื่อนำสูตรคำนวณรหัสลับ MD5 แฮชกลับมาจำลองพิมพ์ค้นหาตำแหน่งพิกัดไฟล์รหัสผ่านตัวจริง