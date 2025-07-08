**Digital Temp & RH Sensor** เป็นอุปกรณ์สำหรับตรวจวัด อุณหภูมิและความชื้นสัมพัทธ์ในอากาศ ที่ใช้งานง่ายและให้ค่าที่แม่นยำ โดยภายในโมดูลนี้ใช้ชิปตระกูล SHT3x (เช่น SHT30 หรือ SHT31) ซึ่งได้รับความนิยมอย่างแพร่หลายในงานวิทยาศาสตร์สิ่งแวดล้อม งานสมาร์ทโฮม และระบบตรวจวัดอัตโนมัติต่าง ๆ

**ข้อมูลเฉพาะ Digital Temp & RH Sensor**
|Parameter|Value|
|-|-|
|**Model**|SHT30 digital temp & RH sensor|
|Temperature Range|–40 °C ถึง +125 °C|
|Temperature Accuracy|±0.2 °C|
|Humidity Range|0 – 100 % RH|
|Humidity Accuracy|±2 % RH|
|Supply Voltage|2.4 – 5.5 V|

**ชุดอุปกรณ์ที่จำเป็น**
- เซ็นเซอร์วัดอุณหภูมิและความชื้น (Digital Temp & RH Sensor) จำนวน 1 ตัว
- สาย Grove สำหรับใช้งานร่วมกับ GoGo Board 1 เส้น
- คอมพิวเตอร์หรือแท็บเล็ต
- สมองกลฝังตัว GoGo Board และสาย USB-C

**วิธีการใช้เซ็นเซอร์**
**- การเชื่อมต่ออุปกรณ์เบื้องต้น**
1. เชื่อมต่อบอร์ด GoGo Board กับเครื่องคอมพิวเตอร์ ใช้สาย USB-C เชื่อมต่อระหว่างบอร์ด GoGo Board กับโน้ตบุ๊ค ตามภาพด้านล่าง
<img src="https://github.com/thegogoboard/gogodoc/blob/main/Automation/Image%20(91).jpg?raw=true" alt="Description" width="73%">

2. เชื่อมต่อเซ็นเซอร์เข้ากับบอร์ด เสียบสายสัญญาณของเซ็นเซอร์เข้ากับหัวแปลง Grove จากนั้นเชื่อมต่อกับช่องสำหรับเซ็นเซอร์บนบอร์ด GoGo Board ดังนี้
<img src="https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/sensor/Temperature.gif?raw=true" alt="Description" width="73%">

**- การเขียนโปรแแกรม**
- ผู้เรียนสามารถเข้าใช้งานเว็บไซต์ [GoGo Code](https://code.gogoboard.org/#/program) เพื่อเขียนโปรแกรมควบคุมการทำงานของอุปกรณ์ โดยสามารถเริ่มต้นจากการเขียนโค้ดเพื่อเก็บข้อมูลอุณหภูมิแบบออฟไลน์ (Offline Mode) ได้ตามตัวอย่างต่อไปนี้
<img src="https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/sensor/Code-Temp.gif?raw=true" alt="Description" width="73%">

- เมื่อผู้เรียนดำเนินการบันทึกข้อมูลอุณหภูมิเสร็จสิ้นแล้ว หากต้องการนำข้อมูลออกมาใช้งาน สามารถดำเนินการได้ดังนี้


**- ตัวอย่างโปรแกรม**

::: details ข้อมูลเพิ่มเติม
  
  **ข้อควรระวัง**
- หลีกเลี่ยงการดัดแปลงสายไฟหรือเชื่อมต่อผิดขั้ว อาจทำให้อุปกรณ์เสียหาย
- อย่าจับบริเวณหัวเซ็นเซอร์ขณะทำงาน อาจส่งผลต่อความแม่นยำในการตรวจจับ
- หากเซ็นเซอร์ไม่ทำงาน ควรตรวจสอบแรงดันไฟฟ้าและการเชื่อมต่อสายอีกครั้ง
:::
