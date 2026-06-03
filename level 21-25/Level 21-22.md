# Bandit Level 21 → 22

## Objective

Find the password by inspecting a regularly scheduled job running under cron.

## Skills Learned

- Cron Job Inspection

## Commands Used

ls /etc/cron.d/
cat /etc/cron.d/cronjob_bandit22
cat /usr/bin/cronjob_bandit22.sh

## What I Learned

- วิธีเข้าไปสืบค้นและแกะรอยดูรายละเอียดของระบบงานตั้งเวลาอัตโนมัติ (Cron Jobs) ภายในระบบปฏิบัติการลินุกซ์เพื่อหาไฟล์สคริปต์ทำงานเบื้องหลัง