# Bandit Level 13 → 14

## Objective

Retrieve the password for the next level by logging in using the private SSH key stored in `sshkey.private`.

## Skills Learned

- SSH Key Authentication

## Commands Used

ssh -i sshkey.private bandit14@localhost -p 2220

## What I Learned

- เรียนรู้วิธีการเข้าใช้งานเซิร์ฟเวอร์ปลายทางโดยอาศัย Private Key คู่กับตัวเลือก `-i` แทนการป้อนรหัสผ่านปกติเพื่อความปลอดภัยขั้นสูง