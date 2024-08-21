
## หลังจากที่ Clone Git มาแล้ว สิ่งที่ต้องทำ111

**1. เพิ่ม file keystore เข้าใน Project**
- สามารถโหลดได้จาก  *[กด Link ที่นี่](https://drive.google.com/drive/folders/1o7UomGtm2xrXmUk9LlWDjDvNEHmC_oB8)*

- หลังจากโหลด เสร็จ วางใน เข้าไปไว้ใน project > app- มี sit.keystore, beta.keystore, salehere.keystore


**2. เพิ่ม key เข้าไปใน local.properties มี Data ที่เพิ่มมีดังนี้**
 ```
 HEADER_KEY_SIT = I86...   
 HEADER_KEY_UAT = TYN...   
 HEADER_KEY_PROD = Gpn...  
 OMISE_KEY_TEST = pkey_test_...   
 OMISE_KEY = pkey_...  
 MAPS_API_KEY=AIzaSy...8uRY
```
**หมายเหตุ** : ต้องส่งต่อจาก Dev สู่ Dev เท่านั้น ถ้าไม่มี ให้ไปหาใหม่

_________________

## UnitTest Automate
เอกสารเกี่ยวกับ UnitTest ของ Android : [Link](https://app.clickup.com/25670239/v/dc/rfcjz-2742/rfcjz-9822)



## UITest  Automate:
เอกสารเกี่ยวกับ UI Test ของ Android ที่ใช้ Katalon: [Link](https://app.clickup.com/25670239/v/dc/rfcjz-2742/rfcjz-9822)

วีดีโอผลเทส UI Test ของ Android ที่ใช้ Katalon: [Link](https://drive.google.com/drive/folders/13lpL6n3l1VZcbtxhD6M4uENSD8UWH3LS?usp=drive_link)
