คำสั่งสำหรับการสร้างโฟลเดอร์
1. mkdir -p components/Sensors
2. mkdir -p components/Display

คำสั่งสำหรับการสร้างไฟล์
1. touch components/Sensors/CMakeLists.txt
2. touch components/Sensors/sensor.h
3. touch components/Sensors/sensor.c
4. touch components/Display/CMakeLists.txt
5. touch components/Display/display.h
6. touch components/Display/display.c

คำสั่งสำหรับการ build
build - idf.py build

รูปภาพแสดงผลลัพธ์ก่อนการเพิ่ม Display
<img width="923" height="802" alt="Screenshot 2025-08-14 222549" src="https://github.com/user-attachments/assets/646d0248-ae3f-4b4b-8873-2f26663eb26a" />

รูปภาพแสดงผลลัพธ์หลังการเพิ่ม Display
<img width="926" height="664" alt="Screenshot 2025-08-17 141104" src="https://github.com/user-attachments/assets/4f0f1104-4d40-44ed-a6c6-ebbcb4bb4f93" />

