# งานพัฒนาการจำลอง Banker Algorithm
### จงพัฒนาระบบจำลอง Banker Algorithm โดยมีคุณสมบัติดังนี้
- กำหนดให้มี Resources 3 ชนิด คือ A B และ C โดยเริ่มต้นจะกำหนดให้มีอย่างละ 10
- การสร้างโปรเซสจะต้องระบุชื่อและ Max resource
- เมื่อโปรเซสทำการร้องขอ Resource แล้ว ให้แสดงผลลัพธ์การร้องขอนั้นว่า Safe หรือ Not Safe หาก Safe ให้ Allocate resource นั้นแก่โปรเซส หาด Not Safe ก็ไม่อนุญาตให้ Allocate
- หากโปรเซสได้รับ Resource ครบตาม Max resource แล้ว โปรเซสนั้นจะต้องจบโปรเซสและคืน Resource แกระบบ