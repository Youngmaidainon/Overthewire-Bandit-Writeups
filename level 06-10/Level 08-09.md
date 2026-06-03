# Bandit Level 8 → 9

## Objective

Find the line of text in `data.txt` that occurs only once.

## Skills Learned

- Sorting Text
- Filtering Unique Lines

## Commands Used

sort data.txt | uniq -u

## What I Learned

- การเชื่อมโยงคำสั่งผ่านท่อส่งข้อมูล Pipeline (`|`)
- การจัดเรียงลำดับข้อความด้วยคำสั่ง `sort` เพื่อให้คำสั่ง `uniq -u` สามารถตรวจสอบและคัดกรองบรรทัดข้อมูลที่ไม่มีคำซ้ำออกมาได้