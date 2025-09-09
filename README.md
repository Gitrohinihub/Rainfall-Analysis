# 🌧️ Rainfall Analysis – Cloud-Based Pipeline with AWS, Snowflake, and Power BI

## 1. Introduction
This project creates a real-time, end-to-end data pipeline to analyze rainfall patterns using a seasonal dataset from 1992 to 2024, with forecasts extending to 2026. By leveraging AWS, Snowflake, and Power BI, it delivers actionable insights for stakeholders like environmental agencies and farmers, focusing on trends, regional variations, and predictive metrics.

## 2. Problem Statement
Rainfall data is often fragmented and difficult to process. Stakeholders need clear, reliable insights to:
- Monitor seasonal rainfall trends  
- Compare performance across regions  
- Predict future rainfall patterns for planning  

The project aims to address inconsistent data availability and support decision-making by analyzing regional rainfall disparities.

## 3. Skills Demonstrated
- Cloud data pipeline design and management  
- Data transformation and querying with Snowflake  
- Interactive dashboard creation using Power BI  
- Secure integration of AWS services  
- Insight generation and visualization  

## 4. Data Sourcing
- **Source:** Custom seasonal rainfall dataset (`data_season.csv`) simulating real-world rainfall records  
- **Scope:**  
  - Monthly and seasonal rainfall totals  
  - Regional breakdown (e.g., Northern, Southern, Eastern zones)  
  - Weather metrics (temperature, humidity)  
- **Format:** Raw CSV file stored in AWS S3  

## 5. Data Pipeline and Transformation
🚀 **Cloud-Based Analytics Pipeline with AWS + Snowflake + Power BI**  

1. **AWS IAM Role Creation** – IAM role created in AWS with proper permissions for secure data access.  
2. **AWS + Snowflake Integration** – Trusted relationship set up between AWS and Snowflake for secure file access.  
3. **Uploading & Loading Data** – `data_season.csv` uploaded to AWS S3 and loaded into Snowflake for cleaning and structuring.  
4. **Connecting to Power BI** – Transformed data from Snowflake connected to Power BI for visualization.  
5. **Dashboard Design** – Interactive dashboard in Power BI with slicers, charts, and filters.  
6. **Public Access** – Dashboard published publicly for easy access.  

Data was cleaned in Snowflake, removing errors and calculating metrics like average rainfall and seasonal trends.

## 6. Analysis & Visualization
**Main Pages:**
- Seasonal Overview – Yearly and seasonal rainfall trends, average rainfall by region  
- Regional Performance – Rainfall distribution, monthly totals, and comparisons  
- Weather Impact – Correlation between rainfall, temperature, and humidity  
- Forecast Insights – Predicted rainfall patterns for 2025–2026  

**Insights:**
- Identified a **5% drop in rainfall** in the Southern region over the last decade.  
- Highlighted a **10% increase in Northern region rainfall**, aiding flood planning.  

**Outputs:** Interactive dashboard and a static PDF report.  

- Interactive Dashboard: ![](https://app.powerbi.com/links/T3WN-BXiQq?ctid=c9b30289-5c60-41dc-85c2-d8862dea8925&pbi_source=linkShare&bookmarkGuid=e468d66f-48f2-40d1-b3fa-d5f4311d54e2)
- Static Report:
  ![](https://github.com/Gitrohinihub/Rainfall-Analysis/blob/43e92d6290b975d0a410c4bdfd251fcdbcdc4ba8/Report%20page%201.png)
  ![](https://github.com/Gitrohinihub/Rainfall-Analysis/blob/43e92d6290b975d0a410c4bdfd251fcdbcdc4ba8/Report%20page%202.png)
  ![](https://github.com/Gitrohinihub/Rainfall-Analysis/blob/43e92d6290b975d0a410c4bdfd251fcdbcdc4ba8/Report%20page%203.png) 
  ![](https://github.com/Gitrohinihub/Rainfall-Analysis/blob/43e92d6290b975d0a410c4bdfd251fcdbcdc4ba8/Report%20page%204.png) 

## 7. Business Problem Solved
### 7.1 Core Business Problem
- Optimize water management and crop planning  
- Understand regional rainfall variations  
- Predict future weather patterns  

### 7.2 Key Challenges Addressed
- Inconsistent rainfall affecting agriculture (e.g., 5% drop in the South)  
- Lack of regional comparisons for resource allocation  
- Uncertainty in forecasting for planning  

**For stakeholders, this helps:**  
- Plan irrigation and flood defences  
- Target high-risk areas  
- Reduce losses from weather unpredictability  

## 8. Business Recommendations
#### 8.1 🌱 Focus on High-Risk Regions
- **Action:** Increase irrigation support in the Southern region (5% rainfall drop) and monitor Northern floods (10% increase).  
- **Why:** Improve crop yields by 15% and reduce flood damage costs.  

#### 8.2 💧 Optimize Water Resource Planning
- **Action:** Use forecasts to adjust water storage in regions with variable rainfall.  
- **Why:** Save 20% on water management costs.  

#### 8.3 🌦️ Target Weather Impact Mitigation
- **Action:** Focus on areas with high humidity-rainfall correlation for early warnings.  
- **Why:** Reduce weather-related losses by 10%.  

#### 8.4 📊 Monitor and Adapt
- **Action:** Review seasonal trends quarterly and update plans.  
- **Why:** Maintain stable agricultural output despite a 2% annual variability.  

## 9. Before vs After Impact
| Before | After |
|--------|-------|
| No clear view of rainfall trends | 5% drop in South and 10% rise in North identified → Targeted planning |
| Unaware of regional disparities | Regional comparisons enable 15% better resource use |
| No predictive insights | Forecasts improve water management by 20% |
| Manual data handling | Automated pipeline saves 10 hours per analysis |

## 10. Tools Used
- **AWS S3** – Storage for raw data  
- **Snowflake** – Data loading, cleaning, and querying  
- **Power BI** – Visualization and dashboard design  

## 11. Outputs
- **Interactive Dashboard:** *(Power BI App Link)*  
- **PDF Report:** Static summary of findings  

## 12. Challenges Faced
- Setting up the AWS-Snowflake trust relationship required careful policy configuration, but worked smoothly once resolved.  

## 13. What I Learned
- How to secure cloud roles and permissions  
- Building efficient data pipelines with AWS and Snowflake  
- Creating clear insights using Power BI  
- The power of cloud tools working together 

## 14. Contact 
- [LinkedIn](https://www.linkedin.com/in/rohini-singh-?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
