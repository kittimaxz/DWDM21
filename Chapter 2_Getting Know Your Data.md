**Intro to Data Mining**

**_Getting To Know Your Data_**

**Data**

  Data ที่จะได้ใช้ส่วนใหญ่ในวิชานี้จะมีรูปแบบดังนี้ ซึ่งอยู่ในรูปของเมทริกซ์ ในแนวนอน คือ Role และในแนวตั้ง คือ Column หรือจะเรียก แถวกับหลักก็ได้

  เมทริกซ์ 1 มิติ มีแค่ด้านยาว
  
  เมทริกซ์ 2 มิติ มีด้านกว้างและยาว
  
  เมทริกซ์ 3 มิติ มีด้านกว้าง ยาวและลึก
  
  เมทริกซ์ 4 มิติ มีด้านกว้าง ยาว ลึกและหนา
  
  แนวตั้ง เรียก Attribute คือคุณสมบัติที่ใช้อธิบายข้อมูล แนวนอน เรียก Record
  
  **Data Objects And Attribyte Types**
  
  Data ที่มีหลายตารางที่มีความสัมพันธ์กัน ลักษณะคล้ายกับการเก็บข้อมูลใน Database
  
  **_Record Data_**
  
    ตาราง Term-Freequency เป็นตารางที่ใช้เก็บข้อมูลที่เป็น Text
  
  **_Graphs And Network_**
  
    จะเป็นการยอกว่าจุดนี้เชื่อมกับอะไร อย่างเช่น ข้อมูลในโซเชียล เว็บไซต์ต่างๆ แผนที่รถไฟฟ้า ที่มีการเชื่อมต่อกันไปอย่างไรบ้าง
    
  **_Spatial, Image And Multimedia Data_**
  
    เป็นข้อมูลที่มีเวลาเข้ามาเกี่ยวข้อง 
    
    - Vedio เช่น วีดิโอ โดยทำการเอารูปหลายรูปมาซ้อนกัน เป็นรูปที่ 1 ทับรูปที่ 2 ทับรูปที่ 3 ไปเรื่อยๆ(เหมือนรูปสามารถเคลื่อนไหวได้(เรียกว่า Cartoon Making))
    - Image เช่น รูปภาพ ซึ่งจะมีด้านกว้างกับยาว ซึ่งอาจจะกำหนดเป็นพิกัด x,y โดยแต่ละตัวจะมีสีบอกจุด
    - Spatial เช่น แผนที่ ซึ่งจะมีการกำหนดจุดพิกัด x,y โดยอาจจะกำหนดสีให้แต่ละพิกัดจังหวัด
    
  **_Ordered Data_**
   
    เป็นข้อมูลที่มีเวลาเข้ามาเกี่ยวข้องเหมือนกัน ทำการแปลง Data เป็นตัวเลข
    - Time-Series เช่น ราคาหุ้น แต่ละวันที่มีราคาขึ้นลงไปมา
    - Sequential เช่น ข้อมูลที่ไม่สามารถสลับตำแหน่งหรือลำดับกันได้
    
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
    
    - Data Sets ประกอบด้วย Data Object หลายๆ ตัวมารวมกัน
    
        Data Set คือ set ของข้อมูลหลายๆ ตัวมารวมกัน
    
    - Data Object คือข้อมูลแแต่ละตัวประกอบด้วย Entity ของแต่ละอัน 
    
    - Also called sample,examples,instances,data points,objects,tues ***สำคัญ***
    
      มีความหมายเดียวกันทั้งหมด คือ ข้อมูลที่เป้น Data 1 จุดที่อยู่ในแนวตั้ง (Data 1 จุด คือ Data point)
    
    - ข้อมูลจะถูกอธิบายด้วย Attributes
    
    - ใน Database ที่จะนำมาทำคือ Rows > Data, Column > Attributes
    
    
    
