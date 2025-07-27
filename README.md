# 💳 Banking Transaction Analysis Dashboard in Power BI

This Power BI dashboard provides an analytical overview of **banking transaction data**, with insights into transaction performance, failure analysis, network bandwidth effects, and transaction types. The goal is to support business and network decision-making using transactional and technical KPIs.

## 📌 Objective

To provide a comprehensive and interactive Power BI dashboard that enables:
- Monitoring of transaction volume and value.
- Identifying patterns in transaction failures and successes.
- Evaluating network performance impact (6G Slice Bandwidth and Latency).
- Supporting fraud detection and failure mitigation strategies.
- Visualizing business activity and financial throughput.

---

## 📂 About the Dataset

This dataset consists of **1,000 synthetic banking transactions** with rich contextual and technical features designed for advanced analysis.

### Key Features:
- **Transaction ID**: Unique identifier for each transaction.
- **Sender/Receiver Account ID**: IDs involved in each transaction.
- **Transaction Amount**: Value in each transaction.
- **Transaction Type**: Transfer, Withdrawal, or Deposit.
- **Timestamp**: Date and time of the transaction.
- **Transaction Status**: Indicates success or failure.
- **Fraud Flag**: Binary flag showing possible fraud.
- **Geolocation**: Latitude and Longitude of transaction origin.
- **Device Used**: Mobile or Desktop.
- **Network Slice ID**: The 6G network slice used.
- **Latency (ms)**: Network delay experienced.
- **Slice Bandwidth (Mbps)**: Bandwidth available during the transaction.
- **PIN Code**: Masked 4-digit PIN for authentication.

---

## 📊 Dashboard Overview

This dashboard is composed of multiple visuals offering granular insight into the dataset. Each section is described below:

![image alt](https://github.com/Omensah-15/Bank_Transcaction_Insights/blob/6bc863c0e1f92735a44e8a807f3f56c00adab1be/Images/Image-1.png)

### 1. 🧩 Total Transaction Count by Network Slice ID
**Visual Type:** Pie Chart  
- **Slice1:** 323 transactions (32.3%)  
- **Slice2:** 340 transactions (34%)  
- **Slice3:** 337 transactions (33.7%)  
- **Insight:** Transactions are fairly evenly distributed across the three network slices. Helps identify if any network slice is over- or under-utilized.

![image alt](https://github.com/Omensah-15/Bank_Transcaction_Insights/blob/b3b51ef72cd85d63dfe5216f303eb437e42db8ca/Images/Image_1.png)
---

### 2. 📶 Impact of Bandwidth on Success Rate (%)
**Visual Type:** Bar Chart  
- **X-axis:** Slice Bandwidth (50–250 Mbps)  
- **Y-axis:** Success Rate (%)  
- **Insight:** Success rates vary significantly with bandwidth. Higher bandwidth generally correlates with improved success, highlighting the importance of network capacity on transaction reliability.

![image alt](https://github.com/Omensah-15/Bank_Transcaction_Insights/blob/3adcb73eb1e390f5ebfd249089e59efe8fcb61d4/Images/Image_2.png)
---

### 3. ⏱️ Failed Transactions by Latency (ms)
**Visual Type:** Scatter Plot  
- **X-axis:** Latency (ms)  
- **Y-axis:** Number of Failed Transactions  
- **Insight:** Failed transactions increase noticeably at higher latency values (>15ms). Latency optimization can reduce transaction failures.

![image alt](https://github.com/Omensah-15/Bank_Transcaction_Insights/blob/3adcb73eb1e390f5ebfd249089e59efe8fcb61d4/Images/Image_2.png)
---

### 4. ✅❌ Failed vs Successful Transactions
**Visual Type:** Donut Chart  
- **Success Transactions:** 513 (51.3%)  
- **Failed Transactions:** 487 (48.7%)  
- **Insight:** A nearly even split between successful and failed transactions signals potential process or system bottlenecks needing resolution.

![image alt](https://github.com/Omensah-15/Bank_Transcaction_Insights/blob/3adcb73eb1e390f5ebfd249089e59efe8fcb61d4/Images/Image_2.png)
---

### 5. 📈 Total Transaction Over Time
**Visual Type:** Line Chart  
- **Y-axis:** Sum of Transaction Amount  
- **Time Range:** 10:00 AM to 11:00 AM  
- **Insight:** Transaction volume fluctuates during the hour, with peaks around 10:20 AM and 10:55 AM. This can be useful for identifying high-demand periods.

![image alt](https://github.com/Omensah-15/Bank_Transcaction_Insights/blob/3adcb73eb1e390f5ebfd249089e59efe8fcb61d4/Images/Image_2.png)
---

### 6. 🔁 Failure Rate by Transaction Type
**Visual Type:** Bar Chart  
- **Deposit Failures:** ~165  
- **Transfer Failures:** ~180  
- **Withdrawal Failures:** ~165  
- **Insight:** Transfers have the highest failure rate. Additional focus should be placed on investigating the causes (e.g., network, user error, fraud).

![image alt](https://github.com/Omensah-15/Bank_Transcaction_Insights/blob/3adcb73eb1e390f5ebfd249089e59efe8fcb61d4/Images/Image_2.png)
---

### 7. 💰 Total Transaction Value
**Visual Type:** Card  
- **Value:** **771.17K**  
- **Insight:** The dashboard summarizes the overall financial impact, helping business stakeholders understand total transaction throughput.

![image alt](https://github.com/Omensah-15/Bank_Transcaction_Insights/blob/3adcb73eb1e390f5ebfd249089e59efe8fcb61d4/Images/Image_2.png)
---


## 🛠️ Tools Used

- **Power BI**: Interactive dashboard and data visualization

---
## 👨‍💻 Author

**Obed Mensah**  
*Data Scientist — Python | Power BI | SQL | Analytics*  
📧 [heavenzlebron7@gmail.com](mailto:heavenzlebron7@gmail.com)
