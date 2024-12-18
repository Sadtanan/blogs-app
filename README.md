﻿#Blog app
เป็น MERN stack web app สำหรับเรียกดู บันทึก แก้ไข ลบ บทความใน database

โดยใน Project นี้จะประกอบด้วยระบบล็อกอินด้วยที่คนที่่ล็อกอินคือแอดมิน
User ธรรมดาจะสามรถเรียกดูบทความได้อย่างเดียว และปิดช่องโหวของ user ที่สามารถใช้ URL ในการเข้าถึงฟังก์ชันของแอดมินด้วย
รวมถึงใช้ JWT express ในการจำกัดสิทธิในกรณีเรียกใช้ API โดยตรง
ตอนนี้ hosting อยู่ที่ https://blogs-app-1-gbx1.onrender.com โดยเมื่อเข้าไปแล้วจะใช้เวลาโหลดเนื้อหาสัก 1-3 นาที เนื่องจากใช้ free hosting ของ render
รหัสสำหรับสิทธิ admin => username : admin
password : admin123

package ที่เกี่ยวข้อง
-express
-mongoose
-jsonwebtoken
-cors
-nodemon
-dotnev
-slugify
-express-jwt
-morgan
-sweetalert2
-อื่นๆ

## Installation
1. Clone the repository:
git clone https://github.com/Sadtanan/blogs-app

2. Install dependencies:
npm install

3. Start the application:
ืnpm start
