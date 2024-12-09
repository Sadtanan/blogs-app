Blog app
เป็น MERN stack web app สำหรับเรียกดู บันทึก แก้ไข ลบ บทความใน database

โดยใน Project นี้จะประกอบด้วยระบบล็อกอินด้วยที่คนที่่ล็อกอินคือแอดมิน
User ธรรมดาจะสามรถเรียกดูบทความได้อย่างเดียว และปิดช่องโหวของ user ที่สามารถใช้ URL ในการเข้าถึงฟังก์ชันของแอดมินด้วย
รวมถึงใช้ JWT express ในการจำกัดสิทธิในกรณีเรียกใช้ API โดยตรง

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