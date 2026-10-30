# JWT 
## JWT Standard from Json web token
ประกอบไปด้วยสามส่วนหลักๆ
| Header || Payload || Signature |
|:---||:---||:---|
- header for เพื่อให้รู้ว่าใช้วิธีไหนมา เช่น alg hs256,typ jwt
- payload มีข้อมูลอะไรของ user เช่น name,id,exp
- Signature ตรวจสอบว่ายังน่าเชื่อถือไหม ประกอบไปด้วย header + payload + jwt secret