# Chomthong Star Connext

หน้าเว็บสำหรับฝัง Google Apps Script Web app พร้อมลิงก์เปิดโดยตรง

## เปิดเว็บไซต์

Settings → Pages → Deploy from a branch → main → /(root) → Save

URL หลังเผยแพร่สำเร็จ: https://takahiro4-glitch.github.io/Chomthong-Star-Connext/

## ข้อกำหนดของ Apps Script

Web app ต้องอนุญาต iframe โดยใช้ HtmlService.XFrameOptionsMode.ALLOWALL และตั้งค่าสิทธิ์เข้าถึงให้ตรงกับผู้ใช้ที่ต้องการ ผู้พัฒนาต้องประเมินการป้องกันการหลอกคลิกเมื่อเปิด ALLOWALL

หากติดการเข้าสู่ระบบภายใน iframe ให้กดเปิดระบบในแท็บใหม่

การทำงานและข้อมูลยังอยู่ใน Apps Script และแหล่งข้อมูลเดิม การฝังไม่เพิ่มความเร็วหรือโควต้าของระบบ

ต้องตรวจสอบการเข้าสู่ระบบและการทำงานจริงด้วยบัญชีผู้ใช้งานหลังเปิด Pages
