# DWDM21

Data Warehouse &amp; Data Mining 2021

นางสาวกิตติมา อุปสุข 623021040-9 

Group name:Sandboxนะจ๊ะ

1. **_นางสาวกิตติมา อุปสุข 623021040-9_**
2. **_นางสาวชนัญชิดา เมธีกุลมานิต 623020516-1_**
3. **_นางสาวณิชากร ไชยสุวรรณ 623020521-8_**
4. **_นางสาวนฤมล ไสยโสภณ 623021050-6_**
5. **_นางสาวภิญญาดา เพ็ญสุข 623021052-2_**

# สารบัญ
## ทฤษฎี
**Chapter 1 :** [Introduction](https://github.com/kittimaxz/DWDM21/blob/main/Chapter1_Introduction.md)
  * Data Warehouse & Data Mining
  * Why Data Mining ?
  * What is Data Mining ?
  * Knowledge Discovery (KDD) Process
  * Data Mining Function
  
**Chapter 2 : Getting to Know Your Data** 
  * [Getting to Know Your Data](https://github.com/kittimaxz/DWDM21/blob/main/Chapter%202.1_Getting%20Know%20Your%20Data.md)
    * Intro to Data Mining
    * Data Objects And Attribute Types
    * Important characeristics Of Structered Data
    * Discrete VS. Continuous Attributes
    * Basic statistical Descriptions of Data
    * Measuring the Central Tendency
  * [Similarity And Dissimilarity](https://github.com/kittimaxz/DWDM21/blob/main/Similarity-Dissimilarity.pdf) 
    * Similarity, Dissimilarity and Proximity
    * Data Matrix And Dissimilarity Matrix
    * Standardizing Numeric Data 
  * [Binary Variable](https://github.com/kittimaxz/DWDM21/blob/main/binary-variable.pdf)
    * Binary Attributes
    * Categorical Atrributes
    * Ordinal Variable
    
**Chapter 3:** [Data Preprocessing](https://github.com/kittimaxz/DWDM21/blob/main/Chapter-3-Preprocessing.pdf)
  * What is Data Preprocessing ?
  * Why Preprocess the Data ?
  * Incomplete (Missing) Data
  * How to Handle Missing Data ?
  
**Chapter 6 :** [Association and Correlation](https://github.com/kittimaxz/DWDM21/blob/main/Chapter6.pdf)
  * What is Pattern Discovery
  * Why is it Important ?
  * Basic concepts
  * Apriori

**Chapter 7 : Classification**
  * [Basic Concepts](https://github.com/kittimaxz/DWDM21/blob/main/08ClassBasic.pdf)
    * Superised VS. Unsupervised Learning
    * Predition Problems
    * Decision Tree Induction
  * [Dicision Tree](https://github.com/kittimaxz/DWDM21/blob/main/08ClassBasicdicision-tree_algorithm.pdf)
    * Algorithm
    * Gain Ratio
    * Another Measure 
    * Overfitting And Tree Pruning
  * [Bayes](https://github.com/kittimaxz/DWDM21/blob/main/08ClassBasic-bayes.pdf)
    * Basics
    * Naive Bayes Classifier 
  * [Evaluation And Selection](https://github.com/kittimaxz/DWDM21/blob/main/Evaluation-and-Selection.pdf)
    * Basic Classifier Evaluation Metrics
* [Evaluation](https://github.com/kittimaxz/DWDM21/blob/main/EVALUATION.pdf)
    * Confusion Matrix
    * Accuracy, Error Rate, Sensitivity And Specificity
* [การบ้าน](https://github.com/kittimaxz/DWDM21/blob/main/HW14.pdf)
* [Neural Network for Classification](https://github.com/kittimaxz/DWDM21/blob/main/Neural-Network.pdf)  
  * Perceptron
  * ตัวอย่างการเรียนรู้ฟังก์ชัน AND และ XOR ด้วยกฎเรียนรู้เพอร์เซปตรอน
    
**Chapter 8 :**[Clustering](https://github.com/kittimaxz/DWDM21/blob/main/K-MEANS.pdf)
 * Basic concepts
 * The K-Means Clustering Method
 
## ปฏิบัติ
**Chapter 2 : Getting to Know Your Data**
* [Basic Python](https://github.com/kittimaxz/DWDM21/blob/main/Data101(Chapter2).ipynb)
  * Basic Python
    * Variables
  * Casting
    * Int()
    * Float()
    * Str()
  * Data Structure
    * List()
    * วิธีสร้าง List ว่าง
     * เติมค่าลงไปใน List (.append()) 
     * การชี้ค่าใน List (Indexing)
    * List Slicing
    * List + List
  * Loop
    * Nested Loop
  * Condition
    * If Statement
  * Quiz
    * เฉลย
  * HW
  * Function
    * Example 1
    * Example 2 (ไม่มี input)
    * Example 3 (ไม่มี output)
    * Example 4 (ไม่มี input and output)
    * ลักษณะของ Input (Parementer, Argument)  
  * Quiz    
* [Pandas](https://github.com/kittimaxz/DWDM21/blob/main/Data102.ipynb)
  * Read Data
    * .head() ดูหัวตาราง
    * .tail() ดูท้ายตาราง
  * Boxplot
  * Time Seies Plot
* [Data Visualization](https://github.com/kittimaxz/DWDM21/blob/main/Data_Visualization.ipynb)
  * Visualization
  * Scatter Plot
  * Plot
  * Bar Chart
    * Grouped Barchart
    * Stacked Barchart
  * Histogram
  * Box Plot
* [Distance Numpy](https://github.com/kittimaxz/DWDM21/blob/main/Distance_Numpy.ipynb)
  * Numpy Array
    * สร้าง Numpy Array (Matrix)
    * สร้าง Matrix เริ่มต้น (Zeros,Ones)
    * สร้าง Matrix Random
    * Matrix Transpose
  * Indexing & Slicing
  * Useful Function
    * วนลูปเอง
    * Summation
  * Quiz
  * Distance Matrix
    * Euclidean Distance (L2-Norm)
    * Distance Function
    * Manhattan Distance (L1-Norm)
  * Quiz
  * HW
    * เฉลย Quiz
  * Distance of Biinary Value

**Chapter 3 :** [Data Processing](https://github.com/kittimaxz/DWDM21/blob/main/Data_Preprocessing(Chapter_3).ipynb)
  * Meta Data
    * ชี้ข้อมูลในตาราง
    * ชี้แบบธรรมดา [ชื่อ Column][Index]
    * ชี้แบบ .iloc [] 
  * Missing Value
    * Handling Missing Value 1 (ลบค่า Missing ออกไป)
  * Quiz
    * เฉลย
    * Handling Missing Value 1.5 (ลบค่า Missing เฉพาะใน Column ที่เราสนใจ) 
  * Quiz
    * Handling Missing Value 2 (แทนด้วย Class ใหม่ (Unknow))
    * Handling Missing Value 3 (แทนด้วย Class ใหม่ (ค่าที่เหมาะสม))
    * Handling Missing Value 4 (แทนด้วย ค่ากลาง)
      * ถ้าเป็น Numeric ใช้ Mean
      * ถ้าเป็น Norminal (ตัวหนังสือ) จะใช้เป็น Mode(ฐานนิยม)
      * ถ้าเป็น Ordinal ใช้เป็น Median
    * Handling Missing Value 5 (แทนด้วย ค่ากลางของ Samples ใน Class เดียวกัน)
      * สร้าง List ของ Boolean
      * นำ List ของ Boolean มาเลือกค่าในตาราง
  * Select Data By Values[PD]
    * สร้าง List ของ Boolean
    * เราใช้ & (And) และ | (Or) ในการรวม List ของ Boolean
  * Quiz+HW
  * ต่อตารางแนวแกน Y [PD]
    * Handling Missing Value 5 (แทนด้วย ค่ากลางของ Samples ใน Class เดียวกัน)(ต่อ)
    * การเรียงข้อมูล [PD]
  * Outlier
    * สิ่งที่ Datadict (Curly Brackets) บอก
    * ตัด Outlier แบบ Manual
  * Quiz
    * เฉลย
  * Pandaslooping(.iterrows)
  * การรวมตาราง(ต่อตารางในแนวแกน x)
    * รวม 2 ตารางเข้าด้วยกัน (.merge()
    * เอาเฉพาะ Column ที่ต้องการมาแปะ (.map()) 
  * Group by(Pandas)
  * Quiz+HW
  * [PD] Save ตารางเอาไปใช้ที่อื่น
  * [PD] การสร้างตาราง

**Chapter 6 :** [Association and Correlation](https://github.com/kittimaxz/DWDM21/blob/main/Chapter6_Association_Rules.ipynb)
 * ลบ Records ที่ถูก Cancel ออกไป
 * Quiz
 * HW
   * เฉลย
 * เตรียม Data สำหรับ (Fequence Pattern)
 * Apriori
 * Quiz

**Chapter 7 : Classification**
* [Decision Tree](https://github.com/kittimaxz/DWDM21/blob/main/Chapter7_Classification(Decision_Tree).ipynb)
  * Load Data
  * Train Model
    * Import (เรียกใช้ Algoritihm ที่เราต้องการ)
    * Define (การกำหนด Parameters ให้กับ Model)
    * Train (ฝึกสอนตัวแบบ)
  * Plot Tree
  * Evaluation
  * Random
  * Advanced tree
    * Import
    * Define
    * Train
  * Test
  * Start here
  * HW
  * Train ใหม่ด้วย Training
* [KNN_NN](https://github.com/kittimaxz/DWDM21/blob/main/Chapter_Classification_(KNN_NN).ipynb)
  * Load Data
  * Split Data
  * Train Model
  * Retrain & Evaluate
  * Neural Network
    * Import
    * Define
    * Train-Test
* [Evaluation](https://github.com/kittimaxz/DWDM21/blob/main/Chapter7_Classification(Evaluation).ipynb)
  * Load Data
  * แบ่ง Data
  * สร้าง Model ทำนาย
    * Import
    * Define
    * Train
    * Evaluation

**Chapter 8 :** [Clustering](https://github.com/kittimaxz/DWDM21/blob/main/Chapter8_Clustering.ipynb)
 * K-means
  * Generate Data
  * Clustering
    * Import
    * Define
    * Train-Predict
  * Example Application(Color Quanization)
    * นับจำนวนสี
    * จัดกลุ่มสีให้เหลือ 16 สี
    * แปลงข้อมูลให้อยู่ในรูป Row-Column
    * ใช้ Centroid เป็นตัวแทนสี
    * แทนสีคืนลงไป

# MiniExam
[Mini Exam](https://github.com/kittimaxz/DWDM21/blob/main/MiniExam.ipynb)
 * ข้อที่ได้ในการสอบ
   * ข้อ.0 หารัฐที่มีจำนวนเครื่องบินขาเข้ามากที่สุดและน้อยที่สุด
   * ข้อ.3 สายการบินไหนมีเที่ยวบินมากที่สุดและน้อยที่สุด
   * ข้อ.คิดเอง สนามบินที่มีจำนวนเครื่องบินขาออกมากที่สุดและน้อยที่สุด

# Project Group
* [Project Midterm](https://github.com/kittimaxz/DWDM21/blob/main/Project.ipynb)
   * แหล่งที่มาของข้อมูล
   * นำข้อมูลเข้า
   * ตรวจสอบค่า Missing ของข้อมูล
   * เลือกตัดเอาเฉพาะคอลัมน์ของข้อมูลที่ต้องการ
   * เปลี่ยนชื่อคอลัมน์
   * รวม 2 ตารางเข้าด้วยกัน .merge()
   * จัดการค่า Missing ด้วยวิธี Handling Missing (แทนด้วย Class ใหม่ (Unknow) ) โดยใช้คำสั่ง .fillna()
   * ลองเช็คข้อมูล
     * จังหวัดกาญจนบุรี มีผู้มาเยี่ยมชมย่านชุมชนเก่าในปี 2560 กี่คน 2560visitor
     * จังหวัดกาญจนบุรี มีรายได้จากการมาเยี่ยมชมชุมชนเก่าในปี 2560 กี่บาท 2560income
     * จังหวัดเชียวใหม่มีย่านชุมชนเก่าใดบ้าง
* [Project Final](https://github.com/kittimaxz/DWDM21/blob/main/ProjectFinal.ipynb)
   * แหล่งที่มาของข้อมูล
   * Preprocessing
     * นำเข้าข้อมูล
     * ตรวจสอบค่า Missing ของข้อมูล
     * เลือกตัดเอาเฉพาะคอลัมน์ของข้อมูลที่ต้องการ
     * เปลี่ยนชื่อคอลัมน์
     * รวม 2 ตารางเข้าด้วยกัน .merge()
     * จัดการค่า Missing ด้วยวิธี Handling Missing (แทนด้วย Class ใหม่ (Unknow) ) โดยใช้คำสั่ง .fillna()
  * ปัญหา
    * ข้อมูลจำนวนครัวเรือน ข้อมูลจำนวนประชากรแต่ละจังหวัด รายได้จากการท่องเที่ยวของแต่ละจังหวัด ใช้ทำนายลักษณะของชุมชนเก่าว่ามีลักษณะอย่างไร
  * Classification
    * Decision tree
    * KNN
    * Neural Network
    * Retrain & Evaluate
  * Visulization
    * การทำนายลักษณะชุมชนโดยใช้จำนวนครัวเรือน
    * การทำนายลักษณะชุมชนโดยใช้จำนวนประชากร
    * การทำนายลักษณะชุมชนโดยใช้จำนวนรายได้จากการท่องเที่ยว
* [Slide Present](https://github.com/kittimaxz/DWDM21/blob/main/Final%20Project%20DWDM2021.pdf)
