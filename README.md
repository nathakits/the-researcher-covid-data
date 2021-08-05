# The Researcher COVID data
![bot-taks-scheduler](https://github.com/porames/the-researcher-covid-data/workflows/bot-taks-scheduler/badge.svg)  
  
Automated data scraper for Thailand COVID-19 data  

## ข้อมูลวัคซีน
- [การฉีดวัคซีนรายจังหวัด แยกตามชนิดวัคซีน](https://raw.githubusercontent.com/wiki/porames/the-researcher-covid-data/vaccination/provincial-vaccination-by-manufacturer.json)
- [การฉีดวัคซีนเข็ม 1 รายจังหวัด](https://raw.githubusercontent.com/wiki/porames/the-researcher-covid-data/vaccination/1st-dose-provincial-vaccination.json)
- [การฉีดวัคซีนเข็ม 2 รายจังหวัด](https://raw.githubusercontent.com/wiki/porames/the-researcher-covid-data/vaccination/2nd-dose-provincial-vaccination.json)
- [การฉีดวัคซีนเข็ม 3 รายจังหวัด](https://raw.githubusercontent.com/wiki/porames/the-researcher-covid-data/vaccination/3rd-dose-provincial-vaccination.json)
- [อัตราการฉีดวัคซีนของแต่ละผู้ผลิต](https://raw.githubusercontent.com/wiki/porames/the-researcher-covid-data/vaccination/vaccine-manufacturer-timeseries.json) เริ่มรายงานยอดรวมการฉีดวัคซีนของแต่ละผู้ผลิตวันที่ 2 กรกฎาคม 2021 เป็นต้นไป ข้อมูลก่อนหน้านั้นเป็นอัตราการฉีดวัคซีนรายวันแยกตามผู้ผลิตที่รวมแล้วอาจจะไม่ตรงกับรายงานอย่างเป็นทางการของกรมควบคุมโรค
- [อัตราการฉีดวัคซีนทั้งประเทศ](https://raw.githubusercontent.com/wiki/porames/the-researcher-covid-data/vaccination/national-vaccination-timeseries.json)

### ข้อควรรู้เกี่ยวกับข้อมูลการฉีดวัคซีน
- เข็ม 1 หมายถึงจำนวนคนที่ได้รับวัคซีนอย่างน้อย 1 เข็ม
- เข็ม 2 หมายถึงจำนวนคนที่ได้รับวัคซีนอย่างน้อย 2 เข็ม
- เข็ม 3 หมายถึงจำนวนคนที่ได้รับวัคซีนกระตุ้นเข็มที่ 3
- เซตของคนฉีดวัคซีนอย่างน้อย 2 เข็มเป็นเซตย่อยของคนฉีดวัคซีนอย่างน้อย 1 เข็ม เวลารายงานร้อยละการฉีดวัคซีนจะเอาเข็ม 1 มารวมกับเข็ม 2 ไม่ได้ (นะครับ 😏)

