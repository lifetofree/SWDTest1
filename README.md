# swdtest1

ส่วนที่ 1 Flutter
ให้ใช้ Flutter เวอร์ชั่นล่าสุดในการสร้างโปรเจค และใช้ State Management  
สร้างแอปเก็บข้อมูลบุคคล ข้อมูลที่จะเก็บมี 2 ส่วนคือ ข้อมูลส่วนบุคคล และข้อมูลที่อยู่ตามบัตรประชาชน 
โดยจะมี Features ดังนี้
1. หน้าแสดงรายชื่อทั้งหมด
     - สามารถแสดงข้อมูลได้ 2 รูปแบบคือ แสดงรายชื่อทั้งหมดและแสดงรายชื่อแยกตามแต่ละจังหวัด
โดยใช้ Widget TabBar
     - ปุ่มเพิ่มรายชื่อ
     - ปุ่มลบรายชื่อ กดแล้วให้ขึ้น confirm dialog เพื่อยืนยันการกดลบ
2. หน้ากรอกข้อมูล ให้ใช้ Widget Stepper เพื่อเก็บข้อมูล โดยให้ 
      Step 1 เก็บข้อมูลส่วนตัว 
      Step 2 เก็บข้อมูลที่อยู่ตามบัตรประชาชน 
3. หน้าแสดงรายละเอียดข้อมูลแต่ละบุคคล
