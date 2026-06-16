# 🛒 Google Merchandise Store: Conversion Funnel & Revenue Analysis

![Dashboard Preview](E-Commerce%20Performance%20Dashboard.png)

This repository contains an end-to-end data analytics project focused on optimizing the e-commerce performance of the **Google Merchandise Store**. Using a raw GA4 dataset of approximately **360,000 rows**, I developed a Business Intelligence solution to identify conversion bottlenecks and provide data-driven strategic recommendations.

## 📊 Project Overview
The objective was to map the 7-step user journey—from the initial landing to the final purchase—and determine where the highest friction occurs. By analyzing traffic sources and device categories, this project aims to help stakeholders optimize marketing budgets and improve user experience.

## 🛠️ Tech Stack
* **Data Warehousing:** Google BigQuery
* **Query Language:** SQL (Standard SQL)
* **Business Intelligence:** Tableau Public
* **Analytic Techniques:** Funnel Analysis, CTE (Common Table Expressions), Data Cleaning, User Behavior Segmentation.

## 🚀 Technical Implementation

### 1. Data Engineering (BigQuery & SQL)
The raw GA4 dataset presented a challenge: session-level details and event-specific funnel steps were stored in nested or disconnected structures. 
* Engineered **CTEs (Common Table Expressions)** to flatten and join datasets.
* Linked disparate events using a `unique_session_id` logic to ensure a seamless track of the user journey.
* Restructured raw data into aggregated tables optimized for high-speed Tableau rendering.

### 2. Dashboard Design (Tableau)
The interactive dashboard was built with the **Executive Decision-Maker** in mind, adhering to:
* **The F-Pattern:** Placing high-level KPIs and the Funnel at the top-left for natural visual hierarchy.
* **The 5-Second Rule:** Ensuring that a manager can grasp the "health of the store" in under 5 seconds.
* **Dynamic Filtering:** Users can drill down by Device, Language, Source, and Campaign.

## 💡 Key Insights & Strategic Findings
* **The Discovery Bottleneck:** **78% of users** drop off before even viewing a specific product. This indicates a need to optimize homepage navigation and internal search functions.
* **Mobile UX Friction:** While mobile traffic volume is high, the conversion rate during the checkout phase is significantly lower than desktop. Recommendation: Simplify the mobile payment interface.
* **Source Efficiency:** **Google/Organic** search provides the highest quality traffic with the best ROI. Marketing efforts should prioritize SEO and organic growth.

## 🔗 Live Links
* **Interactive Tableau Dashboard:** [Click Here to View](https://public.tableau.com/views/InteractiveE-CommerceDashboard_17780202865100/E-CommercePerformanceDashboard?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
* **Project Presentation Video:** [Watch on Loom](https://www.loom.com/share/53b2bae616b54428892a7f0c414caf66)

---

### 📬 Contact
I am a Data Analyst transitioning from a background in **Science Education**, passionate about turning complex data into actionable business stories.

* **LinkedIn:** [Beyza Melike Mercan](https://www.linkedin.com/in/beyza-melike)
* **Email:** beyzamelikem@outlook.com
