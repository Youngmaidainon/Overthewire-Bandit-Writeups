# Bandit Level 23 → 24

## Objective

Write a shell script that will be automatically executed by a cron job to copy the password file.

## Skills Learned

- Writing Automation Scripts
- Linux Permissions

## Commands Used

touch /var/spool/bandit24/foo/myscript.sh
chmod +x /var/spool/bandit24/foo/myscript.sh

## What I Learned

- ฝึกฝนเขียนสคริปต์คำสั่งสั้นๆ เพื่อให้ระบบหยิบไปทำงานแทน พร้อมทำความเข้าใจการกำหนดสิทธิ์เปิดสวิตช์อนุญาตให้ไฟล์สคริปต์รันได้ด้วยคำสั่ง `chmod +x`