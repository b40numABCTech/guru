 Guru NUM
 ========
 
 * ต่อไปเวลาเขียน code ที่ต้อง concat string ถ้า เป็น method ที่เป็น thread safe ช่วยใช้ StringBuilder ส่วนที่ไม่ใช่ thread safe ใช้ StringBuffer ด้วยครับ อย่าใช้ String เฉยๆ ถ้าข้องใจดูตามลิงค์ด้านหลังนี้ครับ
 
 
 http://kaioa.com/node/59
 
 * DAO ผมแนะนำให้ประกาศเป็น Constant ไว้ครับ
  
ให้เป็น private static final String XXX = "select....."


MySQL
-----

* Search

```sh
use "like %SOMETHING%" instead of "="
```
