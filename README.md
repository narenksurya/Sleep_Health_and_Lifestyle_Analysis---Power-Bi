# Sleep Health and Lifestyle Analysis – Power BI Project

## 📊 Project Overview
This project explores the correlations between sleep, stress, physical activity, BMI, occupation, and age-related health conditions. Using Power BI, I transformed raw data, created calculated measures, and built interactive dashboards to highlight lifestyle patterns and their impact on health.  
Additionally, I created a **presentation using Gamma** to visually communicate the insights in a structured and engaging way.

---

## ⚙️ Data Preparation
- **Data Cleaning:** Loaded raw data and cleaned it using **Power Query** (`Transform Data`).
- **Conditional Columns:** Added four new columns:
  - **Age Group** (based on age ranges)  
  - **Stress** (categorized by stress level)  
  - **Sleep Rating** (based on sleep quality)  
  - **Blood Pressure** (categorized into stages)
- **Category Adjustments:** Unified BMI categories by renaming *Normal Weight* → *Normal*.
- **Final Load:** Applied transformations and loaded the dataset using **Close & Apply**.

---

## 🧮 Measures (DAX)
Created custom measures for key metrics:
- `Avg Sleep Duration`
- `Avg Daily Steps`
- `Avg Physical Activity`
- `Avg Stress Level`

---

## 📈 Dashboard & Visualizations
The dashboard highlights multiple perspectives:

1. **Sleep Duration vs Stress Level**  
   - Shorter sleep (6–6.5 hrs) → higher stress (7–8).  
   - Longer sleep (7.5–8.5 hrs) → moderate/low stress (3–6).  
   - *Negative correlation clearly visible.*

2. **Occupation & Stress/Sleep**  
   - Doctors: ~6 hrs sleep, stress 8, Hypertension Stage 1.  
   - Lawyers: ~7.5 hrs sleep, moderate stress, Hypertension Stage 1.  
   - Teachers: ~6.5 hrs sleep, higher stress, Hypertension Stage 2.  
   - *Occupation strongly influences stress and hypertension risk.*

3. **BMI Category & Physical Activity**  
   - Normal BMI: Higher activity (60–90), 7K–8K steps.  
   - Obese: Lower activity (20–30), <4K steps.  
   - Overweight: Higher activity but higher stress.  
   - *Higher BMI → lower activity → higher stress & hypertension.*

4. **Age Group & Health Conditions**  
   - 27–37 yrs: Mostly Hypertension Stage 1.  
   - 37–47 yrs: More Hypertension Stage 2.  
   - Above 47 yrs: Hypertension Stage 2 + sleep disorders.  
   - *Age progression shows worsening hypertension and sleep issues.*

5. **Sleep Disorders**  
   - Insomnia & Sleep Apnea concentrated among Salespeople and Teachers.  
   - These groups show shorter sleep (~6.3–6.7 hrs) and higher stress (~7).  
   - *Sleep disorders amplify stress–hypertension cycle.*

---

## 📊 Charts Created
- **Bar + Line Chart:** Avg Stress Level & Sleep Duration by Occupation  
- **Line Chart:** Avg Physical Activity & Daily Steps by BMI  
- **Pie Chart:** Stress Levels (Low, Moderate, High)  
- **Pie Chart:** Sleep Quality (Good, Average, Bad)  
- **Line Chart:** Sleep Duration, Stress Level & Physical Activity by Age Group  
- **Table:** Age Group vs Hypertension Stages  

---

## 🔹 Actionable Insights
- **Targeted wellness programs:** Doctors & Teachers need stress management and sleep hygiene.  
- **BMI-focused activity plans:** Obese individuals should increase steps/activity; overweight individuals need stress management.  
- **Age-specific monitoring:** Above 47 yrs → proactive screening for hypertension & sleep disorders.  
- **Occupation-based health policies:** Salespeople & Lawyers show distinct stress/sleep patterns needing workplace wellness programs.

---

## 🚀 How to Use
1. Clone this repository.  
2. Open the `.pbix` file in Power BI Desktop.  
3. Explore the interactive dashboard using filters (Gender, Occupation, Age Group).  
4. Use the visualizations to analyze correlations and derive insights.  
5. View the **Gamma presentation** for a structured walkthrough of findings.

---

Would you like me to also draft a **short “Presentation” section** in the README that links or describes your Gamma presentation (e.g., “See the Gamma deck for a slide-based summary”)? That way, visitors know there’s both a dashboard and a presentation available.
