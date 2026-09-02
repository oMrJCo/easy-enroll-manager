EASY SMART & ENROLLONE ONLINE v1 PIN

โครงระบบ
- GitHub Pages = หน้าเว็บ
- Firestore = ฐานข้อมูลกลาง
- PIN = กันคนเปิดหน้าเว็บโดยไม่ตั้งใจ
- ไม่ใช้ Firebase Authentication

ขั้นตอนต่อ
1. Firestore > Rules
2. วางเนื้อหาในไฟล์ firestore.rules แล้วกด Publish
3. Firebase Project Settings > Your apps > สร้าง Web App
4. นำ firebaseConfig มาใส่ firebase-config.js
5. อัปโหลด index.html และ firebase-config.js ขึ้น GitHub Pages

หมายเหตุ
PIN หน้าเว็บเป็นการกันการเข้าถึงทั่วไป ไม่ใช่ระบบยืนยันตัวตนระดับฐานข้อมูล


FIREBASE CONFIG
- เชื่อม Project easy-enroll-manager แล้ว
- firebase-config.js พร้อมใช้งาน
- สำหรับ GitHub Pages ให้อัปโหลด index.html และ firebase-config.js ที่ root ของ repository
