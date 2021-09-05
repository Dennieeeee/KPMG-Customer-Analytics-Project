# KPMG-virtual-internship Project

### Feel free to contact me:
Email: dengyuantan@gmail.com <br>
LinkedIn: https://www.linkedin.com/in/dengyuan-tan/<br>
## Overview
This project is sponsored by KPMG. The datasets including customer and product information were provided by one of KPMG's clients, Sprocket Central Pty Ltd. I will be using the data to conduct customer segmentation and find useful information. The goal is use the historical customer information to find out who the marketing department should be targeting out of the 1000 new customer list.
- First, I will ensure the data quality and prepare the data for the next step
- Second, I will use Python to find data insights.
- Finally, I will present the key findings.

## Findings and Insights
Tableau Dashboard: 'https://public.tableau.com/profile/dengyuan.tan#!/vizhome/KPMGSummaryDashboard_16035112669790/Dashboard1'

## Table of Contents
<details open>
<summary>Show/Hide</summary>
<br>

1. [ File Descriptions ](#File_Description)
2. [ Technologies Used ](#Technologies_Used)    
3. [ Statistical Summary ](#Statistical_Summary)
   * [ 1. Cleaning and Early EDA ](#Early_EDA_and_Cleaning)
       * [ Solve the Data Quality Issues](#Data_Quality_Issues)
   * [ 2. Further EDA and Preprocessing ](#Further_EDA_and_Preprocessing) 
       * [ Univariate and Muti-variate Tests](#Early_EDA_and_Cleaning)
   * [ 3. Modelling and Hyperparameter Tuning ](#Modelling)
   * [ 4. Evaluation ](#Evaluation)
       * [ Future Improvements ](#Future_Improvements)
</details>

<a name="File_Description"></a>
## File_Description
File link: "https://drive.google.com/file/d/1MAQhwAGqGn0mTNcOatJGFFXUK1DBivR_/view?usp=sharing"

<a name="Technologies_Used"></a>
## Technologies Used
<details open>
<a name="Technologies_Used"></a>
<summary>Show/Hide</summary>

  * <strong>Python</strong><br>
  * <strong>Pandas</strong><br>
  * <strong>Numpy</strong><br>
  * <strong>Matplotlib</strong><br>
  * <strong>Seaborn</strong><br>
</details>

<a name="Executive_Summary"></a>
## Statistical Summary
<details open>
<summary>Show/Hide</summary>
  I have subset the data into three different categories based on wealth segment. I built bar charts to compare the number of purchases made by men and women
  for each subset of data. As a result, Solex is the most popular brand and women tend to make more purchases than men.
  - Affluent USD 500K - 999k
  - Mass Customer: USD 250K - 499K
  - High Net Worth: USD 1 Million to 3.5 Million

<h5 align="center">Compare Customers in Different Wealth Segment</h5>
  <table>
  <tr>
    <td><img src="https://github.com/Dennieeeee/KPMG-Customer-Analytics-Project/blob/master/Images/Affluent.png" width=400></td>
    <td><img src="https://github.com/Dennieeeee/KPMG-Customer-Analytics-Project/blob/master/Images/High%20Net%20Worth.png" width=400></td>
    <td><img src="https://github.com/Dennieeeee/KPMG-Customer-Analytics-Project/blob/master/Images/Mass%20Customer.png" width=400></td>
  </tr>                                                                                                      
  </table>

<h5 align="center">Brand Popularity Women vs. Men</h5>
<p align="center">
  <img src="https://github.com/Dennieeeee/KPMG-Customer-Analytics-Project/blob/master/Images/women%20vs.%20men.png" width=600>
</p>

<h5 align="center">Brand POpularity for People with High Buying Power</h5>
<table>
  <tr>
    <td><img src="https://github.com/Dennieeeee/KPMG-Customer-Analytics-Project/blob/master/Images/High%20Buying%20Power's%20favoriate%20brand.png" width=600></td>
    <td><img src="https://github.com/Dennieeeee/KPMG-Customer-Analytics-Project/blob/master/Images/Rich%20Female%20and%20Male%20Favorite%20Brand.png" width=600</td>
  </tr>                                                                                                      
</table>

Reference: "https://advisor.johnhancockinsurance.com/content/dam/JHINS/images/NLI/Home%20Log%20Out/Life%20Insurance/Collateral/large-case/day-2/2019_sri_wealth_segments.pdf"

</details>

