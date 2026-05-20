# Gym Membership Retention Analysis
Analaizing churn patterns across 1000 members to identify actionable retention strategy for gym managment.

## Business Context
Gyms typically lose 50% of their members within a 6 month period. This analysis identifies which factors predict member retention to help focus retention efforts.  

## Tools Used
Python (Pandas, NumPy, Matplotlib, Seaborn) | Power BI | DAX

## Dataset overview
- **1000 synthetic gym members** (Jan 2022 - Mar 2024)
- Variable: Membership Type, visit frequency, demographic, join date
- Data generated to reflect realistic gym behaviour patterns

## Analysis 

### Cohort Heatmap
**Objective:** Identify the cohort retention trend on an overall and membership type basis

**Key Findings:**
- Premium members show retention through 12 months while Standard/Basic members churn earlier
    - Standard members show retention up to ~9 months
    - Basic members typically drop off within 6 months
- A clear trend of Premium memberships staying the longest followed by Standard and Basic memberships

**Insight:** Membership tier directly correlates with retention duration. i.e. *Higher Investment = Longer Commitment*

### Effect of Frequency of Visit on Retention
**Hypothesis:** Members who visit more frequently have better retention 

**Key Findings:**
- Moderate positive correlation (r = 0.42) was identified
- Scatter plot used to visualize the relationship
- For clearer business communication visit frequency was categorized in to Low, Medium and High 
- Members with high visit frequency have **twice** as retention as members with low visit frequency.

**Insight:** Member visits directly correlates with retention duration. i.e. *Higher visits = Longer Commitment*

### Effect of PT Sessions Availed on Retention
**Hypothesis:** Members who avail more PT sessions show better retention 

**Key Findings:**
- Very weak correlation (r = 0.03) was identified
- PT sessions are not a retention driver - members using personal training showed similar retention to non-users

**Insight:** Unlike visit frequency, PT sessions don't predict retention - suggesting members stay for facility access, not personal training


## Dashboard
<img width="1799" height="983" alt="image" src="https://github.com/user-attachments/assets/e3cc0ab9-b8fb-4d72-b87d-936e2f488d60" />
<img width="1786" height="990" alt="image" src="https://github.com/user-attachments/assets/ea252d4e-dede-4010-994e-6cc9d25c5e75" />
<img width="1774" height="939" alt="image" src="https://github.com/user-attachments/assets/85de37fb-2de1-466b-a3d7-63deede35f9e" />


[View Live Dashboard](paste Power BI publish-to-web link her
