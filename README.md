# Insurance-dataset-analysis
##  Prism Insurance Analytics: Claim & Policy Insights Dashboard 
A dynamic Power BI dashboard that provides a comprehensive view of insurance claims, customer distribution, and policy activity to support business decisions and operational monitoring.

This dashboard provides a complete overview of insurance operations, including claims, policy types, customer segments, and premium performance. It is built for insurance managers, analysts, and executives to track KPIs, detect patterns, and optimize strategies.

This dashboard was built using the following tools and technologies:

• 📊 Power BI Desktop – Core visualization and report creation platform

• 🧼 Power Query – Data cleaning, transformation, and shaping

• 🧠 DAX (Data Analysis Expressions) – Custom measures, KPIs, and visual logic

• 🗂️ Data Modeling – Relationships between customers, policies, claims


## Data Source
• Source: Internal generated file InsuranceData.csv containing 10,004 entries

• Structure Overview:

PolicyNumber, CustomerID, Gender, Age , PolicyType, PolicyStartDate, PolicyEndDate , PremiumAmount, CoverageAmount , ClaimNumber, ClaimDate, ClaimAmount, ClaimStatus

• Key Observations:

5,000 Male & 5,000 Female policyholders

3 Claim statuses: Pending, Settled, Rejected

Multiple policy types: Auto, Travel, Health, Life, Home

Age-wise segmentation allows for age group analysis (e.g., Young Adult, Adult, Elder)

Customers: Gender, ID

Claims: Status (Settled, Rejected, Pending), Claim Amount

Policies: Policy Type, Premiums, Activity Status (Active/Inactive)

Demographics: Age Groups (Young Adult, Adult, Elder)

## Business Problem
• Insurance firms need real-time visibility into claim handling, premium revenue, and inactive customers to maintain profitability and customer satisfaction.

## Goal of the Dashboard
• To deliver an interactive visual system that:

• Tracks total and categorized claim statuses

• Highlights premium and coverage by policy type and age group

• Analyzes customer distribution and policy activeness

• Helps stakeholders evaluate performance and risk

## Walkthrough of Key Visuals
### KPI Cards:

• Premium Amount: ₹5.97M

• Coverage Amount: ₹600.33M

• Claim Amount: ₹16.90M

• Gender Distribution:

Male: 5000

Female: 5000

• Bar Chart – Claim Status:

Rejected: 4.4K claims

Settled: 3.4K claims

Pending: 2.3K claims

• Bar Chart – Premium by Policy Type:
Travel insurance has the highest premium intake, followed by Health and Auto.

• Line Area Chart – Coverage by Age Group:
Adults dominate in total coverage, with Elders next and Young Adults trailing.

• Donut Chart – Policy Activeness:

Active: 5.81K (58.11%)

Inactive: 4.19K (41.89%)

• Detailed Matrix – PolicyType vs Claim Status:
Offers granular view of how each policy type is performing in claim settlements, rejections, and pending status.
## Business Impact & Insights
• Operational Efficiency: Helps identify backlog (Pending Claims) and rejection trends

• Product Strategy: Travel and Health policies are top contributors—can be cross-sold

• Risk Management: Elder demographics may need tailored coverage or pricing

• Customer Engagement: 42% of policies inactive—potential re-engagement campaign needed

![Alt text](https://github.com/LakshmiKopparthi/Insurance-dataset-analysis/blob/main/Insurance%20Dashboard.png)



