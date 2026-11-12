# 👖 DenimSync POS - ระบบขายหน้าร้าน คลังสินค้าแยกสาขา & Denim CRM Loyalty

## 🌐 ลิงก์ระบบใช้งานจริงบน Cloud (ออนไลน์ถาวร 24 ชม. ไม่มีวันหมดอายุ)
- **URL กลางระบบ:** https://hetzelliedberg-oss.github.io/jeans-around-pos/
- **สาขาขอนแก่น:** https://hetzelliedberg-oss.github.io/jeans-around-pos/?branch=khonkaen
- **สาขาโคราช:** https://hetzelliedberg-oss.github.io/jeans-around-pos/?branch=korat
- **สาขาอุดรธานี:** https://hetzelliedberg-oss.github.io/jeans-around-pos/?branch=udon
- **GitHub Repo (สำหรับอัปเดตโค้ดต่อบน Mac):** https://github.com/hetzelliedberg-oss/jeans-around-pos

## 🔑 ข้อมูลเข้าสู่ระบบ (PIN)
- **เจ้าของร้าน (Owner):** PIN `0929` (สิทธิ์เต็ม ปรับแต้ม ลบสมาชิก Reconcile สต็อก)
- **พนักงานทดลอง กีฟ (Gift):** PIN `1234` (สิทธิ์: ขายหน้าร้าน, เพิ่มสินค้า, สร้างบาร์โค้ด, โอนย้ายสต็อก, ดูสต็อกทุกสาขา)

## 🌟 ฟีเจอร์ใหม่ล่าสุดที่อัปเกรด
1. **Denim Club CRM & Member Retention:**
   - 🥉 Blue Denim (0–2,999฿, แต้ม 1.0x)
   - 🥈 Selvedge Silver / ริมแดง (3,000–7,999฿, แต้ม 1.5x + ตัดลูกโซ่ฟรี)
   - 🥇 Raw Indigo Gold / ผ้าดิบทองคำ (8,000฿+, แต้ม 2.0x + รุ่น Limited + ดูแลตลอดชีพ)
   - แคตตาล็อกแลกของรางวัล 5 ชนิด (ตัดลูกโซ่, พวงกุญแจริมแดง, ส่วนลด 150฿, กระเป๋ายีนส์ 14oz, กางเกงยีนส์ฟรี 1 ตัว)
2. **LINE OA Integration (@denimsync):**
   - Pop-up QR Code ชวนลูกค้าแอดไลน์ในหน้าแคชเชียร์
   - QR Code สแกนเช็คแต้มท้ายใบเสร็จ
   - ปุ่มคัดลอกใบเสร็จส่งเข้าแชท LINE 1-คลิก
3. **Multi-Branch Real-Time Stock Matrix:**
   - ตารางเปรียบเทียบสต็อก 3 สาขาแบบแจกแจงทุกไซส์ (S-4XL)
4. **Physical Stock Take & Grill Audit Engine:**
   - ตรวจนับสต็อกจริงหน้าร้าน vs ข้อมูลในระบบ
   - วิเคราะห์ส่วนต่าง ขาด/เกิน และมูลค่าเงินเสียหาย (THB) อัตโนมัติ
   - เลือกระหว่างบันทึกรายงานอย่างเดียว หรือ ปรับสต็อกในระบบให้ตรงจริง (Reconcile)

## 💻 วิธีนำไปรันต่อบน MacBook
1. คัดลอกไฟล์ `DenimSync_POS_Latest.zip` หรือโฟลเดอร์นี้ไปไว้บนเครื่อง MacBook
2. แตกไฟล์แล้วดับเบิลคลิกเปิด `index.html` บน Safari, Chrome หรือ Brave ได้ทันทีโดยไม่ต้องติดตั้งเซิร์ฟเวอร์
3. ข้อมูลจะซิงค์ตรงกับระบบ Cloud กลางและทุกสาขาอัตโนมัติ
