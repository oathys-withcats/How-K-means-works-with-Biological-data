# K-means Clustering Explorer

Interactive web application สำหรับสอน K-means clustering ด้วยข้อมูลสัณฐานวิทยาใบไม้ (leaf morphometric data)

## วิธี Deploy บน GitHub Pages

### ขั้นตอนที่ 1 — สร้าง GitHub Repository

1. ไปที่ [github.com](https://github.com) แล้ว sign in
2. กดปุ่ม **+** มุมขวาบน → เลือก **New repository**
3. ตั้งชื่อ เช่น `kmeans-explorer`
4. เลือก **Public**
5. ติ๊ก **Add a README file**
6. กด **Create repository**

### ขั้นตอนที่ 2 — อัปโหลดไฟล์

1. ในหน้า repository กด **Add file** → **Upload files**
2. ลากไฟล์ `index.html` ที่ดาวน์โหลดมาวางลงในหน้า
3. กด **Commit changes**

### ขั้นตอนที่ 3 — เปิด GitHub Pages

1. ไปที่แท็บ **Settings** (ด้านบนของ repository)
2. เลื่อนลงที่เมนูซ้ายมือ กด **Pages**
3. ในส่วน **Source** เลือก **Deploy from a branch**
4. ในส่วน **Branch** เลือก `main` แล้วเลือก `/ (root)`
5. กด **Save**
6. รอประมาณ 1-2 นาที แล้ว refresh หน้า จะเห็น URL ปรากฏด้านบน

### ขั้นตอนที่ 4 — แชร์ลิงก์

URL จะมีรูปแบบ:

```
https://[ชื่อผู้ใช้].github.io/kmeans-explorer/
```

คัดลอก URL นี้ส่งให้นิสิตได้เลย ใช้งานได้ทันทีผ่าน browser โดยไม่ต้องติดตั้งอะไรเพิ่ม

## หมายเหตุ

- ไฟล์นี้เป็น standalone HTML ไม่ต้อง build หรือติดตั้ง dependencies ใด ๆ
- ใช้งานได้ทั้งบน desktop และ mobile browser
- ต้องเชื่อมต่ออินเทอร์เน็ตเพื่อโหลด font และ React library จาก CDN
