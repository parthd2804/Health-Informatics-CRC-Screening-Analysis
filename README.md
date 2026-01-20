# Health Informatics CRC Screening Analysis

## 📌 Project Overview
This project analyzes the relationship between **provider–patient communication** and **colorectal cancer (CRC) screening adherence** using nationally representative U.S. health survey data. The goal is to understand whether better communication increases the likelihood that adults are up-to-date with CRC screening and to highlight how **health informatics tools** can support preventive care.

This analysis was completed as part of the **IS460 – Health Informatics** course.

---

## ❓ Research Question
**Does better provider–patient communication increase the likelihood that adults are up-to-date with colorectal cancer (CRC) screening?**

---

## 📊 Dataset
- **Source:** National Cancer Institute (NCI)  
- **Survey:** Health Information National Trends Survey (HINTS 6)  
- **Cycle:** 2022–2023  
- **Population:** Adults aged 18+ in the United States  
- **Type:** Nationally representative, self-reported health communication survey  

Key variables include:
- CRC screening status  
- Provider explanations and recommendations  
- Opportunity for patients to ask questions  
- Demographics (age, gender, education)

---

## 🧠 Analysis Approach
The analysis was performed using **Python** in a **Jupyter Notebook** and includes:

- Data cleaning and recoding of communication variables  
- Descriptive statistics and visualizations  
- Chi-square tests to examine associations  
- Logistic regression to assess predictive relationships while controlling for demographics  
- Interpretation of odds ratios  

This approach allows both **association analysis** and **predictive modeling**.

---

## 📈 Key Findings
- Only **~19%** of respondents were up-to-date with CRC screening  
- General communication quality showed higher screening rates, but results were not always statistically significant  
- **Doctor recommendation for CRC screening** was the strongest predictor:
  - Increased odds of screening by approximately **56%**
- Older age groups were more likely to be screened
- Male respondents showed lower screening likelihood compared to females

---

## 🏥 Health Informatics Implications
The findings highlight the importance of informatics-supported communication, including:
- **EHR reminders** to prompt provider discussions
- **Clinical decision support (CDS)** to flag eligible patients
- **Patient portals and digital messaging** for education and follow-up
- **Public health informatics** for monitoring screening gaps across populations

Effective communication is not only interpersonal—it is strengthened by **health IT systems**.

---

## ⚠️ Limitations
- Cross-sectional survey design (cannot infer causation)
- Self-reported data may include recall bias
- Screening status measured using proxy variables
- Minor convergence issues in regression due to rare categories

---

## 🛠️ Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib / Seaborn  
- Statsmodels  
- Jupyter Notebook  

---

## 📁 Repository Structure
Health-Informatics-CRC-Screening-Analysis/
│
├── IS460_Project.ipynb # Main analysis notebook
└── README.md # Project documentation

---

## 📚 References
- National Cancer Institute. (2023). *Health Information National Trends Survey (HINTS 6)*  
- U.S. Preventive Services Task Force. (2021). *Screening for colorectal cancer*  
- Katz et al. (2011). *Patient–provider communication and CRC screening*  
- Krist et al. (2020). *Digital health tools and preventive screening*

---

## 👤 Author
**Parth Patel**  
Graduate Student – Information Systems  
University of Maryland, Baltimore County (UMBC)
