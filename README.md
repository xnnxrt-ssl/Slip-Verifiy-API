# Rachin Slip Verify API (v2.2.0)

## 📲 การเชื่อมต่อ API (สำหรับนักพัฒนา)
ทุกการเรียกใช้งาน API ด้านล่างนี้ ต้องแนบ Header: **`x-api-key`**
api key สามารถทักมาขอได้ที่: [Instargram](https://www.instagram.com/n.taraputtasi/)

### 1. ตรวจสอบสลิปจากรูปภาพ
- **URL:** `POST https://slip-verify.scyw.site/api/verify/bank/image`
- **Type:** `multipart/form-data`
- **Parameter:** `image` (ไฟล์สลิป)

### 2. ตรวจสอบสลิปจากข้อความ QR (Payload)
- **URL:** `POST https://slip-verify.scyw.site/api/verify/bank`
- **Type:** `application/json`
- **Body:** `{"payload": "รหัสQR Code"}`

### 3. ตรวจสอบข้อมูลอื่นๆ
- **Status API:** `GET https://slip-verify.scyw.site/api/health`, `https://slip-verify.scyw.site/api/health?apiKey=`
- **Status System:** `https://slip-verify.scyw.site/`

---
**Develop by xnnxrt-ssl**
