# DWDM21
Data Warehouse &amp; Data Mining 2021

Ratima Chinwong 623020042-0

Group Name: SUKUNA

1 **Ratima Chinwong 623020042-0**

2. Jennapa Phunanil 623020515-3

3. Watcharaporn Nammungkhun 623020535-7

4. Suphalaksana Buajan 623020540-4

5. Kiartisak Senchan 623021041-7

## สารบัญเนื้อหา
### วิชา Data Warehouse & Data Mining (คลังข้อมูลและการทำเหมืองข้อมูล)

* บทที่ 1 [Introduction](https://github.com/Octa-p/DWDM21/blob/main/%E0%B8%AA%E0%B8%A3%E0%B8%B8%E0%B8%9B_Chapter_1.ipynb)

  * Data Mining คืออะไร
  * ทำไมจึงต้องมี Data Mining..?
  * วัตถุประสงค์ในการใช้ Data Mining
  * เป้าหมายหลักของ Data Mining
  * ขั้นตอนการทำ Data Mining
  * ส่วนประกอบการทำ Data Mining
  * เทคนิคในการทำ Data Mining

* บทที่ 2 Getting to know your data
  * [Basic Python](https://github.com/Octa-p/DWDM21/blob/main/Data101_(Chapter2).ipynb)
    * Variables
    * Casting int() float() str()
    * Data Structure
    * List
    * Loop
    * Condition
    * Quiz 1
    * HW3
    * Function
    * Quiz 4
  * [Plot](https://github.com/Octa-p/DWDM21/blob/main/Data102_(Chapter2).ipynb)
    * Box Plot
    * Time Series Plot
  * [Visualization](https://github.com/Octa-p/DWDM21/blob/main/Data_Visualization.ipynb) 
    * Scatter plot
    * Plot
    * Bar chart
    * Stacked Bar Chart
    * Histogram
  * [Distance Numpy](https://github.com/Octa-p/DWDM21/blob/main/Distance_Numpy.ipynb)
    * Numpy Array
    * Matrix transpose
    * Quiz กลุ่ม
    * Indexing & Slicing
    * Euclidean Distance (L2-norm)
    * Distance function
    * Manhattan Distance (L1-norm)
    * HW11
    * Distance of Binary Value
  * [ชีทสรุป Chapter 2](https://github.com/Octa-p/DWDM21/blob/main/HW2.1-%E0%B8%AA%E0%B8%A3%E0%B8%B8%E0%B8%9B-Chapter-2.pdf)
  
* บทที่ 3 [Data Preprocessing](https://github.com/Octa-p/DWDM21/blob/main/Data_Preprocessing_(Chapter3).ipynb)
  * Meta Data
  * ชี้ข้อมูลในตาราง
    * ชี้แบบธรรมดา ใช้ [ชื่อ column][index]
    * ชี้แบบ .lioc[] (มองข้อมูลเป็น matrix)
  * Missing Values
    * Handing Missing Value 1 (ลบค่า missing ออก)
    * Handling Missing Value 1.5 (ลบค่า missing เฉพาะใน column ที่เราสนใจ)
    * Handling Missing Value 1.5 (แทนด้วย class ใหม่ (unknown))
    * Handling Missing Value 3 (แทนด้วย class ใหม่ (ค่าที่เหมาะสม))
    * Handling Missing Value 4 (แทนด้วย ค่ากลาง)
    * Handing Missing Value 5 (แทนด้วย mean ที่อยู่ใน class เดียวกัน)
  * Select data by values [PD]
    * สร้าง list ของ boolean
    * นำ list ของ boolean มาเลือกค่าในตาราง
    * ใช้ & (and) และ | (or) ในการรวม list ของ boolean
  * Quiz4 + HW
    * ต่อตารางแนวแกน Y [PD]
    * การเรียงข้อมูล [PD]
  * Outlier
  * Quiz 5
  * Quiz กลุ่ม |||
  * Pandas' looping (.iterrows)
  * การรวมตาราง (ต่อตารางในแนวแกน X)
    * รวม 2 ตาราง (.merge())
    * เอาเฉพาะคอลลัมม์ที่เราต้องการมาแปะ (.map())
    * Group by (pandas)
  * HW + Quiz
    * [PD] save ตารางเอาไปใช้ที่อื่น
    * [PD]การสร้างตาราง
  * [ชีทสรุป Chapter 3](https://github.com/Octa-p/DWDM21/blob/main/03Preprocessing.pdf)
  
* บทที่ 4 [Data Warehousing and on-line Analytical Processing](https://github.com/Octa-p/DWDM21/blob/main/Chapter-4.pdf)
  * Data Warehouse Basic Concepts
  * Data Warehouse Modeling
     * Data Cube
     * OLAP
  * Data Warehouse Design and Usage
  * Data Warehouse Implementation
  * Summary
  * [ชีทสรุป Chapter 4](https://github.com/Octa-p/DWDM21/blob/main/Chapter-4.pdf)
  
* บทที่ 5 [Associationn Rules](https://github.com/Octa-p/DWDM21/blob/main/Chapter6_Association_Rules.ipynb)
  * [Q] มีประเทศสาขาของ supermarket นี้ทั้งหมดกี่ประเทศ
  * [HW13] วาดกราฟสรุปจำนวน items และ ยอดขายของแต่ละประเทศ
  * เตรียม Data สำหรับ (Fequence Pattern) Association Rule
  * Apriori
  * Quiz7
  * [ชีทสรุป Chapter 5](https://github.com/Octa-p/DWDM21/blob/main/Chapter-6.pdf)

* บทที่ 6 Classification
  * [Decision Tree](https://github.com/Octa-p/DWDM21/blob/main/Chapter_7_Classification_(Decision_Tree).ipynb)
     * Train Model
     * Plot Tree
     * Evaluation
     * Random
     * Advanced Tree
     * TEST
     * HW
     * เลือก T4 แล้ว train ใหม่ด้วย Training
  * [KNN](https://github.com/Octa-p/DWDM21/blob/main/Chap_7_classification_(KNN_NN)_.ipynb)
     * Load data
     * Split Data
     * Train Model
     * Retrain & Evaluate
     * Neural Network
  * [Evaluation](https://github.com/Octa-p/DWDM21/blob/main/Chap7_Classification_(Evaluation).ipynb)
     * Load data
     * แบ่ง Data
     * สร้าง Model ทำนาย
     * Evaluation
  * [ชีทสรุป Chapter 6 + การบ้าน](https://github.com/Octa-p/DWDM21/blob/main/08ClassBasic.pdf)
  * [ชีทสรุป Chapter 6 ต่อ](https://github.com/Octa-p/DWDM21/blob/main/Chapter%208%20%E0%B8%A7%E0%B8%B1%E0%B8%99%E0%B8%97%E0%B8%B5%E0%B9%88%20141064.pdf)
  
* บทที่ 7 [Clustering](https://github.com/Octa-p/DWDM21/blob/main/Chap_8_Clustering.ipynb)
  * K-means
    * Generate Data
    * Clustering
      * import
      * Define
      * Fit-Predict
      * Plot
      * 3 Cluster
      * 4 Cluster
      * 5 Cluster
    * Example Application (Color Quantization)
      * นับจำนวนสี
      * จัดกลุ่มสีให้เหลือ 16 สี
      * ใช้ centroid เป็นตัวแทนของสี
      * แทนสีคืนลงไป
      * จัดกลุ่มสีให้เหลือ 8 สี
  * Hierachical Clustering
  * Clustering Evaluation
  * [ชีทสรุป Chapter 7](https://github.com/Octa-p/DWDM21/blob/main/Chapter-10.pdf)
  
* [MiniExam](https://github.com/Octa-p/DWDM21/blob/main/MiniExam.ipynb)
* [Final Project](https://github.com/Octa-p/DWDM21/blob/main/Project_SUKUNA.ipynb)
  * [Slide Project](https://github.com/Octa-p/DWDM21/blob/main/Project.pdf)
  
