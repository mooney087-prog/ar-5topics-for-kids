# AR English – 5 Fun Categories (Primary 3)

## ไฟล์สำคัญ
- `index.html` เกมหลัก
- `assets/cover.png` ภาพหน้าปก
- `assets/*.svg` ภาพคำศัพท์ 30 ภาพ
- `hiro-marker.png` มาร์กเกอร์สำหรับพิมพ์หรือเปิดบนอีกจอ

## วิธีอัปโหลดขึ้น GitHub Pages
1. สร้าง Repository ใหม่ หรือเปิด Repository เดิม
2. อัปโหลด `index.html`, โฟลเดอร์ `assets` และ `hiro-marker.png` ไว้ระดับบนสุด
3. ไปที่ Settings → Pages
4. เลือก Deploy from a branch → `main` → `/root` → Save
5. เปิดลิงก์ GitHub Pages ด้วย Chrome บนโทรศัพท์และกด Allow camera

## วิธีเล่น
1. พิมพ์ `hiro-marker.png` หรือเปิดภาพนี้บนคอมพิวเตอร์/แท็บเล็ตอีกเครื่อง
2. เปิดเกมบนโทรศัพท์
3. เลือกด่านและส่องกล้องไปที่ HIRO Marker
4. ภาพจะปรากฏเหนือ Marker แล้วนักเรียนเลือกคำศัพท์ให้ตรงกับภาพ
5. เมื่อจบด่าน ระบบจะปลดล็อกด่านถัดไปอัตโนมัติ

## หมายเหตุ
- กล้องจะทำงานเมื่อเว็บเปิดผ่าน HTTPS เช่น GitHub Pages
- หากภาพ AR ไม่ขึ้น ให้เพิ่มแสง วาง Marker ให้เรียบ และถือกล้องห่างประมาณ 25–40 ซม.
- เกมบันทึกด่านที่ผ่านไว้ในอุปกรณ์ด้วย localStorage
