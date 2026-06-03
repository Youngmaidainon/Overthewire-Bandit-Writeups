# Bandit Level 6 → 7

## Objective

Find a file somewhere on the server owned by user `bandit7`, group `bandit6`, and 33 bytes in size.

## Skills Learned

- System-wide File Searching
- Error Redirection

## Commands Used

find / -user bandit7 -group bandit6 -size 33c 2>/dev/null

## What I Learned

- การค้นหาไฟล์จากรูทไดเรกทอรี (`/`) โดยเจาะจงเจ้าของไฟล์และกลุ่มผู้ใช้งาน
- การใช้คำสั่ง `2>/dev/null` ปิดกั้นการแสดงผลข้อผิดพลาดจำพวก Permission Denied เพื่อให้เห็นผลลัพธ์ที่ต้องการได้ชัดเจนขึ้น