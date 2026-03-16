# ⛽ แผนที่ปั๊มน้ำมัน พิษณุโลก

แผนที่ interactive ปั๊มน้ำมันในจังหวัดพิษณุโลก รัศมี 15 กม. จากใจกลางเมือง  
รวม **26 สาขา** — PTT · PT · Shell · Bangchak · Caltex

🔗 **ดูแผนที่ออนไลน์**: `https://flurep678.github.io/phitsanulok-gasmap`

---

## ฟีเจอร์
- 🗺 แผนที่จริงจาก OpenStreetMap
- 🔍 ซูมเข้า/ออกได้
- 🏷 กรองตามแบรนด์
- ⛽ แสดงประเภทน้ำมันแต่ละสาขา
- ⚡ แสดงสาขาที่มี EV Charging
- 📍 กดลิงก์เปิด Google Maps ได้

---

## วิธี Deploy บน GitHub Pages

### ขั้นตอนที่ 1 — สร้าง Repository
1. ไปที่ [github.com](https://github.com) แล้ว **Sign in**
2. คลิกปุ่ม **"+"** มุมบนขวา → **New repository**
3. ตั้งชื่อ: `phitsanulok-gasmap`
4. เลือก **Public**
5. คลิก **Create repository**

### ขั้นตอนที่ 2 — อัปโหลดไฟล์
**วิธีง่าย (ไม่ต้องใช้ Git):**
1. ในหน้า repository ที่เพิ่งสร้าง คลิก **"uploading an existing file"**
2. ลาก `index.html` และ `README.md` ไปวาง
3. คลิก **Commit changes**

**วิธีใช้ Git:**
```bash
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/phitsanulok-gasmap.git
git push -u origin main
```

### ขั้นตอนที่ 3 — เปิด GitHub Pages
1. ไปที่ **Settings** ของ repository
2. เมนูซ้าย เลือก **Pages**
3. Source → เลือก **Deploy from a branch**
4. Branch → เลือก **main** / **(root)**
5. คลิก **Save**
6. รอ 1–2 นาที จะได้ลิงก์:  
   `https://YOUR_USERNAME.github.io/phitsanulok-gasmap`

---

## แชร์บน Facebook
นำลิงก์ `https://YOUR_USERNAME.github.io/phitsanulok-gasmap`  
ไปวางบน Facebook ได้เลย — Facebook จะดึง preview อัตโนมัติ

---

## ข้อมูล
- แหล่งข้อมูล: Google Maps
- พื้นที่: จังหวัดพิษณุโลก รัศมี 15 กม.
- อัปเดต: 2026
