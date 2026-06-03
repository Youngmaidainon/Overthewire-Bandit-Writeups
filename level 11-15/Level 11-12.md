# Bandit Level 11 → 12

## Objective

Decode the password in `data.txt` which has been rotated by 13 positions (ROT13).

## Skills Learned

- Character Transformation (Substitution Cipher)

## Commands Used

cat data.txt | tr '[A-Za-z]' '[N-ZA-Mn-za-m]'

## What I Learned

- การใช้คำสั่ง `tr` (Translate) เพื่อสลับแทนที่ชุดตัวอักษรเพื่อทำการถอดรหัสลับประเภทโครงสร้างเลื่อนตำแหน่งอักษร (Substitution Cipher)