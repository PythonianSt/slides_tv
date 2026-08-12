# Meeting Slides - Vercel

## โครงสร้างไฟล์

```
vercel_slides_app/
├─ index.html
├─ vercel.json
└─ slides/
   ├─ slide01.png
   ├─ slide02.png
   ├─ slide03.png
   ├─ slide04.png
   ├─ slide05.png
   ├─ slide06.png
   ├─ slide07.png
   └─ slide08.png
```

ให้นำภาพสไลด์ PNG เดิม 8 ภาพใส่ในโฟลเดอร์ `slides` โดยใช้ชื่อข้างต้น

## วิธีขึ้น Vercel ผ่าน GitHub

1. สร้าง GitHub repository ใหม่
2. Upload `index.html`, `vercel.json` และโฟลเดอร์ `slides`
3. เข้า Vercel > Add New > Project
4. Import repository นี้
5. Framework Preset เลือก `Other`
6. Build Command ปล่อยว่าง
7. Output Directory ปล่อยว่าง
8. กด Deploy

เว็บนี้เป็น Static HTML/JavaScript จึงไม่ต้องใช้ Python, Streamlit หรือ requirements.txt
