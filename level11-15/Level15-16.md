# Bandit Level 15 → 16

## Objective

Submit the current password to port 30001 on localhost using SSL/TLS encryption.

## Skills Learned

- Secure Network Communication
- SSL/TLS Clients

## Commands Used

openssl s_client -connect localhost:30001

## What I Learned

- การเชื่อมต่อเครือข่ายแบบเข้ารหัสความปลอดภัยด้วยคำสั่ง `openssl s_client` เพื่อใช้รับส่งข้อมูลกับบริการพอร์ตที่ทำงานภายใต้ระบบรักษาความปลอดภัย SSL/TLS