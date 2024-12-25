# HR Analytics Dashboard  

## Dashboard Overview  

This **HR Analytics Dashboard** visualizes key employee attrition metrics across multiple dimensions, providing detailed insights into factors contributing to employee turnover. Below, we describe the process followed to create this dashboard and explain the purpose and insights of each chart used in it.  

---

## Process of Creating the Dashboard  

### **Step 1: Data Preparation**  
- **Source of Data**: The data was obtained from the HRAnalytics.csv and loaded into Microsoft Power BI.  
- **Data Cleaning**:  
  - Removed duplicates to ensure data accuracy.  
  - Addressed missing or inconsistent entries by imputing values or removing invalid rows.  
  - Standardized columns such as job roles, salary brackets, and education levels for uniformity.  

### **Step 2: Data Transformation and Modeling**  
- Utilized **Power Query** to transform the data:  
  - Grouped and filtered data to focus on key dimensions like age, education, job role, and salary.  
  - Created a calculated measure for **Attrition Rate** in PowerPivot:  
    \[
    \text{Attrition Rate} = \frac{\text{Number of Employees Left}}{\text{Total Number of Employees}} \times 100
    \]  

### **Step 3: Designing the Dashboard**  
- Selected appropriate visualizations to represent key dimensions and metrics.  
- Organized the layout for clarity:  
  - Placed KPIs (e.g., employee count, attrition rate) at the top for quick insights.  
  - Used intuitive visual formats (e.g., pie charts, bar charts) to ensure readability.  

---

## Breakdown of Charts and Their Purpose  

### **1. Attrition by Education (Pie Chart)**  
- **Purpose**: Displays the distribution of attrition based on employees' educational backgrounds.  
- **Why Used**: Pie charts effectively showcase proportions and highlight differences among categories.  
- **Insight**:  
  - Minimal attrition in Marketing and Technical Degrees suggests strong retention in these fields.  
  - Attrition in Life Sciences (2%) could require additional investigation.  

---

### **2. Attrition by Salary (Bar Chart)**  
- **Purpose**: Breaks down attrition by salary brackets to understand how compensation influences turnover.  
- **Why Used**: Bar charts provide a clear view of categorical comparisons like salary ranges.  
- **Insight**:  
  - High attrition for employees earning less than $5K indicates a need to revisit compensation policies for lower brackets.  

---

### **3. Attrition by Age (Bar Chart)**  
- **Purpose**: Examines the age distribution of employees leaving the organization.  
- **Why Used**: Bar charts clearly show attrition counts for discrete age groups.  
- **Insight**:  
  - Attrition peaks in the **26–35 age group**, possibly due to career growth opportunities outside the company.  

---

### **4. Attrition by Years of Experience (YOE) at Company (Line Chart)**  
- **Purpose**: Analyzes attrition trends based on tenure in the company.  
- **Why Used**: Line charts effectively highlight trends over time or sequential data points like years of experience.  
- **Insight**:  
  - Spikes in attrition for employees with less than **5 years of experience** underscore the need to improve engagement strategies for new hires.  

---

### **5. Attrition by Job Role (Bar Chart)**  
- **Purpose**: Highlights attrition trends across different job roles.  
- **Why Used**: Bar charts are effective for comparing counts across categories like job roles.  
- **Insight**:  
  - **Laboratory Technicians** and **Sales Executives** exhibit higher attrition rates, suggesting job-specific challenges like workload or job satisfaction.  

---

### **6. Attrition by Gender (Stacked Bar Chart)**  
- **Purpose**: Provides a comparison of attrition rates between male and female employees.  
- **Why Used**: Stacked bar charts effectively compare two subcategories (male vs. female) within a broader category (attrition).  
- **Insight**:  
  - Minimal gender difference in attrition indicates no significant gender bias.  

---

### **Summary Metrics**  
The KPIs displayed at the top of the dashboard provide a quick summary of workforce metrics:  
- **Total Employee Count**: 47 employees included in the analysis.  
- **Total Attrition**: 8 employees left the organization.  
- **Attrition Rate**: 17%, calculated as a dynamic measure in PowerPivot.  
- **Average Employee Age**: 58 years.  
- **Average Salary**: $9.2K.  
- **Average Tenure**: 8.5 years at the company.  

These metrics give an at-a-glance view of the organization's overall workforce health.  

---

## Why This Dashboard Is Effective  

1. **Data-Driven Insights**: Provides actionable insights into key dimensions such as salary, job role, and experience to help HR leaders address root causes of attrition.  
2. **Clear Visuals**: Organized layout and appropriate chart types make data easy to interpret for stakeholders.  
3. **Customizable Filters**: Allows interactive analysis by drilling down into specific departments, salary brackets, or age groups.  
4. **Strategic Decision-Making**: Supports HR teams in designing targeted retention programs and refining hiring strategies.  

This dashboard equips HR professionals with the tools and insights needed to proactively address employee turnover and create a healthier, more engaged workforce.
