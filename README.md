##**Adroid+Terminal Emulator**

###การใช้ terminal emulator บน android 

##การสำรวจเครื่องมีการดำเนินการ 2 ส่วน
1. การสำรวจระบบ android linux
2. การจัดการแฟ้ม และสารบบ 
โดยใช้คำสั่งต่าง ๆ เรียงลำดับก่อนหลังดังนี้

#[1. การสำรวจระบบ android linux]
1. pwd ดูว่าปัจจุบันอยู่ใน folder อะไร พบว่าอยู่ใน /
2. id ดูชื่อ และรหัสตนเอง พบว่าตนเองชื่อ app_... id คือ ... หมายเหตุ *(....)คืออะไร*
3. df ดูว่าในเรื่องมีพื้นที่เท่าใด
4. env ดูข้อมูลสาพแวดล้อม
5. ps ดูว่ามี process อะไรประมวลผลอยู่
6. netstat ดูว่าเปิด port อะไร และติดต่อไปข้างนอกอยู่หรือเปล่า
7. netcfg ดูว่าเชื่อมต่อออกไปใช้ ip อะไร
8. ls ดูรายชื่อแฟ้ม
9. du ดูขนาดแต่ละ folder ทั้งหมด
10. date ดูว่ากี่โมง และวันที่เท่าใด

#[2. การจัดการแฟ้ม และสารบบ]
1. cd เพื่อย้ายตำแหน่งไปยัง app_HOME
2. du / > a เพื่อสร้างแฟ้มชื่อ a
3. ls -al เพื่อแสดงรายชื่อ และขนาดของแฟ้ม
4. tail a เพื่อดูส่วนหางของแฟ้ม เพียง 10 บรรทัดทุดท้าย
5. mkdir x เพื่อสร้าง folder ชื่อ x
6. mv a x เพื่อย้ายแฟ้ม a ไปใน x
7. cd x เพื่อเข้าห้อง x
8. cp a b เพื่อคัดลอกแฟ้ม a เป็น b
9. find เพื่อแสดงรายชื่อแฟ้ม หรือ find a หรือ find c
10. find > c เพื่อนำชื่อแฟ้มไปสร้างเป็นแฟ้ม c

![Image](http://kawintharawiw.github.io/Android-Terminal-Emulator/77.jpg)
![Image](http://kawintharawiw.github.io/Android-Terminal-Emulator/88.jpg)

