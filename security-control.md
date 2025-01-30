# ▶️ Security Control: Microsoft SQL Sever Login 🌌
 - ### Microsoft SQL Server Login 🔏
   - คือระบบการยืนยันตัวตนหรือการลงชื่อเข้าใช้งานในฐานข้อมูล Microsoft SQL Server ซึ่งเป็นขั้นตอนสำคัญในการรักษาความปลอดภัยของฐานข้อมูล

### ⛺ สถานที่: 
 - ### My own Notebook :computer:

<img src="/images/sqlseverloginpage.jpg" width="555" />

### 🔷 Type of Security Control: Technical Control 🔷
 - ใช้เทคโนโลยีในการควบคุมความปลอดภัย:
   - มีระบบ Authentication ผ่านซอฟต์แวร์
   - ใช้ระบบฐานข้อมูล SQL Server ซึ่งเป็นเทคโนโลยีในการจัดการ
   - มีการควบคุมผ่านระบบคอมพิวเตอร์โดยตรง

###  🔶 Control Function: Preventive Control 🔶
 - ทำหน้าที่ป้องกันก่อนเหตุการณ์ (Prevention before incident):
   - มีการตรวจสอบตัวตนผู้ใช้งาน (Authentication) ก่อนอนุญาตให้เข้าถึงระบบ
   - ต้องระบุ Server name และ Login credentials ก่อนจึงจะสามารถเชื่อมต่อได้
 - มีการควบคุมการเข้าถึงแบบเชิงป้องกัน:
   - ผู้ใช้ต้องมีบัญชีที่ถูกต้องก่อน
   - มีการเลือกรูปแบบการยืนยันตัวตน (Authentication type)
   - มีการป้องกันการเข้าถึงโดยไม่ได้รับอนุญาต

### 🔦 summarize
&nbsp;  Microsoft SQL Server Login เป็นการควบคุมแบบ Technical Control ในรูปแบบ Preventive Control ที่ชัดเจน เนื่องจากเป็นระบบการยืนยันตัวตนที่ใช้เทคโนโลยีโดยตรงผ่านกลไก username และ password ซึ่งเป็นส่วนหนึ่งของระบบรักษาความปลอดภัยของ Microsoft SQL Server นอกจากนี้ยังทำหน้าที่เป็นด่านป้องกันแรกในการคัดกรองผู้ใช้งาน โดยจะอนุญาตให้เฉพาะผู้ที่มีสิทธิ์เท่านั้นที่สามารถเข้าถึงระบบฐานข้อมูลได้
  
