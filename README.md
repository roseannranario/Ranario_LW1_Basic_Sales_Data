# Ranario_LW1_Basic_Sales_Data
PART 1: Launching Power BI & Loading Data
Open Power BI    
<img width="507" height="293" alt="image" src="https://github.com/user-attachments/assets/f041a7b4-913e-4327-ae20-1d23fd5eec6e" />

Home tab
<img width="633" height="335" alt="image" src="https://github.com/user-attachments/assets/f6ce631a-e253-4993-8a2f-fd9462530786" />

Get Data
<img width="499" height="399" alt="image" src="https://github.com/user-attachments/assets/8979f6d2-0891-4161-89b0-085fbb6c7de2" />

Select Text/CSV
<img width="512" height="392" alt="image" src="https://github.com/user-attachments/assets/29e17597-84b3-414d-8d48-312541af5c9a" />

Download Data.csv
<img width="622" height="453" alt="image" src="https://github.com/user-attachments/assets/d312d6e4-54f9-4a28-9fba-2a471399b0d7" />

Browse and select:
Week1_Basic_Sales_Data.csv
<img width="627" height="354" alt="image" src="https://github.com/user-attachments/assets/c52d4bbb-04ef-406a-9f19-3984e0b4d02c" />

Load
<img width="601" height="404" alt="image" src="https://github.com/user-attachments/assets/9aca9376-befd-4a40-9524-67d43fdfec1b" />

Data View icon
<img width="541" height="399" alt="image" src="https://github.com/user-attachments/assets/cacd37f7-2ecf-4a6c-8c86-c65c75f8d491" />

PART 1 Step-3 Questions 
1.Are all columns visible? 
  - Yes, it is visible.
2 Is “Date” formatted as Date? 
  - Yes, the name and data type are the same.
3 Is “Sales” formatted as Decimal Number? 
  - No,but I already change it into decimal number.
    
Column Tools
<img width="649" height="517" alt="image" src="https://github.com/user-attachments/assets/db7244ca-9308-4818-89ce-d9fbb56bcc36" />

Date → Date
<img width="626" height="184" alt="image" src="https://github.com/user-attachments/assets/04527990-e045-4ebb-9233-7c3634e9f13f" />

Sales → Decimal Number
<img width="625" height="171" alt="image" src="https://github.com/user-attachments/assets/7c05d45e-d67d-49ad-9f25-2eb863bc8d4a" />

Product/Category/Region → Text
<img width="624" height="127" alt="image" src="https://github.com/user-attachments/assets/d8626bb2-2abc-4fc5-b9e6-dc5953d3895f" />
<img width="625" height="195" alt="image" src="https://github.com/user-attachments/assets/fb09e6f9-3bb5-41d7-b76e-46e07a75a91c" />
<img width="625" height="185" alt="image" src="https://github.com/user-attachments/assets/8916b8e1-2221-41ce-8e55-455f67256a5c" />

PART 2: Exploring the Interface
Report View
<img width="623" height="211" alt="image" src="https://github.com/user-attachments/assets/7d1fe3ef-fb56-406d-87be-c136d706a8f6" />

Data View
<img width="246" height="194" alt="image" src="https://github.com/user-attachments/assets/1ab7b11e-b851-4dc5-8a9e-355a6fa5f747" />

Model View
<img width="545" height="274" alt="image" src="https://github.com/user-attachments/assets/557149ae-3323-45a3-bc6a-1765645ad1b8" />

PART 3: Creating Auto-Generated Visuals

Power BI automatically creates a visual
<img width="226" height="227" alt="image" src="https://github.com/user-attachments/assets/60408462-9723-49aa-8cb3-826aa9df34b4" />

PART 3 Step 1 Questions
1.What type of chart was created?
 - Clustered column chart
2 What does it show?
 - it shows sum of sales

Step 2: Create a Sales by Region Chart
<img width="291" height="293" alt="image" src="https://github.com/user-attachments/assets/a1ef162f-9b49-41a1-bba3-b5a785675fdd" />
Question & Answer:
● Which region has the highest sales?
  Answer : the west region have 60 k sales

Step 3: Sales by Category
<img width="328" height="329" alt="image" src="https://github.com/user-attachments/assets/f4654833-b5ad-475b-91df-5299438f1ba9" />
Question & Answer:
● Which category dominates?
    Answer: Electronics dominates with 90K in sales (40.8% of total)
● Is the distribution balanced?
   Answer:  No, the distribution is not balanced. Electronics holds the largest share at ~41%, followed by Furniture at ~39%, while Office Supplies trails significantly at
   ~20%. Electronics and Furniture are fairly close to each other, but Office Supplies is notably underrepresented compared to the other two.

Step 4: Sales Over Time
<img width="297" height="299" alt="image" src="https://github.com/user-attachments/assets/08251597-8648-47ee-93f4-4e327dea7c8a" />
Question & Answer:
● Is there growth?
   Answer: No sales actually declined 
                  significantly from 2024 to 2025, dropping 
                  from approximately 0.2M down to 
                  near 0.0M.
● Any noticeable trend?
    Answer:  Yes, there is a sharp and consistent downward trend. The steep decline suggests either a major drop in business activity, incomplete 2025 data (e.g., only  
             partial year recorded), or a significant loss of customers/revenue. It would be worth investigating whether the 2025 data is complete, as a partial year would               naturally show lower totals compared to a full year of 2024 data.



PART 4: Basic Data Insight Interpretation
Question:
● Which region contributes the most revenue?
   - The West region contributes the most revenue at approximately 60K, followed closely by East (~59K) and South (~57K). The North region lags   
     behind at roughly 46K, noticeably lower than the other three.
● Which product category performs best?
   - Electronics performs best at 90K (40.8%), followed by Furniture at 86K (39.19%), and Office Supplies trailing at 44K (19.99%). Electronics and 
     Furniture are strong and competitive, while Office Supplies significantly underperforms.
● Are sales consistent across dates?
   - No, sales are not consistent. There is a steep decline from ~0.2M in 2024 to near 0.0M in 2025. This is a major red flag — likely caused by incomplete 2025 data,  
     seasonal patterns, or a genuine business downturn.

● What business recommendation can you suggest?
    1. Investigate the 2025 sales drop immediately. If it's incomplete data, normalize comparisons by time period. If it's a real decline, identify root causes — lost   
       clients, market shifts, or operational issues.
    2. Focus on the North region. It underperforms all other regions by a significant margin. Consider targeted marketing campaigns, new partnerships, or sales incentives  
       specific to that region.
    3. Grow Office Supplies. At only 20% of revenue, it's either undermarketed or underpriced. Bundling it with Electronics or Furniture could boost its contribution.
    4. Protect the West region lead. Since West is the top performer, ensure customer retention strategies are in place there to maintain that advantage.

 
 LABORATORY QUESTIONS
 Part A – Technical Questions
 1. What are the five columns in the dataset?
    -  The five columns are:
       Category
       Date
       Product
       Region
       Sales
 2. What data type is assigned to the “Sales” column?
    - The Σ (Sigma) symbol next to Sales confirms it is a Numeric/Whole Number data type — Power BI automatically treats         it as a summable measure.
 3. Which Power BI view allows you to see raw data?
    - The Data View (Table View) allows you to see the raw data.
 4. What chart type is best for showing trends over time?
    - A Line Chart is best for showing trends over time.
 5. What aggregation is automatically applied to Sales?
    - Sum is automatically applied, as indicated by the Σ symbol beside the Sales column in the field list.

Part B – Analytical Questions
6. Which region has the highest total sales?
   - The West region has the highest total sales at approximately ~60K, based on the bar chart showing Sum of Sales by Region.
7. Which category has the lowest performance?
   - Office Supplies has the lowest performance at 44K (19.99%), significantly behind Electronics (90K) and Furniture (86K) as shown in the pie chart.
8. Are sales increasing, decreasing, or stable?
   - Sales are decreasing. The line chart shows a sharp downward trend from approximately 0.2M in 2024 to near 0.0M in 2025, indicating a significant decline in revenue   
     over time.
9. If you were a manager, which region would you prioritize?
   -  I would prioritize the North region because it has the lowest sales (~46K) compared to all other regions. As a manager, I would investigate why North is 
      underperforming and implement targeted strategies such as increased marketing efforts, sales incentives, or new customer acquisition programs to bring it in line with
      the other regions.

10. Provide one actionable recommendation based on the data.
   - Launch a recovery and growth plan for the North region while investigating the 2025 sales decline. Since North consistently underperforms and overall sales are   
     dropping sharply into 2025, management should conduct a root cause analysis — identifying whether the drop is due to lost clients, poor product-market fit, or data 
     gaps. Simultaneously, reallocating some budget from stronger regions to boost North's performance could help balance revenue distribution across all regions.

ENHANCEMENT SECTION










  



