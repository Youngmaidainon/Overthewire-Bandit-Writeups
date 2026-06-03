# Bandit Level 9 → 10

## Objective

Find the password in `data.txt` which is one of the few human-readable strings, preceded by several `=` characters.

## Skills Learned

- Extracting Readable Strings from Binary

## Commands Used

strings data.txt | grep "=="

## What I Learned

- การดึงเอาเฉพาะชุดตัวอักษรที่มนุษย์สามารถอ่านรู้เรื่องออกมาจากไฟล์ข้อมูลแบบกึ่งไบนารีด้วยคำสั่ง `strings` ก่อนที่จะกรองต่อด้วยสัญลักษณ์เครื่องหมายเท่ากับ