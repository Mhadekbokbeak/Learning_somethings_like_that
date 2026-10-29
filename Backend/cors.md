# CORS 

## Standard from Cross-origin Resource sharing
*เมื่อ Client ต้องการเข้าถึงข้อมูบบางอย่างจาก server ต้องให้ backend ตรวจ CORS ก่อนว่าตรงกันให้ ซึ่งแยกออกอีกมาอีกว่าต้องมีกฎ SOP*

# SOP

## SOP Standard from Same-origin policy
*ประกอบไปด้วย 3 ส่วนๆ หลัก potocal เช่น http,https , host เช่น google.com , port เช่น 5000,443*
*ดังนั้น cors และ sop จึงเป็นการรักษาความปลอดภัยเว็บแต่ไม่ใช่ authentication เพื่อให้เว็บหนึ่งอ่านข้อมูลอีกเว็บ
หรือใช้ติดต่อกับฝั่ง server*
|:potocal||:host:||port:|
|http,https||google.com||5000,443|

# Should know
- http คือ วิธีสื่อสารระหว่าง client กับ server
- การจะสร้างหน้าเว็บและเชื่อมกับ backend เพื่อขอข้อมูลบางอย่างจาก server ต้อ
งผ่าน cors และเป็น same-origin
- CORS เป็นข้อจำกัดของ browser ใช้ควบคุมการเข้าถึงข้าม origin


