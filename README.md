# Insurance-Claims-project
Interactive Tableau dashboard analyzing health insurance premium factors using 30,000+ applicant records. Explores the impact of age, BMI, cholesterol, smoking status, exercise habits, and medical history on insurance costs.  Built with Tableau | Data Visualization | Insurance Analytics

# Insurance Claim Dashboard

![Tableau Dashboard Preview](https://via.placeholder.com/800x450?text=Insurance+Premium+Dashboard+Preview)

An interactive **Tableau dashboard** built to analyze and predict factors influencing **health insurance costs** based on 29,999+ applicant records.

## 🎯 Project Objective

This dashboard helps insurance companies, analysts, and customers understand:
- Which factors most strongly influence insurance premiums
- Risk profiling based on lifestyle and medical history
- Customer segmentation by cost brackets
- Regional and demographic trends in insurance pricing

## 📊 Key Insights Available

- **Impact of Age, BMI, Cholesterol & Glucose Levels** on premium
- Effect of **Smoking Status**, Alcohol consumption & Exercise habits
- Role of **Adventure Sports**, Regular Checkups & Doctor Visits
- **Heart Disease & Other Major Disease History** analysis
- Weight change, Fat percentage & Daily steps correlation
- City-wise / Location-wise premium distribution
- Occupation-wise (Salaried / Student / Business) premium trends

## 🛠️ Technologies Used

- **Tableau Desktop / Tableau Public** (Primary tool)
- Data Cleaning & Preparation in Tableau Prep / Excel / Python (optional)
- Dataset: 29,999+ rows × 24 columns

## 📁 Dataset Features

- `applicant_id`, `age`, `gender`, `bmi`, `weight`
- `cholesterol_level`, `avg_glucose_level`
- `smoking_status`, `Alcohol`, `exercise`
- `heart_decs_history`, `other_major_decs_history`
- `daily_avg_steps`, `fat_percentage`, `weight_change_in_last_one_year`
- `adventure_sports`, `regular_checkup_lasy_year`, `visited_doctor_last_1_year`
- `Occupation`, `Location`, `insurance_cost` (Target variable)

## 📌 Dashboard Sections

1. **Overview / KPI Cards**
2. **Demographic Analysis** (Age, Gender, BMI)
3. **Lifestyle & Risk Factors**
4. **Medical History Impact**
5. **Geographical Analysis** (City-wise)
6. **Cost Distribution & Segmentation**
7. **Correlation & Trend Analysis**

## 🚀 How to View the Dashboard

1. Go to the **Tableau Public** link (add your published link here)
2. Download the `.twbx` file from the repository
3. Open with **Tableau Desktop** or **Tableau Reader**

## 📂 Repository Structure

insurance-premium-analyzer-tableau/
├── Insurance_Premium_Analyzer.twbx     # Packaged Tableau Workbook
├── Data.csv                            # Original dataset
├── README.md
├── screenshots/                        # Dashboard screenshots
│   ├── overview.png
│   ├── lifestyle-analysis.png
│   └── ...
├── insights.md                         # Key business insights (optional)
└── LICENSE


## 🔍 Key Findings (Add after your analysis)

- Smoking status increases premium by X% on average
- BMI above 30 significantly impacts cost
- Regular checkups help reduce premium

## ✨ Features

- Fully interactive filters (Age group, Gender, Smoking, City, etc.)
- Dynamic tooltips
- Responsive layout
- Professional color scheme
- Clear storytelling
