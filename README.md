# Adesh Kumar Pal - Data Analyst Portfolio

## About

Hi, I'm Adesh! I combine an engineering foundation from Netaji Subhas University of Technology (NSUT) with a passion for transforming complex datasets into actionable business and product strategies. My quantitative aptitude—backed by securing **All India Rank (AIR) 556 in GATE 2026 (Mechanical Engineering)**—drives my structured approach to diagnosing root causes, modeling risk, and optimizing systems.

Through hands-on internships and end-to-end analytics projects, I have worked across the full data lifecycle: querying raw event streams in SQL, performing exploratory modeling in Python, and designing executive-ready dashboards in Power BI and Tableau. My experience ranges from detecting fintech lending drop-offs and modeling labor market AI disruption to slashing automotive logistics turnaround times at Maruti Suzuki.

In my free time, I enjoy dissecting product mechanics, exploring Generative AI applications, and working on graphic design. Whether working with cross-functional product squads or diving deep into raw telemetry independently, I thrive on the thrill of uncovering hidden patterns and turning data into measurable outcomes.

My CV in [pdf](link).

This is a repository to showcase skills, share projects, and track my progress in Data Analytics / Product Analytics related topics.

## Table of Contents

* [About](#about)
* [Portfolio Projects](#portfolio-projects)
  * Power BI / Python
    * [The AI Exposure Landscape: Workforce Risk Analysis](#the-ai-exposure-landscape-workforce-risk-analysis)
  * SQL / Tableau
    * [Cars24 Lending & Credit Card Funnel Optimization](#cars24-lending--credit-card-funnel-optimization)
  * Excel / Product Analytics
    * [Amazon Prime Video Channels Monetization Strategy](#amazon-prime-video-channels-monetization-strategy)
    * [Maruti Suzuki Logistics TTAT Optimization](#maruti-suzuki-logistics-ttat-optimization)
* [Education](#education)
* [Certificates](#certificates)
* [Contact](#contact)

## Portfolio Projects

In this section I will list data analytics projects briefly describing the technology stack used to solve cases.

### The AI Exposure Landscape: Workforce Risk Analysis

**Code:** [`AI_Workforce_Exposure_Analysis.pbix`](#)

**Goal:** To determine exactly which jobs, industries, and education levels are most at risk from AI disruption.

**Description:** This project focused on analyzing a massive dataset encompassing 82 million US jobs. Instead of relying on a single data source, the project involved combining pre-LLM exposure scores with newer LLM-based metrics to build a balanced, bias-checked model of workforce trends. The project included data loading, smoothing out model divergences (especially around physical and creative jobs), and mapping exposure against wage levels, education requirements, and cognitive skills (verbal, spatial, quantitative, and reasoning).

**Skills:** data cleaning, bias reconciliation, exploratory data analysis (EDA), risk profiling, interactive data visualization.

**Technology:** Power BI, Python, DAX.

**Results:** The analysis revealed a "College Degree Paradox" where jobs requiring a Bachelor's degree have the highest AI exposure rate (0.47), while jobs requiring no formal education sit at just 0.12. Furthermore, visualizing cognitive skills proved that Spatial Ability is currently the strongest defense against AI automation.

### Cars24 Lending & Credit Card Funnel Optimization

**Code:** [`Cars24_Funnel_Analysis.sql`](#)

**Goal:** To diagnose end-to-end conversion drop-offs, credit-tier bottlenecks, and pricing inconsistencies across financial products to maximize disbursals.

**Description:** The dataset contained records for 2,579 loan applications and 3,627 credit card leads. The project mapped the user journey from login to partner processing, approval, and issuance. Steps included writing SQL queries to segment users by CIBIL bands and internal risk grades, identifying stage-by-stage funnel leakage, and auditing partner lender performance across different geographic states.

**Skills:** funnel analysis, SQL querying, customer segmentation, credit risk analysis, conversion rate optimization.

**Technology:** SQL Server, Tableau, Microsoft Excel.

**Results:** Diagnosed a 63% drop-off at the initial login stage and an 85% drop-off between credit card selection and submission. The analysis also uncovered 295 pricing anomalies where high-risk customers secured better rates than low-risk profiles, and recommended shifting traffic to high-performing lenders, projecting a 20% disbursal uplift.

### Amazon Prime Video Channels Monetization Strategy

**Code:** [`Prime_Video_Monetization_Model.xlsx`](#)

**Goal:** To uncover the root cause behind low Prime Video Channels conversion and architect a data-backed product monetization framework.

**Description:** The project investigated why a base of 65.9M subscribers in India yielded only a 6% paywall conversion rate for add-on channels. A hypothesis-driven primary research study (n=50 verified users) was conducted to map the user journey and test core behavioral blockers. The findings informed a top-down financial model (TAM/SAM/SOM) sizing the impact of two proposed features: 1-Tap micro-billing and regional content windowing.

**Skills:** hypothesis testing, quantitative user research, unit economics modeling, TAM/SAM/SOM sizing, KPI framework design.

**Technology:** Excel (Financial Modeling), Figma, Product Analytics.

**Results:** Research confirmed that 94% of users perceive add-on paywalls as unfair "double-charging," triggering immediate defection to free alternatives. Modeled a highly defensible base-case projecting ₹97.2 Cr gross consumer spend and ₹29.2 Cr incremental net revenue for Amazon, alongside a comprehensive L1/L2 metric tracking framework.

### Maruti Suzuki Logistics TTAT Optimization

**Code:** [`Maruti_Supply_Chain_Analytics.xlsx`](#)

**Goal:** To reduce truck turnaround time (TTAT) and eliminate peak-hour roadside congestion across loading/unloading bays.

**Description:** The project analyzed hourly congestion metrics and vendor arrival data at India's largest passenger-vehicle manufacturer. It involved mapping current supply chain bottlenecks, driving the rescheduling of vendor E-nagare timings, and designing an automated First-Come-First-Served (FCFS) digital token system linked to real-time bay telemetry dashboards.

**Skills:** supply chain analytics, bottleneck analysis, process digitization, workflow mapping.

**Technology:** Microsoft Excel, IIoT Telemetry Systems.

**Results:** Successfully slashed average truck turnaround time from 151 minutes to 85 minutes (a 43.7% reduction). E-nagare rescheduling of 13 vendors effectively shifted peak-hour congestion from red to green operating zones, and vendor safety buffer hours were reduced by 50%.

## Education

*   **Netaji Subhas University of Technology (NSUT), Delhi:** B.Tech, Mechanical Engineering, 2023 - 2027
*   **Bal Bhavan Public School, Delhi:** AISSCE (Class XII), 2022

## Certificates

The best way to showcase skills is by doing and sharing your work, but sometimes certificates appear to be as an indirect result. Here's a list of the ones I have:

*   Build a Computer Vision App with Azure Cognitive Services (Microsoft)
*   Introduction to Generative AI, LLMs & Responsible AI (Google)

## Contact

*   **LinkedIn:** [@Adeclak](https://www.linkedin.com/in/Adeclak)
*   **Email:** [adesh6603@gmail.com](mailto:adesh6603@gmail.com)
