**Intro to Data Mining**

**_Getting To Know Your Data_**

**Data**

  Data ที่จะได้ใช้ส่วนใหญ่ในวิชานี้จะมีรูปแบบดังนี้ ซึ่งอยู่ในรูปของเมทริกซ์ ในแนวนอน คือ Role และในแนวตั้ง คือ Column หรือจะเรียก แถวกับหลักก็ได้
  
![ป](https://user-images.githubusercontent.com/76931027/126058810-c8afe8ff-6a7a-463b-add9-0511ac3cbcd6.PNG)

  เมทริกซ์ 1 มิติ มีแค่ด้านยาว
  
  ![ผ](https://user-images.githubusercontent.com/76931027/126058855-9267c9ba-8fb7-4cd8-ae96-f7d00834764f.PNG)

  เมทริกซ์ 2 มิติ มีด้านกว้างและยาว
  
  ![แ](https://user-images.githubusercontent.com/76931027/126058866-94857e6e-cff5-4851-b686-5a0a57884356.PNG)

  เมทริกซ์ 3 มิติ มีด้านกว้าง ยาวและลึก
  
  ![อิ](https://user-images.githubusercontent.com/76931027/126058877-b82fff87-e449-4d83-b097-e8ee69840b50.PNG)

  เมทริกซ์ 4 มิติ มีด้านกว้าง ยาว ลึกและหนา
  
  แนวตั้ง เรียก Attribute คือคุณสมบัติที่ใช้อธิบายข้อมูล แนวนอน เรียก Record
  
  **Data Objects And Attribyte Types**
  
  Data ที่มีหลายตารางที่มีความสัมพันธ์กัน ลักษณะคล้ายกับการเก็บข้อมูลใน Database
  
  **_Record Data_**
  
  ![q](https://user-images.githubusercontent.com/76931027/126058994-bf236140-0b05-497c-8629-a04673e682a9.PNG)

   ตาราง Term-Freequency เป็นตารางที่ใช้เก็บข้อมูลที่เป็น Text
  
  **_Graphs And Network_**
  
  ![w](https://user-images.githubusercontent.com/76931027/126059061-3b11d560-950b-4e64-b4c0-be2bad22f221.PNG)

   จะเป็นการยอกว่าจุดนี้เชื่อมกับอะไร อย่างเช่น ข้อมูลในโซเชียล เว็บไซต์ต่างๆ แผนที่รถไฟฟ้า ที่มีการเชื่อมต่อกันไปอย่างไรบ้าง
    
  **_Ordered Data_**
   
   ![e](https://user-images.githubusercontent.com/76931027/126059130-7e1150dd-f34b-4b0d-ba71-298734229e40.PNG)
   
   เป็นข้อมูลที่มีเวลาเข้ามาเกี่ยวข้องเหมือนกัน ทำการแปลง Data เป็นตัวเลข
    - Time-Series เช่น ราคาหุ้น แต่ละวันที่มีราคาขึ้นลงไปมา
    - Sequential เช่น ข้อมูลที่ไม่สามารถสลับตำแหน่งหรือลำดับกันได้
    
   **_Spatial, Image And Multimedia Data_**
  
  ![r](https://user-images.githubusercontent.com/76931027/126059191-9527c874-8fb8-4e83-b241-39feb0106c78.PNG)

   เป็นข้อมูลที่มีเวลาเข้ามาเกี่ยวข้อง 
    
   - Vedio เช่น วีดิโอ โดยทำการเอารูปหลายรูปมาซ้อนกัน เป็นรูปที่ 1 ทับรูปที่ 2 ทับรูปที่ 3 ไปเรื่อยๆ(เหมือนรูปสามารถเคลื่อนไหวได้(เรียกว่า Cartoon Making))
   - Image เช่น รูปภาพ ซึ่งจะมีด้านกว้างกับยาว ซึ่งอาจจะกำหนดเป็นพิกัด x,y โดยแต่ละตัวจะมีสีบอกจุด
   - Spatial เช่น แผนที่ ซึ่งจะมีการกำหนดจุดพิกัด x,y โดยอาจจะกำหนดสีให้แต่ละพิกัดจังหวัด
    
  **Important Characeristics Of Structered Data**
  
  **_Dimensionality_**
    
   Curse Of dimensionality ดูว่า Data มี Dimension เท่าไรเป็นอย่างไร
    
   **_Sparsity_**
   
   Only Presence Counts สนใจแค่ที่ที่มีข้อมูล
    
   **_Resolution_**
   
   Patterns Depend On The Scale ความละเอียดในการเก็บข้อมูล
    
   **_Distribution_**
   
   Centrality And Dispersion การกระจายตัวของ Data โดยการวัดค่ากลางของ Data 
    
   **Data Object**
   
   ![t](https://user-images.githubusercontent.com/76931027/126059230-660579be-98a2-4cea-85db-05cc5b3ee915.PNG)

   - Data Sets ประกอบด้วย Data Object หลายๆ ตัวมารวมกัน
    
      Data Set คือ set ของข้อมูลหลายๆ ตัวมารวมกัน
    
   - Data Object คือข้อมูลแแต่ละตัวประกอบด้วย Entity ของแต่ละอัน 
    
   - Also called sample,examples,instances,data points,objects,tues ***สำคัญ***
    
      มีความหมายเดียวกันทั้งหมด คือ ข้อมูลที่เป้น Data 1 จุดที่อยู่ในแนวตั้ง (Data 1 จุด คือ Data point)
    
   - ข้อมูลจะถูกอธิบายด้วย Attributes
    
   - ใน Database ที่จะนำมาทำคือ Rows > Data, Column > Attributes
    
   **Attributes**
   
   ![y](https://user-images.githubusercontent.com/76931027/126059248-66df3e01-88cf-48aa-bcbc-c6170cd2ee04.PNG)

   คือ คุณสมบัติที่ใช้อธิบายข้อมูลแต่ละตัว อาจจะเรียกว่า Dimension, Features, Varibles 
    
   **_Type_**
    
   ชนิดของข้อมูลของ Attribute คือ
      
   - Norminal คือ ข้อมูลที่เป็นชื่อ(นามบัญญัติ) เช่น สีแดง สีเขียว
   - Binary คือ ข้อมูลที่มีแค่ 2 ค่า เช่น True Fale
   - Ordinal คือ ข้อมูลที่สามาารถเรียงลำดับได้ เช่น ป.1, ป.2, ป.3
   - Numeric คือ ข้อมูลที่เป็นตัวเลข
      - Interval-Scaled 
      - Ratio-Scaled
    
   **Attribute Types**
   
   ![u](https://user-images.githubusercontent.com/76931027/126059280-0e4edd9e-81a5-4fff-8a2a-d42b5c272614.PNG)

   **_Norminal_**
      
   ข้อมูลที่เป็นการบอกกลุ่ม บอกสถานะ เป็นชื่อของสิ่งของ เช่น สีผม, สถานะการแต่งงาน, อาชีพ, ID, Zip, Code
   
   **_Binary_**
      
   คือ ข้อมูล Norminal เพียงแต่มี 2 สถานะ เช่น Yes/No 
      
   - Symmetric Binary คือสมมาตรกัน เช่น ชอบกินโค้กหรือเปปซี่ (ในข้อมูลเก่าเป็นเพศ)
   - Asymmetric Binary คือไม่สมมาตรกัน เช่น เป็นเอดส์ไหม
        
   **_Ordinal_**
      
   คือ ข้อมูลที่มีความหมายสามารถนำมาเรียงลำดับได้ แต่จะไม่รู้ว่ามีค่าต่างกันมากน้อยแค่ไหน เช่น ขนาดใหญ่ ขนาดกลาง ขนาดเล็ก เกรด 
      
  **์Numeric Attribute Types**
  
  ![i](https://user-images.githubusercontent.com/76931027/126059306-2ba0a7ec-7b9e-4589-8e0b-462b43edb525.PNG)

   ข้อแตกต่างกัน คือ มี 0 แท้ และไม่มี 0 แท้
  
  มี 0 แท้ คือ 0 ที่ไม่มีค่าเลย เช่น มีดินสอ 0 แท่ง คือ ไม่มีดินสอ
   
  ไม่มี 0 แท้ คือ 0 องศา คืออากาศที่ 0 องศาที่หนาวกว่า 1 องศา
  
  **_Interval_**
      
   ข้อมูลที่ไม่มี 0 แท้ เช่น อุณหภูมิ
              
  **_Ratio_**
      
   ข้อมูลที่มี 0 แท้ เช่น ความยาว เงิน จำนวนวนับ
      
 **Discete VS. Continuous Attributes**
 
 ![o](https://user-images.githubusercontent.com/76931027/126061943-0d836837-76c0-43df-88db-145be6f424ee.PNG)

  **_Discete Attribute_**
  
  คือ ข้อมูลที่ไม่ต่อเนื่องกัน(ไม่มีค่าตรงกลาง) เช่น 1,2,3 ซึ่งไม่มีค่าอยู่ระหว่าง 1-2 เช่น Zip Code,อาชีพ,Binary เนื่องจากเป็นข้อมูลที่มีเพียง 2 ค่าซึ่งไม่มีค่ากลาง
  
  **_Continuous Attribute_**  
  
   คือ ข้อมูลที่ต่อเนื่องกัน(มีค่าตรงกลาง) โดยข้อมูลส่วนใหญ่เป็นจำนวนจริง เช่น ส่วนสูง 180,181.5,182
    
 **Basic Statistical Descriptions Of Data**
 
 ![p](https://user-images.githubusercontent.com/76931027/126061965-92bc69cc-97b8-4211-b8fb-380e986b1ad3.PNG)

   เป็นการดูค่าทางสถิติ โดยการใช้ค่ากลางของข้อมูลแทน ค่ากลางทางสถิติมีทั้งหมด 3 ชนิด คือ ค่าเฉลี่ย ค่ามัธฐาน ค่าฐานนิยม 
    
  **_Movation_**
  
   คือ ค่ากลางของข้อมูล คือ ค่าเฉลี่ย ค่ามัธฐาน ค่าฐานนิยม และ Spread คือ ถ้าเอาค่าทั้งหมดมา Plot ค่าจะแตกต่างมากน้อยแค่ไหน
  
  **_Data Dispersion Characteristcis_**
  
   ค่าที่นิยมนำมาใช้ คือ ค่ากลาง,มากที่สุด,ต่ำสุด,Quantile,Outlines,Varaiance
    
  **_Numerical Dimensions_**
  
 **Measuring The Central Tendency**
 
 ![a](https://user-images.githubusercontent.com/76931027/126061990-5dc80311-a839-4f19-8356-de10c2d4408f.PNG)

 **_Mean,Median,Mode_** ควรให้ความสำคัญ
 
  เนื่องจาก Attribute บางอย่างก็ไม่สามารถนำมาหาได้ เช่น Attribute ที่ไม่ใช้ตัวเลข ซึ่งเมื่อนำมา บวก ลบ คูณ หาร กันแล้วไม่มีความหมาย เช่น ID ซึ่งเป็นไปไม่ได้
หรือบางอย่างเองก็สามารถหา Median ได้แต่หา Mean ไม่ได้ เช่น ค่าที่เป็น Ordinal ซึ่งสามารถเรียงลำดับได้ จึงหา Median ของ Attribute ได้ หรือค่า Mode ซึ่งไม่สนใจว่าจะบวก ลบ คูณ หาร หรือเรียงลำดับได้ เพียงแค่รู้ว่าลำดับไหนมีค่าซ้ำกันมากที่สุดก็จะนำค่านั้นมา
