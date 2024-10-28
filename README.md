# Gender-Diversity-Inclusion-Report


## **Telecom Client - Executive Management Gender Balance Analysis**


## **Table of Contents**  
1. Introduction  
2. Problem Statement  
3. Stakeholders  
4. Data Preparation  
5. Data Analysis & Insights (with DAX Formulas)
6. Power BI Dashboard
7. Recommendations  
8. Conclusion  



## **1. Introduction**  
This report provides an analysis of gender diversity at the executive management level of a telecom company. The client has been working to improve gender balance in senior management but has not seen significant progress. The goal of this report is to identify current trends in gender representation, focusing on hiring, promotion, and turnover rates to offer data-driven recommendations to improve gender balance and foster a more inclusive workplace.





## **2. Problem Statement**  
Despite efforts to improve gender diversity, the company is struggling to make progress, particularly at the executive management level. This report seeks to uncover the underlying causes of the imbalance by analyzing key diversity and inclusion metrics, including gender-based hiring and promotion rates, turnover rates, and performance evaluations. By identifying areas of improvement, the company can take actionable steps toward achieving a more balanced workforce.





## **3. Stakeholders**  
- **HR Department**: Responsible for implementing diversity strategies, recruitment, promotions, and addressing turnover.  
- **Executive Leadership**: Tasked with championing diversity initiatives and ensuring equal opportunities at the senior level.  
- **Diversity & Inclusion Team**: Focused on creating an inclusive workplace environment and ensuring progress toward gender diversity goals.  



## **4. Data Preparation**  
The analysis draws on employee records for fiscal year 2021 (FY21), including details on gender, hiring, promotion, turnover, and performance ratings. The data was cleaned and transformed to focus on metrics related to gender diversity and representation at various levels of the organization.




## **5. Data Analysis & Insights (with DAX Formulas)**

**1. Gender Distribution:**  
- **Number of Female Employees:**  
  Formula:
  
         CALCULATE(DISTINCTCOUNT(Pharma[Employee ID]), FILTER(Pharma, Pharma[Gender] = "Female"))
  
- **Number of Male Employees:**  
  Formula:
  
        CALCULATE(DISTINCTCOUNT(Pharma[Employee ID]), FILTER(Pharma, Pharma[Gender] = "Male"))
  
- **Percentage of Female Employees:**  
  Formula:
  
        DIVIDE(Pharma[# of Female], Pharma[# of Female] + Pharma[# of Male])
  
- **Percentage of Male Employees:**  
  Formula:
  
          DIVIDE(Pharma[# of Male], Pharma[# of Female] + Pharma[# of Male])
  
  - The current gender distribution shows that **X%** of the executive team are women, while **Y%** are men, indicating a gender imbalance at the leadership level.




## **6. Power BI Dashboard**  

  ### Dashboard     
  
  ![Diversity And Inclusion Analysis](https://github.com/user-attachments/assets/6d222217-1858-4993-beb4-e6bd5547fa2c)
   
  ### Page 1 Dashboard
  
  ![Div 1](https://github.com/user-attachments/assets/f519d732-c0c6-4050-8d0e-4164529688c2)

  ### Page 2 Dashboard
  
  ![Div 2](https://github.com/user-attachments/assets/cedf612e-87c3-468c-84ca-3fac00485601)



## **7. Recommendations**  
**1. Targeted Recruitment:**  
   Implement strategies to recruit more women, particularly for senior and executive-level roles. This may include attending women-focused career fairs, partnering with organizations that promote women in leadership, and ensuring gender-neutral language in job descriptions.

**2. Promotion Programs for Women:**  
   Develop internal leadership programs aimed at preparing women for promotion into executive roles. Mentorship programs, leadership development workshops, and sponsorship from senior leaders can help women advance within the company.

**3. Reduce Turnover Among Women:**  
   Conduct exit interviews with women to understand the reasons behind their higher turnover rates. Based on feedback, implement policies to address their concerns, such as flexible working hours, family support initiatives, or opportunities for remote work.



## **8. Conclusion**  
The analysis reveals a significant gender imbalance at the executive level, with women being underrepresented. Addressing this issue requires a multifaceted approach, including targeted recruitment, promotion of women to leadership roles, and policies aimed at retaining female talent. By implementing these recommendations, the telecom client can make meaningful progress toward achieving gender balance and creating a more inclusive workplace culture.

---
