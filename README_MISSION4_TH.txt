AR Farm Tool Hero — ภารกิจที่ 4 (เวอร์ชันพื้นหลังมีลูกเล่น)

ลิงก์เว็บที่จะใช้:
https://chamchuree220538.github.io/ar-farm-tool-hero/mission4.html

ไฟล์ในชุด:
- mission4.html       เว็บ AR ด่านที่ 4
- target-card4.png    การ์ดภารกิจที่ 4 (มี QR จริงแล้ว)
- mission4-qr.png     QR จริงที่เปิด mission4.html
- watering-can.png    รูปบัวรดน้ำที่แสดงเป็น AR
- dry-plant.png       รูปต้นไม้เหี่ยว
- healthy-plant.png   รูปต้นไม้สดชื่น
- demo4.html          ทดลองคำถามโดยไม่เปิดกล้อง

จุดเด่นเวอร์ชันนี้:
- ฉากฟาร์มสดใส
- เมฆลอยและใบไม้ลอย
- กรอบสแกนกระพริบ
- ต้นไม้เหี่ยว -> สดชื่น เมื่อเลือกคำตอบถูก
- เอฟเฟกต์หยดน้ำและดาวฉลอง

ยังต้องทำ 1 ขั้นตอนก่อนอัปโหลดเว็บ:
1) เข้า MindAR Image Targets Compiler
   https://hiukim.github.io/mind-ar-js-doc/tools/compile/
2) อัปโหลด target-card4.png
3) กด Start
4) กด Download
5) เปลี่ยนชื่อไฟล์ที่ได้จาก targets.mind เป็น:
   targets4.mind

จากนั้นให้อัปโหลดไฟล์เหล่านี้เข้า Repository เดิม ar-farm-tool-hero:
- mission4.html
- targets4.mind
- target-card4.png
- mission4-qr.png
- watering-can.png
- dry-plant.png
- healthy-plant.png
(จะอัปโหลด demo4.html ด้วยก็ได้)

เมื่อ GitHub Pages deploy เสร็จ:
- สแกน QR บน target-card4.png
- เปิดเว็บ AR
- อนุญาตใช้กล้อง
- ส่องกลับไปที่การ์ดภารกิจที่ 4
- บัวรดน้ำ AR จะปรากฏ
- เด็กตอบ A/B/C
- คำตอบที่ถูกคือ B. บัวรดน้ำ
