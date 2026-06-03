# Bandit Level 16 → 17

## Objective

Scan ports between 31000 and 32000 on localhost to find which one speaks SSL and returns the credentials.

## Skills Learned

- Port Scanning
- Private Key Management

## Commands Used

nmap -p 31000-32000 localhost
openssl s_client -connect localhost:<port>

## What I Learned

- เรียนรู้วิธีสำรวจตรวจสอบพอร์ตบริการที่เปิดใช้งานอยู่บนเครือข่ายด้วยชุดโปรแกรมตรวจสอบระบบอย่าง `nmap` และนำพอร์ตที่พบไปดึงข้อมูลคีย์ส่วนตัวคืนมา