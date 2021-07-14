**Data Warehouse & Data mining**

  เกี่ยวกับ Data ว่ามีกระบวนการอย่างไร หลังจากที่ถูกเก็บไว้ใน Database ซึ่งจะเอามาวิเคราะห์ความรู้เพื่อนำไปใช้ประโยชน์ต่อไป
  
  Data Warehouse = Data ที่เก็บมาจะถูกคัดแยก จัดเก็บอย่างไรต่อจาก Database ซึ่งที่ถูกจัดเก็บจะถูกนำมาทำ Data Mining ต่อไป
  
  Data Mining = การวิเคราะห์หาสิ่งที่มีค่าที่อยู่ใน Data

**_Why Data Mining?_**

  การทำเหมืองข้อมูล ขุดเหมืองข้อมูล เนื่องจากในปัจจุบันนั้นมี Data เพิ่มมากขึ้นเรื่อยๆ เช่น เซนเซอร์อุณหภูมิ เซนเซอร์ปริมาณน้ำฝน ข้อมูลในเว็บไซต์ต่างๆ การจัดเก็บข้อมูลในแบบต่างอย่างเช่น รูปถ่ายในกล้องหรือแอพต่างๆ ฯลฯ ที่อาจจะมีการสุ่มการจัดเก็บข้อมูลในทุกๆชั่วโมง จึงทำให้ Data นั้นล้นมากขึ้นเรื่อยๆ
  
**_What Is Data Mining?_**

  การนำ Data ที่มีอย่างมากมายที่ไม่สามารถนำมาใช้งานได้โดยตรงมาวิเคราะห์เป็นความรู้เพื่อที่จะนำมาใช้ประโยชน์ โดยจะทำการเก็บจัด Data อย่างไรให้มีประสิทธิภาพ นำมาวิเคราะห์อย่างไรให้ได้ข้อมูลที่มีคุณค่า จาก Database
  
**_Knowledge Discovery(KKD) Process_**

  => Database จัดเก็บข้อมูลอย่างไร คิวรีอย่างไร หลังจากนั้นเป็นการจัดการข้อมูล renoise remissing ใน multivariate หลังจากนั้นเป็นการทำ Data Integration คือการเอาข้อมูลหลายๆ แหล่งมารวมกันเพื่อนำไปเก้บไว้ใน Data Warehouse 
  
  => Data Warehous ดึงข้อมูลที่เราจำเป็นต้องใช้ประโยชน์ต่างๆ จากฐานข้อมูลต่างๆ มารวมกัน เพื่อดูข้อมูลที่จะเลือกนำมาวิเคราะห์องค์ความรู้จริงๆ มาทำ Data mining ซึ่งจะได้เป็น Pattern คือรูปแบบที่ซ้อนอยู่ในข้อมูล จากนั้นทำการวัดผลเพื่อดูว่าข้อมูลที่วิเคราะห์มานั้นเป็นองค์ความรู้จริงๆ หรือไม่ โดยการทำการทดสอบองค์ความรู้ที่วิเคราะห์มาได้ ก่อนที่จะได้มาเป็นองค์ความรู้
  
 **Example: A Web Mining Framework**
 
 *Web mining usually involves*
  
  - Data Cleaning
  - Data Integration From Multiple Sources
  - Warehousing The Data ในขั้นตอนนี้เป็นการดูข้อมูล จะยังไม่มีการวิเคราะห์ข้อมูลที่ซ้อนอยู่
  - Data Cube Construction
  - Data selection For Data Mining 
  - Data Mining เป็นการวิเคราะห์ข้อมูลที่ซ้อนอยู่
  - Presentation Of The Mining Results เป็นขั้นตอนที่สำคัญมาก เนื่องจากเป็นการนำเอาองค์ความรู้ที่ทำการวิเคราะห์แล้วมาแสดงให้ผู้อื่นที่ได้เห็นเข้าใจได้
  - Patterns And Knowledge To Be Used Or Stored Into Knowledge-Base
    
**Data Mining In Business Intelligence**

  Data Sources คือแหล่งข้อมูล ซึ่งจะมาแหล่งข้อมูลใดก็ได้ ไม่ว่าจะเป็นในกระดาษ เว็ปไซต์ หรือ Database มาทำเป็นดิจิตอล คือเก็บไว้ใน Database => Data Preprocessing/Integration จะเป็นการรวบรวมข้อมูลให้เป็น Data Warehouse เพื่อให้สามารถดูข้อมูลหรือสรุปต่างๆ ดึงออกมาดูได้ => Data Mining เป็นการหาสิ่งที่ถูกซ้อนไว้ในข้อมูล => Data Presentation เป็นการนำเสนอให้ผู้อื่นเข้าใจองค์ความรู้ที่วิเคราะห์ออกมาได้ => Decision Making ทำการตัดสินใจว่าจะนำข้อมูลที่วิเคราะห์มาได้ไปใช้ประโยชน์อย่างไรต่อไป
  
**_KKD Process: A View From ML And Statistics_**
![7](https://user-images.githubusercontent.com/76931027/125625415-59f80bb7-0dc9-4859-82b1-5695cebfae47.PNG)

Input Data > Data Pre-Processing > Data Mmining > Post-Processing > Pattern Information Knowladge

Data Pre-Processing

  - Data Integration
  - normalization
  - Feature Selection
  - Dimension Reduction

*Data Minig*

  - Pattern Discovery การหารูปแบบที่ซ้อนอยู่ในข้อมูล
  - Classification การจำแนกข้อมูล
  - Clustering การแบ่งกลุ่มข้อมูล
  - Outlier Analysis
  
Post-Processing
  - Pattern Evaluation
  - Pattern Selection
  - Pattern Interpretation
  - Pattern Visualization
  
**How The Data Suppose To Look Like**
![00](https://user-images.githubusercontent.com/76931027/125620468-ed47378b-d14b-4cc6-8c35-1094511a9a37.PNG)

 * ใน Data ที่จะใช้เรียนในวิชานี้จะเป็นรูปแบบประมาณนี้ * 
  เป็นการดูคร่าวๆ ว่าในแต่ละ reccord data นั้นมีคุณสมบัติอะไรบ้างที่ใช้อธิบาย

**Data Mining Function**

**_Pattern Discovery_**
 ![12](https://user-images.githubusercontent.com/76931027/125622467-b5c959dd-9384-4637-b264-6b060046c0bb.PNG)

  เป็นการวิเคราะห์หารูปแบบที่เกิดขึ้นซ้ำๆในข้อมูล โดยเทคนิคที่จะใช้ในการเรียนคือ " Association Rule"

**_Classification_** (ใช้ข้อมูลที่มีอยู่มาทำนนาย ในตัวที่อยากทำนาย)
![13](https://user-images.githubusercontent.com/76931027/125622865-3105eaa4-e559-4745-a7a5-76266cb4595f.PNG)

  การจำแนกกลุ่มของข้อมูล เช่น การเก็บข้อมูลของกรมอุตุ ที่เก็บข้อมูลปริมาณน้ำ อุณหภูมิ ความกดอากาศ ฯลฯ ว่าเป็นอย่างไรของทุกๆ วัน โดย Classification จะช่วยนำเอาข้อมูลอื่นๆ ที่ไม่ใช่ข้อมูลฝนตกของวันนี้ไปทำนายว่าวันอื่นๆ ฝนจะตกหรือไม่
  
  โดยเป็นการนำข้อมูลต่างๆ มาทำนายข้อมูลตัวหนึ่ง (การทำนายค่า Y โดยการนำค่า X มาทำนาย)
  
**_Cluster Analysis_** (ไม่มีคำตอบให้ทำนาย เป็นการแบ่งกลุ่มเฉยๆ)
![14](https://user-images.githubusercontent.com/76931027/125623938-18146157-8be4-4411-99d0-f9c236c06578.PNG)

  การแบ่งกลุ่ม โดยทำการแบ่งกลุ่มข้อมูลที่มีลักษณะคล้ายๆ กันมาอยู่ด้วยกัน
  
