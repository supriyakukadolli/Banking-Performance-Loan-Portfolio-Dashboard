# Banking-Performance-Loan-Portfolio-Dashboard
I developed a comprehensive project in PowerBI, creating multiple dashboard and tables to analyze the data. This process involves the several stages, including preprocessing and dashboard
1. Banking Performance & Loan Portfolio Dashboard
A comprehensive, interactive analytics suite designed to monitor the health of bank loan portfolios and operational efficiency. It unifies critical financial KPIs—such as total funded amounts, interest income, and retention rates—with deep-dive analytics into repayment behavior, branch performance trends, and client risk profiles (Good vs. Bad loans) to drive data-led lending strategies.
2. Short Description / Purpose
The Fine Sight Banking Dashboard is a dynamic and data-rich PowerBI report designed to enable financial stakeholders to monitor and analyze the health of a 52M loan portfolio across various branches and client segments. The dashboard focuses on highlighting critical KPIs such as repayment behavior, good VS bad loan ratios, product profitability, and interest income trends over time. This tool is intended for use by bank managers, credit risk analysts, and financial strategists who seek to optimize operational efficiency and minimize credit risk through data-driven insights.
3. Tech Stack
The dashboard was built using the following tools and technologies:
•	Power Query – The ETL (Extract, Transform, Load) engine used for data cleaning, type conversion, and reshaping raw banking data for analysis.
•	 DAX (Data Analysis Expressions) – Utilized to create complex calculated measures and enable dynamic time-intelligence filtering.
•	Data Modeling – Relationships were established between fact tables  and dimension tables to support robust cross-filtering and slicing.
4. Data Source
The data for this dashboard is typical of a banking portfolio analysis project. Given the level of detail on client demographics, loan status, and branch performance, the underlying data would likely be sourced from a bank's internal systems.
5. Features / Highlights
The Business Problem: 
•	Good Loan vs. Bad Loan Ratio: Provides immediate visibility into the quality of the portfolio (88.99%$Good vs. 11.01% Bad), enabling management to track the Non-Performing Loan (NPL) rate and set risk tolerance levels.
•	Repayment Behavior: Categorizing repayments (On-Time, Late, Very Late) allows the bank to identify borrowers moving toward default before they become "Bad Loans," enabling proactive collections efforts.
•	Client Income Range & Interest Rate by Purpose: Helps analysts correlate risk factors (like low income or certain loan purposes) with default rates, informing future underwriting policies.
•	Total Loans Per Branch / Branch Performance: Allows the regional manager to benchmark the performance of branches (e.g., Agra vs. Asansol), identifying high-performing branches for best-practice sharing and underperforming ones that require coaching or attention.
•	Product Profitability: Clearly shows which loan products (e.g., JLG30K) are most profitable, guiding the sales team on where to focus marketing and sales efforts.
•	Total Payment Received by Month/Year: Tracks the monthly flow of funds, providing essential data for cash flow forecasting and budget management.
•	Retention Rate (67.24%): A crucial high-level KPI that tells the leadership team the success rate of retaining clients, a direct measure of client satisfaction and long-term revenue stability.
•	New Client Trend: Tracks client acquisition over time, showing the growth trajectory and the effectiveness of marketing or outreach programs.

The GOAL of the Fine Sight Banking Dashboard is to deliver an interactive visual tool that: Enables bank stakeholders to monitor the financial health and operational efficiency of the loan portfolio. It supports critical decisions related to credit risk assessment, resource allocation (branch comparison), and optimization of lending product profitability...

• Walkthrough of Key Visuals
Here is a walkthrough of the key visuals and interactive elements on your "Fine Sight: Banking Performance & Loan Portfolio Dashboard," explaining what each section shows and the insights it provides, mirroring the structure you provided.
• Key KPIs (Top Left)
These cards provide the immediate, high-level financial snapshot of the analyzed portfolio.
•	Total Funded Amount (52.4M): The overall size of the bank's lending portfolio being analyzed.
•	Total Payment Collected (53.9M): The cumulative amount received from borrowers, often used to track progress against the principal and interest.
•	Interest Income (5.06M): The core revenue generated directly from the interest charges on loans, reflecting true profitability.
•	Retention Rate (67.24%): The percentage of customers who remain active with the bank over a defined period, a vital measure of client loyalty and long-term stability.
•	Active Clients (324) / Total Client (1000): Provides context on the size of the client base and the proportion currently engaged in lending products.
• Filter Panel (Top Right Slicers)

These interactive slicers allow users to dissect the portfolio data for deeper analysis.
•	Year, Month Name: Enables time-based trend analysis, allowing managers to focus on a specific quarter or month to review performance or investigate anomalies.
•	Grade: Filters the data by the bank's internal customer segmentation or risk rating, allowing users to assess the performance of high-risk vs. low-risk clientele.
•	Branch Name: (Likely on the second page/tab) Allows a focus on the operational performance and loan portfolio health of a single branch.
• Good Loan vs. Bad Loan (Donut Chart)

This is a critical risk visualization used for immediate assessment of portfolio quality.
•	What it shows: The proportion of the total loan portfolio that is currently performing well (Good Loan) versus the portion that is non-performing or in default (Bad Loan).
•	Helps Identify: The bank's overall Non-Performing Loan (NPL) ratio and allows for benchmarking against industry standards.
• Repayment Behavior (Bar Chart)

This visual breaks down the status of all active loans based on adherence to the repayment schedule.
•	What it shows: The volume of loans categorized as On-Time, Late, and Very Late (or in a similar delinquency status).
•	Helps Identify: Early warning signs of distress. The bank can use this to prioritize collection efforts on accounts transitioning from Late to Very Late.
• Total Loans Per Branch (Bar Chart)

This chart compares the operational output and scale across the bank's physical locations.
•	What it shows: The number of loans originated or the total loan volume (amount) attributed to specific branches (e.g., Agra, Asansol).
•	Helps Identify: Which branches are the highest volume generators and aids in resource allocation (staffing, marketing budgets).
• Product Profitability (Bar Chart)

This chart is key for strategic planning and optimizing the product mix.
•	What it shows: The profit generated or the volume of loans for each specific lending product (e.g., JLG30K, Home Loan, Car Loan).
•	Helps Identify: The most financially successful products to determine where marketing and sales efforts should be concentrated.
• New Client Trend (Line Chart)

These visual tracks the bank's ability to grow its customer base over time.
•	What it shows: The count of new clients acquired over a timeline (e.g., month-over-month or year-over-year).
•	Helps Identify: The effectiveness of client acquisition strategies and aids in forecasting future client growth.
• Branch Performance / Interest Rate by Purpose (Charts)

These visuals provide granular details for risk and operational review.
•	Branch Performance (Treemap/Map): Categorizes branches as High, Medium, or Low performance (likely based on profitability or loan quality), aiding in quick operational assessment.
•	Interest Rate by Purpose (Bar Chart): Compares the average interest rate applied to different loan categories (e.g., Services, Home Loan). This helps analysts confirm that riskier loan purposes are being priced appropriately.

Here is the business impact and key insights delivered by the "FinSight: Banking Performance & Loan Portfolio Dashboard":

💼 Business Impact & Insights
•	Risk Mitigation & Provisioning: Enables the Finance team to proactively manage credit risk by identifying high-risk segments (e.g., specific income ranges or loan purposes) and accurately setting provisions based on the Good vs. Bad Loan ratio.
•	Operational Efficiency & Strategy: Allows bank managers to benchmark and reward branch performance based on volume and loan quality, leading to optimized resource allocation and the adoption of successful lending practices across the organization.
•	Profitability Optimization: Provides clear data on Product Profitability and Interest Income drivers, guiding executive decisions on which loan products to promote or discontinue to maximize revenue.
•	Client Management & Retention: Monitors the Retention Rate and New Client trends, offering insights to the CRM and Marketing teams on improving customer loyalty and growing the active client base.

6. Screenshots 
https://github.com/supriyakukadolli/Banking-Performance-Loan-Portfolio-Dashboard/blob/banking-performance-dashborad/Banking%20Performance%20Dashborad.png

https://github.com/supriyakukadolli/Banking-Performance-Loan-Portfolio-Dashboard/blob/banking-performance-dashborad/Bank%20Loan%20Report.png

