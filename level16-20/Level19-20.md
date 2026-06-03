# Bandit Level 19 → 20

## Objective

Use a SUID binary to read the password file for the next level.

## Skills Learned

- Executing Privileged Binaries (SUID)

## Commands Used

./bandit20-do cat /etc/bandit_pass/bandit20

## What I Learned

- ทำความเข้าใจเรื่อง SUID (Set Owner User ID) ซึ่งเป็นกลไกพิเศษยอมให้ผู้ใช้ระดับธรรมดาเรียกเปิดรันไฟล์โปรแกรมเฉพาะทางด้วยสิทธิ์ของผู้เป็นเจ้าของระบบได้ชั่วคราว