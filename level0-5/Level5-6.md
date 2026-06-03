# Bandit Level 5 → 6

## Objective

Find a file under `inhere` directory that is human-readable, 1033 bytes in size, and not executable.

## Skills Learned

- Advanced File Searching

## Commands Used

find inhere/ -type f -size 1033c ! -executable -exec cat {} +

## What I Learned

- การประยุกต์ใช้คำสั่ง `find` ร่วมกับเงื่อนไขตัวกรองขั้นสูง เช่น ชนิดไฟล์ สิทธิ์การรันไฟล์ และขนาดหน่วยเป็นไบต์ (`1033c`) เพื่อเจาะจงค้นหาไฟล์ที่ถูกต้อง