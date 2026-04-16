Lotto Entry System (ระบบลงตัวเลขหวย)

ระบบลงตัวเลขหวยที่สามารถส่งข้อมูลไปยัง Google Sheets ได้โดยตรง พร้อมระบบตรวจสอบเลขปิดประจำงวด

🚀 วิธีการติดตั้งบน GitHub (GitHub Pages)

สร้าง Repository ใหม่:

ไปที่ GitHub ของคุณแล้วกด "New repository"

ตั้งชื่อโปรเจกต์ (เช่น lotto-system) และตั้งเป็น Public

อัปโหลดไฟล์:

กดปุ่ม "uploading an existing file"

ลากไฟล์ index.html และ README.md ขึ้นไป

กด Commit changes

เปิดใช้งานหน้าเว็บ:

ไปที่เมนู Settings ของ Repository นั้น

เลือกเมนู Pages ทางด้านซ้าย

ในส่วนของ Build and deployment, เลือก Branch เป็น main และโฟลเดอร์เป็น /(root)

กด Save

รอสักครู่:

GitHub จะสร้างลิงก์เว็บไซต์ให้คุณ (เช่น https://yourusername.github.io/lotto-system/) คุณสามารถเข้าใช้งานผ่านลิงก์นั้นได้ทันที!

📊 การเชื่อมต่อ Google Sheets

เปิด Google Sheets

ไปที่ Extensions > Apps Script

คัดลอกโค้ดจากไฟล์ google_apps_script.js ไปวาง

กด Deploy > New Deployment

เลือกประเภทเป็น Web App

ตั้งค่า Who has access เป็น Anyone

นำ URL ที่ได้มาใส่ในเมนู Settings (รูปเฟือง) ในหน้าเว็บของคุณ

หมายเหตุ: โค้ดนี้ใช้ React ผ่าน CDN ทำให้ไม่ต้องติดตั้ง Node.js บนเครื่อง