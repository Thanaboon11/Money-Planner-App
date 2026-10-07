MONEY PLANNER APP — แอปวางแผนการเงินแบบ Offline-first + Google Sheets

ไฟล์ชุดนี้พร้อมนำขึ้น GitHub Pages ได้ทันที

การเชื่อม Google Sheets (ทำครั้งเดียว)
1) สร้าง Google Sheet ใหม่ 1 ไฟล์
2) ไปที่ Extensions > Apps Script
3) ลบโค้ดเดิม แล้ววางโค้ดทั้งหมดจากไฟล์ Code.gs
4) กด Run ที่ฟังก์ชัน setupMoneyPlannerApp หนึ่งครั้ง และอนุญาตสิทธิ์ Google
5) กด Deploy > New deployment > Web app
   Execute as: Me
   Who has access: Anyone
6) กด Deploy แล้วคัดลอก Web app URL ที่ลงท้าย /exec
7) เปิดแอป Money Planner App > ตั้งค่า > วาง URL > “บันทึกและทดสอบการเชื่อมต่อ”

หลังจากนั้นไม่ต้องตั้งค่าใหม่ทุกครั้ง
- ไม่มีอินเทอร์เน็ต: แอปบันทึกในเครื่องและใช้งานต่อได้
- มีอินเทอร์เน็ต: แอปซิงก์ Google Sheets
- เปลี่ยนเครื่อง: ตั้ง URL เดิมเพื่อใช้ฐานข้อมูลชีตเดิม

ติดตั้งบน Android: เปิดเว็บด้วย Chrome > Install app / เพิ่มไปยังหน้าจอหลัก
ติดตั้งบน iPad/iPhone: เปิดด้วย Safari > Share > Add to Home Screen

หมายเหตุ: Google กำหนดให้เจ้าของบัญชีเป็นผู้อนุญาตและ Deploy Apps Script เอง จึงเป็นขั้นตอนที่ไม่สามารถใส่ไว้ใน ZIP ให้ข้ามได้
