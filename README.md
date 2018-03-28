# ตัวอย่างการเรียก Open API ของ กลต

## Installation
Check ก่อนว่ามี Python Version 3 แล้วด้วย
```
python --version
```
หากไม่เคยลง Modules เหล่านี้มาก่อนให้รัน
```
pip install pandas openpyxl requests 
```
## การทำงาน
Script จะไปกวาด Id ของทุก บลจ และใช้ Id ของแต่ละ บลจ ไปกวาดกองทุนทั้งหมดของ บลจ นั้น ๆ จากนั้นเอา Id ของกองทั้งหมดไปหา Risk Spectrum
จากนั้น Merge ข้อมูลทั้งหมด และ Save ลง File Excel

Run script ด้วย
```
python AllRiskSpectrum.py
```

Happy Scripting~
