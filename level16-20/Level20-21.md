# Bandit Level 20 → 21

## Objective

Perform a local connection challenge where a SUID binary connects back to a listening port to verify credentials.

## Skills Learned

- Background Processes
- Netcat Listening

## Commands Used

nc -l -p 12345 &
./suconnect 12345

## What I Learned

- การเปิดพอร์ตเพื่อทำหน้าที่รอรับการเชื่อมต่อกลับ (Listening Mode) ควบคู่กับการใช้สัญลักษณ์แอมเพอร์แซนด์ (`&`) สั่งรันคำสั่งทิ้งไว้ให้ทำงานอยู่เบื้องหลัง (Background Process)