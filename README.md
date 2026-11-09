# Campus Marketplace (Lab 9 - Firebase Auth & Cloud Firestore)

Mobile Software Development (MDSD) - Lab 9

## Overview
แอปพลิเคชัน Campus Marketplace สำหรับซื้อ-ขายสินค้าภายในมหาวิทยาลัย พัฒนาด้วย Flutter รองรับ:
- **Authentication**: Email/Password และ Google Sign-In ผ่าน Firebase Authentication
- **Remote Database**: ดึงและโพสต์ประกาศสินค้าขึ้น Cloud Firestore พร้อม Security Rules จำกัดสิทธิ์เจ้าของประกาศ
- **Local Database**: บันทึกรายการโปรดและร่างประกาศสินค้าลงฐานข้อมูลออฟไลน์ด้วย Drift (SQLite)
- **Offline Resilience**: รองรับการใช้งานฟีเจอร์ออฟไลน์และจัดการ Error ได้อย่างถูกต้องเมื่อขาดการเชื่อมต่อ

## Tech Stack
- **Framework**: Flutter 3.x (Dart 3.x)
- **Backend / Cloud**: Firebase Authentication, Cloud Firestore, Firebase Storage
- **Local Database**: Drift, SQLite
- **Network**: HTTP (Fake Store API), Cloud Firestore SDK

## Getting Started
1. ติดตั้ง Dependencies:
   ```bash
   flutter pub get
   ```
2. รันแอปพลิเคชัน:
   ```bash
   flutter run
   ```

## Labsheet
ดูใบงานและการทดสอบ Checkpoint ทั้งหมดได้ที่:
[imnotppee/MDSD-Lab9-Labsheet-2026](https://github.com/imnotppee/MDSD-Lab9-Labsheet-2026)
