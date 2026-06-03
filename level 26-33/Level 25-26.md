# Bandit Level 25 → 26

## Objective

Log into bandit26 but escape the restricted shell that immediately closes the connection using `more`.

## Skills Learned

- Escaping Restricted Shells
- Text Viewer Interaction

## Commands Used

ssh -i bandit26.sshkey bandit26@localhost
# ทำการย่อหน้าต่าง Terminal ให้มีขนาดเล็กจิ๋วเพื่อให้หน้าแสดงผล more ทำงานค้างไว้
v
:set shell=/bin/bash
:shell

## What I Learned

- วิธีเล็ดลอดหนีออกจากระเบียบบังคับสิทธิ์ของเชลล์ที่ถูกจำกัดวง (Restricted Shell Escape) โดยการเจาะช่องทางลัดผ่านตัวอ่านข้อความโปรแกรม `more` ไปหาโปรแกรมแก้ไขข้อความ `vi`