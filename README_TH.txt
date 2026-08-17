AR Farm Tool Hero — Mission 1

ชุดนี้ทำเว็บ AR ด่าน 1 ให้แล้ว เหลือสร้างไฟล์ targets.mind จากการ์ดเพียง 1 ครั้ง

ไฟล์
- index.html = เว็บ AR จริง
- target-card1.png = การ์ดที่ใช้เป็น Image Target
- hoe.svg = ภาพจอบ AR
- demo.html = ทดลองเกมคำถามโดยไม่เปิดกล้อง

ทำต่อ 4 ขั้นตอน
1) เปิด MindAR Image Targets Compiler
   https://hiukim.github.io/mind-ar-js-doc/tools/compile/

2) อัปโหลดไฟล์ target-card1.png แล้วกด Start

3) เสร็จแล้วกด Download จะได้ targets.mind
   นำ targets.mind มาไว้โฟลเดอร์เดียวกับ index.html

4) นำโฟลเดอร์ขึ้นเว็บ HTTPS เช่น GitHub Pages
   เปิดบนมือถือ > อนุญาตกล้อง > ส่องการ์ดภารกิจที่ 1

สิ่งที่จะเกิดขึ้น
- จอบ AR ลอยขึ้นบนการ์ด
- คำถามและตัวเลือก A/B/C ปรากฏ
- A. จอบ = ถูก + 2 ดาว
- B/C = ให้ลองใหม่
- มีปุ่มฟังคำใบ้ภาษาไทยด้วย speech synthesis

หมายเหตุ: เปิด index.html ตรงจากไฟล์มักใช้กล้องไม่ได้ ต้องเปิดผ่าน HTTPS หรือ localhost
