# Bandit Level 18 → 19

## Objective

Log into bandit18, but bypass the modified `.bashrc` profile that logs you out instantly.

## Skills Learned

- SSH Command Execution

## Commands Used

ssh bandit18@bandit.labs.overthewire.org -p 2220 "cat readme"

## What I Learned

- วิธีการส่งคำสั่งพ่วงต่อท้ายหลังจากล็อกอินผ่านระบบ SSH เพื่อสั่งให้คำสั่งทำงานและรับค่ากลับคืนมาโดยไม่ต้องเปิดเข้าใช้ระบบ Shell เต็มรูปแบบที่คอยขัดขวางเราอยู่