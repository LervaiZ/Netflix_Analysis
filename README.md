**Languages:** [**🇹🇭 ภาษาไทย**](#-ภาษาไทย-thai-version) | [**EN English**](#-english-version)
<hr>

<a name="-ภาษาไทย-thai-version"></a>
# 🇹🇭 การวิเคราะห์และจัดกลุ่มคอนเทนต์บน Netflix

โปรเจกต์นี้เป็นการวิเคราะห์ข้อมูลคอนเทนต์บน Netflix ในเชิงสำรวจ (Exploratory Data Analysis - EDA) และใช้ Machine Learning (K-Means Clustering) เพื่อจัดกลุ่มคอนเทนต์ตามลักษณะที่คล้ายคลึงกัน

---

## 💡 สิ่งที่ค้นพบจากการวิเคราะห์ (Key Findings)

### 1. ปริมาณ vs. คุณภาพ/ผลกระทบ
<img width="515" height="413" alt="pie_chart" src="https://github.com/user-attachments/assets/4a61b8ca-28de-401d-ba5b-1e3eb74b8922" />

> หากกล่าวถึงสิ่งที่สร้าง Brand Identity ให้ Netflix อย่าง Original Series เช่น Stranger Things ซึ่งเป็นหมวด TV Show ก็จะเกิดคำถามได้ว่า Netflix เน้นให้ความสำคัญกับ 'ปริมาณ' (จำนวนภาพยนตร์ที่เยอะกว่า) หรือ 'คุณภาพ/ผลกระทบ' (ที่มาจาก Series) มากกว่ากัน

### 2. สหรัฐอเมริกาคือผู้ผลิตหลัก
<img width="651" height="482" alt="bar_chart_countries" src="https://github.com/user-attachments/assets/9140241d-b14c-4de6-91cb-474c4c915744" />

> สหรัฐอเมริกาเป็นผู้ผลิตคอนเทนต์หลักให้กับ Netflix อย่างท่วมท้น แต่เทรนด์ในปีล่าสุดแสดงให้เห็นถึงแนวโน้มการขยายตลาดไปยังเอเชีย เช่น ญี่ปุ่น

### 3. กลุ่มเป้าหมายหลักคือผู้ใหญ่และวัยรุ่น
<img width="583" height="505" alt="bar_chart_ratings" src="https://github.com/user-attachments/assets/3f2b6a1f-40e9-4f1c-985f-d3026a3eb3db" />

> คอนเทนต์ส่วนใหญ่มีเรตติ้ง TV-MA (สำหรับผู้ใหญ่) และ TV-14 (สำหรับผู้ชม 14+) ชี้ชัดว่ากลยุทธ์ของ Netflix เน้นไปที่การตอบสนองความต้องการของผู้ชมกลุ่มนี้เป็นหลัก

### 4. เทรนด์หลังยุค "Streaming Wars"
<img width="622" height="480" alt="line_chart_years" src="https://github.com/user-attachments/assets/351c2980-58dc-4f2c-8945-10c88d8f3e81" />

> จำนวนคอนเทนต์ใหม่พุ่งสูงสุดในปี 2018 ก่อนจะลดลงต่อเนื่อง ซึ่งสอดคล้องกับช่วงที่คู่แข่งเข้ามาในตลาด ทำให้ Netflix เปลี่ยนกลยุทธ์จากการเน้น 'ปริมาณ' มาเป็นการเน้นสร้าง 'Original Content' ที่มีคุณภาพ

---

## 🤖 ผลลัพธ์จากการจัดกลุ่มคอนเทนต์ (Clustering Results)

ใช้ K-Means Clustering Model เพื่อแบ่งคอนเทนต์ออกเป็น 8 กลุ่มหลัก ดังนี้:

| หมายเลข Cluster | ชื่อกลุ่ม (Cluster Persona) |
| :---: | :--- |
| 0 | ซีรีส์ดราม่าและอาชญากรรมจากต่างประเทศ |
| 1 | รายการทีวีและซีรีส์วาไรตี้ |
| 2 | ภาพยนตร์แอ็คชั่นและผจญภัย |
| 3 | ภาพยนตร์ดราม่าและหนังนอกกระแส |
| 4 | สแตนด์อัพคอมเมดี้ |
| 5 | ภาพยนตร์สำหรับเด็กและครอบครัว |
| 6 | ซีรีส์สารคดี (Docuseries) |
| 7 | ภาพยนตร์สารคดี (Documentary Films) |

---

## 🛠️ เครื่องมือที่ใช้ (Tools & Libraries)
* Python, Pandas, Matplotlib, Seaborn, Scikit-learn

---

## 📂 ดูการวิเคราะห์ฉบับเต็ม
สำหรับโค้ดและขั้นตอนการวิเคราะห์ทั้งหมด: **[เปิดโปรเจกต์ใน Google Colab](link/to/your/colab_link)**

<hr>

<a name="-english-version"></a>
# EN Netflix Content Analysis & Clustering

This project involves an Exploratory Data Analysis (EDA) of the Netflix content dataset and utilizes Machine Learning (K-Means Clustering) to group content based on similar characteristics.

---

## 💡 Key Findings

### 1. Quantity vs. Quality/Impact
<img width="515" height="413" alt="pie_chart_eng" src="https://github.com/user-attachments/assets/bb6a4cd0-f8d0-47b4-86ba-ad93d18b1577" />


> When considering what builds Netflix's Brand Identity, like Original Series such as 'Stranger Things' (a TV Show), it raises the question of whether Netflix focuses more on 'quantity' (the higher number of movies) or on 'quality/impact' (derived from its series).

### 2. The USA is the Primary Producer
<img width="684" height="463" alt="country_chart_eng" src="https://github.com/user-attachments/assets/b362c6ab-63ea-46d5-a132-0a22ef27a32f" />

> The United States is the overwhelming primary producer for Netflix. However, the trend in the most recent year shows a clear strategic expansion into Asian markets, such as Japan.

### 3. The Target Audience is Adults & Teenagers
<img width="578" height="487" alt="rate_chart_eng" src="https://github.com/user-attachments/assets/ed7aea24-0c86-4834-b50b-3b6c2f24d5b7" />

> The majority of content is rated TV-MA (Mature Audience) and TV-14 (For Audiences 14+), clearly indicating a strategy focused on catering to this demographic.

### 4. The Post-"Streaming Wars" Trend
<img width="609" height="471" alt="line_chart_eng" src="https://github.com/user-attachments/assets/03a9b2fd-a3cc-431a-8c9d-685221374932" />

> The volume of new content peaked in 2018 before steadily declining. This aligns with the period when new competitors entered the market, prompting Netflix to shift its strategy from 'quantity' to producing high-quality 'Original Content'.

---

## 🤖 Clustering Results
A K-Means Clustering Model was used to segment the content into 8 main groups:

| Cluster | Cluster Persona |
| :---: | :--- |
| 0 | International Drama & Crime Series |
| 1 | Variety TV Shows & Series |
| 2 | Action & Adventure Movies |
| 3 | Dramas & Independent Films |
| 4 | Stand-Up Comedy |
| 5 | Children & Family Movies |
| 6 | Docuseries |
| 7 | Documentary Films |

---

## 🛠️ Tools & Libraries
* Python, Pandas, Matplotlib, Seaborn, Scikit-learn

---

## 📂 Full Analysis
For the complete code and step-by-step analysis: **[View Project on Google Colab](link/to/your/colab_link)**
