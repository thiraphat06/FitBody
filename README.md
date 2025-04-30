# FitBody
ชื่อ - นามสกุล (Full Name): Thiraphat Kongkan

รหัสนักศึกษา (Student ID): 6631503023

ตอนเรียน (Section): 1

ชื่อแอป (App Name): FitBody

Framework ที่ใช้ (Framework Used): React Native

ลิงก์ GitHub Repository: https://github.com/thiraphat06/FitBody

ลิงก์ไฟล์ติดตั้ง (APK/IPA): -
----------------------------------------------------------------

# 1. การออกแบบแอป | App Concept and Design (2 คะแนน / 2 pts)
1.1 ผู้ใช้งานเป้าหมาย | User Personas

Persona 1:  

- ชื่อ: มุก  
- อายุ: 23 ปี  
- อาชีพ: พนักงานออฟฟิศ  
- ความต้องการ: อยากมีแอปที่ช่วยแนะนำท่าง่ายๆ สำหรับยืดเส้นยืดสายระหว่างทำงาน

Persona 2:  

- ชื่อ: บอล
- อายุ: 21 ปี
- อาชีพ: นักศึกษา
- ความต้องการ: ต้องการออกกำลังกายเบาๆ ระหว่างเรียนออนไลน์

1.2 เป้าหมายของแอป | App Goals

- แนะนำท่าออกกำลังกายง่ายๆ ในแต่ละวัน
- มีการนับถอยหลังเวลาต่อท่า
- จบ session แล้วมีข้อความให้กำลังใจ
- ใช้งานง่าย เหมาะกับทุกเพศทุกวัย
  
1.3 โครงร่างหน้าจอ / Mockup

หน้า 1: Home

โลโก้ FitBody

ปุ่มเลือกประเภทการออกกำลังกาย เช่น คาร์ดิโอ / ยืดกล้ามเนื้อ

ปุ่มเริ่ม session

หน้า 2: Exercise

แสดงชื่อท่าที่กำลังทำ

หน้า 3: Summary

แสดงผลว่าออกกำลังกายเสร็จแล้ว

ปุ่มกลับไปหน้าแรก





1.4 การไหลของผู้ใช้งาน | User Flow

เปิดแอป > เข้าหน้าหลัก (Home) > เลือกประเภทการออกกำลังกาย > กด "เริ่มออกกำลังกาย" > ทำจนครบท่าทั้งหมด > เข้าหน้าสรุปผล (Summary) > กลับสู่หน้าหลัก

----------------------------------------------------------------

# 2. การพัฒนาแอป | App Implementation (4 คะแนน / 4 pts)
2.1 รายละเอียดการพัฒนา | Development Details

เครื่องมือที่ใช้ / Tools used:

- React Native
- Expo
- Package: React-Navigation
  
2.2 ฟังก์ชันที่พัฒนา | Features Implemented
Checklist:

- [x] เลือกประเภทการออกกำลังกาย
- [x] แสดงผลสรุปหลังทำครบ
- [ ]  เพิ่มระบบนับถอยหลัง 
2.3 ภาพหน้าจอแอป | App Screenshots
แนบภาพหรือ URL (Attach images or image links):
![image](https://github.com/user-attachments/assets/dad7d36a-a2bd-4e93-930d-b56ed6a262fa)
![image](https://github.com/user-attachments/assets/775ebd6d-9714-4141-a039-e36d3b3b1799)
![image](https://github.com/user-attachments/assets/1bf6b030-27f2-4091-a082-059b3cbd99a0)

----------------------------------------------------------------

# 3. การ Build และติดตั้งแอป | Deployment (2 คะแนน / 2 pts)
3.1 ประเภท Build | Build Type

[x] Debug
[ ] Release
3.2 แพลตฟอร์มที่ทดสอบ | Platform Tested

[x] Android
[ ] iOS

3.3 ไฟล์ README และวิธีติดตั้ง | README & Install Guide
แนบไฟล์หรือคำอธิบายการติดตั้งแอป | Insert steps

1.เปิดเทอร์มินัลแล้วพิมพ์ npx expo start
2.สแกน QR Code ด้วย Expo Go เพื่อรันแอป
----------------------------------------------------------------

# 4. การสะท้อนผลลัพธ์ | Reflection (2 คะแนน / 2 pts)

-ได้เรียนรู้โครงสร้างการเขียน React Native จากศูนย์

-พบปัญหาเรื่อง navigation และ useEffect ซ้อนกัน

-หากมีเวลาเพิ่มจะเพิ่มระบบแสดงภาพแต่ละท่า + เพิ่มเสียง



----------------------------------------------------------------

# 5. การใช้ AI ช่วยพัฒนา | AI Assisted Development (Bonus / ใช้ประกอบการพิจารณา)

Prompt:
“แอปออกกำลังกายง่ายๆ สำหรับนักศึกษา มีแค่ 3 หน้า”
ผลลัพธ์:
ได้แนวทางแอป FitBody ที่มี Home / Exercise / Summary

5.2 ใช้ AI ช่วยออกแบบ UI
Prompt:
“React Native layout for simple fitness app”
ผลลัพธ์:
โครงสร้างหน้าจอ พร้อมการจัดปุ่มและข้อความ

5.3 ใช้ AI ช่วยเขียนโค้ด
Prompt:
“Countdown timer for each exercise in React Native”
ผลลัพธ์:
ช่วยเขียน useEffect สำหรับนับถอยหลังอัตโนมัติ

5.4 ใช้ AI ช่วย debug
Prompt:
“useEffect loop when navigating React Native screen”
ผลลัพธ์:
ได้วิธีจัดการ clean up และ dependency ของ useEffect

5.5 ใช้ AI ช่วย Deploy
Prompt:
“How to run and test React Native app using Expo?”
ผลลัพธ์:
ได้คำสั่ง npx expo start และการใช้งาน Expo Go


