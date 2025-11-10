<h1>Customer Segmentation and Response Prediction in iFood’s Marketing Campaigns Using Machine Learning</h1>

<p><strong>Course ID:</strong> 241MI1702<br>
<strong>Instructor:</strong> Assoc. Prof. Ho Trung Thanh, Ph.D.<br>
<strong>Group:</strong> 05</p>

<h2>1. Project Overview</h2>
<p>
This project applies data analytics and machine learning techniques to analyze the iFood marketing dataset. 
Its objective is to develop a data-driven decision support framework that enables businesses to understand 
customer behavior, identify key market segments, and evaluate the effectiveness of marketing campaigns.
</p>
<p>
The study combines <strong>Python-based clustering</strong> and <strong>predictive modeling</strong> 
with <strong>Power BI visualizations</strong> to generate actionable insights for managerial decision-making.
</p>

<h2>2. Folder Structure</h2>
<pre>
241MI1702_Group05_FinalProject/
│
├── Datasets/
│   ├── iFood.xlsx
│   ├── iFood_cluster_0.xlsx
│   ├── iFood_cluster_1.xlsx
│   ├── iFood_cluster_2.xlsx
│   └── iFood_clustered_data_all.xlsx
│
├── PowerBI/
│   ├── CustomerOverviewDashboard.pbix
│   ├── Response_Analysis.pbix
│   ├── Segment_Overview.pbix
│   ├── Segment_AffluentMatureBuyers.pbix
│   ├── Segment_BudgetConsciousYoungFamilies.pbix
│   └── Segment_TraditionalFamilySpenders.pbix
│
├── Source code/
│   └── Group05_Coding_Chapter2+Chapter3.ipynb
│
├── Report/
│   ├── Group05_FinalReport.pdf
│   └── Group05_FinalReport.docx
│
└── Readme.docx
</pre>

<h2>3. Component Descriptions</h2>

<h3>Datasets</h3>
<ul>
  <li><code>iFood.xlsx</code>: The original dataset used for preprocessing and exploratory data analysis.</li>
  <li><code>iFood_cluster_0.xlsx</code>, <code>iFood_cluster_1.xlsx</code>, <code>iFood_cluster_2.xlsx</code>: Clustered subsets created through K-Means segmentation, representing distinct customer groups.</li>
  <li><code>iFood_clustered_data_all.xlsx</code>: The consolidated dataset combining all customer segments, used as the main data source for Power BI visualization.</li>
</ul>

<h3>Source Code</h3>
<ul>
  <li><code>Group05_Coding_Chapter2+Chapter3.ipynb</code>: Jupyter Notebook containing the complete analytical workflow, including data cleaning, EDA, feature engineering, preprocessing, feature selection, clustering, and response prediction.</li>
</ul>

<h3>Power BI</h3>
<ul>
  <li><code>CustomerOverviewDashboard.pbix</code>: Summary of customer profiles and KPIs.</li>
  <li><code>Response_Analysis.pbix</code>: Dashboard analyzing campaign response rates and customer behavior.</li>
  <li><code>Segment_Overview.pbix</code>: Combined summary view of all three segments.</li>
  <li><code>Segment_AffluentMatureBuyers.pbix</code>: In-depth analysis of “Affluent Mature Buyers.”</li>
  <li><code>Segment_BudgetConsciousYoungFamilies.pbix</code>: Analysis of “Budget-Conscious Young Families.”</li>
  <li><code>Segment_TraditionalFamilySpenders.pbix</code>: Insights into the “Traditional Family Spenders” group.</li>
</ul>

<h3>Report</h3>
<ul>
  <li>Contains the final written report and related documentation in both PDF and DOCX formats.</li>
</ul>

<h3>Readme</h3>
<ul>
  <li>This document describes project objectives, structure, and components. It serves as a reference guide for instructors and evaluators reviewing the project package.</li>
</ul>

<h2>4. Tools and Methodology</h2>
<ul>
  <li><strong>Programming Languages:</strong> Python</li>
  <li><strong>Visualization Tools:</strong> Power BI Desktop</li>
  <li><strong>Analytics Framework:</strong> CRISP-DM (Cross-Industry Standard Process for Data Mining)</li>
  <li><strong>Models:</strong> K-Means (Segmentation), Logistic Regression, Random Forest, XGBoost (Response Prediction)</li>
</ul>
