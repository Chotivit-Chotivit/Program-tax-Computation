## คำนวณภาษีเงินได้บุคคลธรรมดาโดยใช้python

![image](https://github.com/Chotivit-Chotivit/Tax-calculation/assets/91452285/e9eb7de8-12e7-4e39-94a7-963f084e0ec8)



โดยโปรเเกรมนี้สามารถที่จะคำนวณเงินได้สุทธิ คำนวณหาอัตราภาษีของคุณโดยที่ไม่ต้องนั่งคำนวณเองเเละสามารถบอกถึงภาษีที่ต้องชำระทั้งหมดได้
เป็นprojectที่เกิดจากความสนใจในด้านการคำนวณเกี่ยวกับภาษีโดยได้ใช้สูตรการคำนวณหาภาษีที่ต้องชำระ 

ภาษีที่ต้องชำระ = [(เงินได้สุทธิของตนเอง - เงินได้สุทธิที่มากที่สุดของลำดับขั้นก่อนหน้า) X อัตราภาษี (%)] + ภาษีสะสมสูงสุดของลำดับขั้นก่อนหน้า

![Screenshot 2024-03-21 163750](https://github.com/Chotivit-Chotivit/Program-tax-Computation/assets/91452285/784bca20-6b19-4bd2-97e6-55df85b1873f)

![image](https://github.com/Chotivit-Chotivit/Tax-calculation/assets/91452285/92a0ae5d-54b0-429d-a2e1-f65367883265)


โดยมีตารางด้านบนเป็นตัวนำเข้ามาเเทนในตัวเเปรเเต่ละตัวเพื่อคำนวณหาภาษีที่ต้องชำระ

โดยมีสิ่งที่ต้องกรอก3อันเพื่อคำนวณหาภาษีที่ต้องชำระ
1.รายได้ทั้งปี
2.ค่าใช้จ่ายส่วนตัว
3.ค่าลดหย่อนทั้งหมด(โดยจะมีการให้กรอกประเถทของค่าลดหย่อนด้วย)

![Screenshot 2024-03-21 163842](https://github.com/Chotivit-Chotivit/Program-tax-Computation/assets/91452285/059ba36b-3afd-4cf0-b290-0ec9b10ca329)

เพื่อหาเงินได้สุทธิของตนเอง หลังจากนั้นโปรเเกรมจะทำการคำนวณจนได้ภาษีที่ต้องชำระ


## ตัวอย่างในการคำนวณ
ตัวเลขอ้างอิงที่นำมาใช้คำนวณในโปรเเกรม

![image](https://github.com/Chotivit-Chotivit/Program-tax-Computation/assets/91452285/8290040c-b365-4d25-94c8-d65ed72ef325)

ผลลัพธ์ที่ต้องได้ตามที่กรอกตามตัวเลขตามด้านบน(รายได้ทั้งปี:1000000 ค่าใช้จ่ายส่วนตัว:100000 ค่าลดหย่อน:60000)

![image](https://github.com/Chotivit-Chotivit/Program-tax-Computation/assets/91452285/b2b4cfe3-fbe4-4b5b-b8d1-731498bf7640)


![image](https://github.com/Chotivit-Chotivit/Program-tax-Computation/assets/91452285/ec947ff4-74f1-400f-a43e-7a059fc683e5)
ผลลัพธ์ที่ได้โดยใช้โปรเเกรมคำนวณ (โดยได้กรอง รายได้ทั้งปี:1000000 ค่าใช้จ่ายส่วนตัว:100000 ค่าลดหย่อน:60000)

## กรณีที่มีค่าลดหย่อนมากกว่า1ค่าลดหย่อน
![image](https://github.com/Chotivit-Chotivit/Program-tax-Computation/assets/91452285/c02fe78a-4d45-4bab-944e-7153ff99b124)
โดยได้กรองให้มีจำนวณการลดหย่อนเป็น2โดยโปรเเกรมจะทำการถามวนซ้ำ2รอบเพื่อเก็บค่าของค่าลดหย่อนของทั้ง2ประเภทกับเก็บข้อมูลประเภทค่าลดหย่อน

## saveเป็นexcel
ถ้าผู้ใช้ต้องการเก็บข้อมูลที่ใช้คำนวณเเละภาษีที่ต้องชำระทั้งหมดเป็นexcel ในโปรเเกรมของเราสามารถsaveไฟล์เป็นexcelได้โดยจะมีการถามว่าต้องการsaveเป็นไฟล์excelมั้ย
หากต้องการให้พิมพ์ yes หรือ ใช่ หรือ /
หากไม่ให้พิมพ์ no หรือ * หรือ x หรือ ไม่

![image](https://github.com/Chotivit-Chotivit/Program-tax-Computation/assets/91452285/c15b5017-1720-40c8-b97c-6f53452ddc34)

ก็จะได้ไฟล์excelที่ชื่อcatตามที่เราได้กรองไว้

![image](https://github.com/Chotivit-Chotivit/Tax-calculation/assets/91452285/dac0c655-f2b4-4c5d-9da5-9c5738192a74)


![image](https://github.com/Chotivit-Chotivit/Program-tax-Computation/assets/91452285/f365f99b-09aa-47a8-b587-335f718056b7)



1/4/2024 by chotivit busamongkol









