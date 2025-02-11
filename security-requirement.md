# OWASP Application Security Verification Standard
### 3.4.1 Cookie-based Session Management 🍪

## Details 🔸
- Verify that cookie-based session tokens have the 'Secure' attribute set.

## ChatGPT 🔹
- ต้องตรวจสอบให้แน่ใจว่าคุกกี้ที่ใช้เก็บโทเค็นเซสชัน (Session Token) มีการตั้งค่า 'Secure' attribute ซึ่งหมายความว่าคุกกี้นั้นจะถูกส่งผ่านเฉพาะการเชื่อมต่อที่เข้ารหัส (HTTPS) เท่านั้น ป้องกันการถูกดักข้อมูลจากการเชื่อมต่อที่ไม่ปลอดภัย (HTTP)

## Gemini 🔸
- การตรวจสอบว่า cookie-based session tokens มี Attribute 'Secure' หรือไม่ เป็นขั้นตอนสำคัญในการรักษาความปลอดภัยของเว็บแอปพลิเคชัน เพื่อป้องกันการถูกดักจับ session token และการเข้าถึงข้อมูลของผู้ใช้โดยไม่ได้รับอนุญาต

## My self 🔹
- การที่ cookie มี 'Secure' attribute จะช่วยให้ป้องการการดักเอาข้อมูล session token ระหว่างการส่งข้อมูล และยังบังคับให้ส่งข้อมูล cookie เมื่อมีการเชื่อมต่อที่เข้ารหัส (HTTPS) เท่านั้นอีกด้วย ดังนั้นการตั้งค่า 'Secure' attribute จึงเป็นข้อกำหนดพื้นฐานที่สำคัญที่ควรมี จึงจำเป็นต้องมีการตรวจสอบว่า cookie-based session tokens ได้ทำการใส่ 'Secure' attribute เข้าไปแล้ว
