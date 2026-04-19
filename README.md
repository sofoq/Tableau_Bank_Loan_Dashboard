#  Bank Loan Dashboard  

## 📌 Project Overview  
This **Tableau** project analyzes bank loan applications for the year **2021**, providing insights into key financial metrics and trends. The dashboard dynamically updates based on user selections and allows for in-depth exploration of loan data.  


##  Key Dashboards  

### ** Summary Sheet**  
This sheet presents an overview of key performance indicators (**KPIs**) with **Month-to-Date (MTD)** and **Month-over-Month (MOM)** comparisons:  
- **Total Loan Applications**  
- **Total Funded Amount**  
- **Total Amount Received**  
- **Average Interest Rate**  
- **Average DTI (Debt-to-Income Ratio)**  

**Important:**  
- The **main KPIs** display the total values for the entire year (**2021**).  
- **MTD and MOM** values reflect only the difference between the most recent month and the previous month.  

Additionally, this sheet includes:  
- **Donut Charts**:  
  - **Good Loans**: Total applications, funded amount, and received amount.  
  - **Bad Loans**: Total applications, funded amount, and received amount.  
- **Matrix for Loan Status**: Displays detailed KPIs for each loan status.  

### ** Overview Sheet**  
This sheet allows users to select parameters (**Total Loan Applications, Total Funded Amount, or Total Received Amount**) using a slicer. All visualizations update dynamically based on the selected parameter:  
- **Area Chart** – Monthly trend of the selected parameter.  
- **Map by State** – Displays regional distribution of loans.  
- **Donut Chart by Term** – Breakdown of loan terms.  
- **Clustered Bar Chart by Employee Length** – Shows loan applications by employment duration.  
- **Clustered Bar Chart by Purpose** – Displays loan distribution by purpose.  
- **Heatmap by Home Ownership** – Analyzes homeownership trends in relation to loans.  

When a parameter is selected, every chart updates to reflect data specifically for that parameter.  

### ** Details Sheet**  
A detailed table containing granular information about each loan, allowing for deeper exploration of individual records.  

##  Dataset  
- The dataset contains loan application details for **2021**, including applicant demographics, financial metrics, loan amounts, interest rates, and loan status.

##  Screenshots  

###  Summary Dashboard  
![Summery](https://github.com/sofoq/Bank-Loan-Analysis/blob/main/SUMMARY.png)  

### Overview Dashboard  
![Overview](https://github.com/sofoq/Bank-Loan-Analysis/blob/main/OVERVIEW.png)  

### Details Dashboard 
![Details](https://github.com/sofoq/Bank-Loan-Analysis/blob/main/DETAILS.png)  


##  How to Use  
1. Use the **Summary Sheet** for high-level insights into loan performance and key KPIs.  
2. Switch between different parameters in the **Overview Sheet** using the slicer to analyze specific financial trends.  
3. Explore the **Details Sheet** for breakdown of loan data.  


