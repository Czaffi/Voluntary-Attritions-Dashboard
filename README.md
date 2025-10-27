# Power BI Headcount Dashboard

This repository contains a Power BI template (`.pbit`) and an Excel data source used to visualize headcount metrics such as start headcount, voluntary turnover, and related KPIs.

## ⚙️ Setup Instructions

Before using the Power BI template, you need to update the **file path** to the Excel data source on your own computer.  
By default, the `.pbit` file references the Excel file using the **local path** from the creator’s machine.  
To make it work on your device, please follow these steps:

### 1. Clone or download this repository
git clone https://github.com/<your-org-or-username>/<repo-name>.git
### 2. Update the .xlsx file path in Power BI
#### a. Open the .pbit (Power BI Template) file in Power BI Desktop.

#### b. When prompted to provide the file location, browse to where you saved the Excel file on your computer.

#### c. If the prompt does not appear:
Go to Transform Data → Data Source Settings → Change Source...
Update the path manually to point to your local version of the Excel file.
Example:
From:
C:\Users\Creator\Documents\Project\data\headcount_data.xlsx

To:
D:\MyProjects\HeadcountDashboard\data\headcount_data.xlsx
### 3. Apply changes and refresh the data
After updating the file path, click Close & Apply, then refresh the report.
Your Power BI dashboard should now load all the data correctly.
