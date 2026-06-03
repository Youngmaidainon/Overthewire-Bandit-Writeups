# Bandit Level 31 → 32

## Objective

Push a specific file to a Git repository to trigger a server-side hook that returns the password.

## Skills Learned

- Git Pushing
- Overriding Gitignore

## Commands Used

git add -f key.txt
git commit -m "add file"
git push origin master

## What I Learned

- วิธีการใช้พารามิเตอร์เพื่อบังคับใส่ไฟล์ฝ่าฝืนกฎข้อห้ามของระบบควบคุม (`git add -f`) เพื่ออัปโหลดไฟล์ไปกระตุ้นคำสั่งประมวลผลอัตโนมัติบนระบบเซิร์ฟเวอร์