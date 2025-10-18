# Apple GHG Emissions Analysis (2015-2022)

### Project Overview
Apple, one of the world’s largest technology companies, took a bold step in 2015 by announcing its goal to reduce its carbon footprint to Net Zero by 2030. This project focuses on understanding how Apple’s emissions have evolved across various operational areas and emission scopes, identifying key sectors that contribute to or influence the company’s carbon footprint over the reporting period.  


### Project Objective
Specifically, the analysis aims to:
1. Track changes in Apple’s total emissions from 2015 to 2022.
2. Compare emission reductions across Scope 1 (direct), Scope 2 (energy-related), and Scope 3 (supply chain and product use) categories.
3. Identify which operational areas have improved the most and which still need attention.


### Data Source
The dataset used is provided by Maven Analytics and offers a unique opportunity to assess Apple’s sustainability journey through the lens of data analytics. It contains emissions data, and growth data for the company. Also includes data to assess the emission per each product category. 

[Download Here](https://mavenanalytics.io/data-playground/apple-s-greenhouse-gas-emissions?page=3&pageSize=5)


### Tool(s)
Excel and Power BI were used for the analysis
- Excel for calculations.
- Power BI for visualisation and report building.

### Analytical Approach
The analysis followed a structured approach: 
1. Examined total GHG trends, while grouping them by their type, to see the progress in each group, i.e. Trend for gross carbon removal, trend for carbon-removal projects. This helps us track the level of progress across each group.
   
2. Compared actual emission trends against Apple’s 2030 target. To do this, the Compounding annual growth rate (CAGR) was carried out in a reverse manner on the gross emission cut target, and a linear growth analysis was carried out on carbon removal pledges. Then their corresponding values were compared against the actual value. 
CAGR is calculated using the formula:

CAGR = ( ((final value)/(Initial value))〗^((1⁄(number of years considered)) )-1) ------------------------------------ (1)

3. CAGR was also carried out on the normalisation factors to determine the impact of emission cuts on the growth of Apple.
   
4. An emission scope time-series analysis was carried out to determine which scope of emissions contributes significantly to Apple’s emissions, in accordance with the GHG Protocol.
   
5. Further analysis was carried out on the most significant business operations contributing to Apple’s emissions, and to determine what the trend is during the reporting period for these operations. 

#### Framework Alignment: 
Though not a full ESG report, this analysis aligns conceptually with the GHG Protocol for defining scopes 1-3.

### Results/Findings

This analysis revealed some interesting things, which are shown under this section of the report. 

1. Apple’s Overall Carbon Reduction Journey
Between 2015 and 2022, Apple reduced its total GHG emissions from 38.4 million to 20.2 million MtCO₂e, a 47% decrease over just seven years.
This indicates that Apple has already achieved more than 60% of its 2030 target in that period. Apple’s decarbonisation journey demonstrates how a global tech firm can expand production while reducing emissions. Despite increasing device output, expanding retail outlets, and rising customer demand, Apple continues to reduce its environmental impact, demonstrating that sustainability and growth can coexist.
Figure 1
<img width="975" height="495" alt="image" src="https://github.com/user-attachments/assets/0b2b83d8-ba5f-4afb-b7f3-a8c428b56af1" />


This represents a significant milestone for Apple; however, it’s important to note that while substantial progress has been made toward achieving the target for gross carbon removals, there is still considerable work to be done in meeting the goal for carbon emission mitigation through carbon removal projects. This is clearly reflected in the green trend line, which indicates minimal progress in that area so far.

2. Business Growth and Sustainability Alignment
Between 2015 and 2022, Apple’s performance data reflects an interesting intersection between business growth and sustainability commitments. While the company has made steady progress toward its carbon reduction goals, it has also achieved substantial financial and operational expansion.

Figure 2: Employee growth trend
<img width="829" height="572" alt="image" src="https://github.com/user-attachments/assets/f3103cd7-f911-49f0-8815-33b3dec60e89" />


Employee count increased by 49.09% (CAGR: 5.87%), suggesting workforce growth in areas such as research, product design, and renewable energy integration. Revenue rose by 68.72% (CAGR: 7.76%), while market capitalization grew by 329% (CAGR: 23.14%). This consistent upward trend suggests that the company’s sustainability strategy has not constrained financial performance; rather, it has likely coexisted with efficiency gains, supply-chain improvements, and stronger brand perception among climate-conscious consumers and investors.

 Figure 3: Revenue trend
<img width="798" height="574" alt="image" src="https://github.com/user-attachments/assets/f1925bc9-81be-4759-8c06-37e3c5f1d8b9" />

Figure 4: Market Capitalization trend
<img width="818" height="591" alt="image" src="https://github.com/user-attachments/assets/9f46fef6-0b7c-46ed-a173-112d16715a74" />

From an ESG perspective, these figures illustrate that environmental performance and business value can move in the same direction when sustainability is embedded into corporate strategy. The data points do not necessarily imply causation but highlight a positive correlation between emission-reduction efforts and broader value creation across the organisation.

 


3. Scope 3 Remains the Main Driver
Scope 3 emissions (indirect emissions from the supply chain, product use, and transport) account for over 95% of Apple’s total carbon footprint.
Manufacturing remains the single largest contributor, but has seen a sharp drop, showing progress in clean production. 
 
Figure 5: Emission Reduction Trends across Apple’s Value Chain
<img width="589" height="748" alt="image" src="https://github.com/user-attachments/assets/6f9ede18-bf0d-49cc-8cce-af0afa42a7bc" />


While manufacturing emissions have fallen, emissions from product transport and product use have stayed relatively stable. This suggests that while Apple’s factories are becoming greener, the life cycle emissions of products after they leave the factory still need attention. This opens up future strategies like sustainable product transport, longer device lifespans, and circular economy initiatives.


4. Analysis revealed that product-level emissions have not followed a consistent downward trend over the years. Despite corporate-level reductions in Apple’s total greenhouse gas emissions, the environmental intensity per product has fluctuated, with the iPhone X (2017) recording the highest footprint at 79 kg CO₂e. More recent models, such as the iPhone 13 (2021) and iPhone 14 (2023), show modest reductions but still reflect the persistent impact of production and material sourcing, as emissions per product are still greater than the iPhone 6s of 2015.
The data suggests that while operational and supply chain efficiency measures contribute to overall emission cuts, product design and material composition remain significant determinants of carbon output. 
