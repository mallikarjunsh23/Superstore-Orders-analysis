# Superstore-Orders-analysis

### Project Overview

This data analysis project aims to provide deep insights into sales performance and regional trends with time using the 
Superstore Orders dataset. By analysing transactional data across various segments, region, category and sub-category the
project identifies the highest revenue products, highest selling regions and growth comparison in profit year by year.
The goal is to uncover comparison sales and profit by region, category, year and month.

### Dataset used 
This dataset was originally downloaded from Kaggle. Unfortunately, I no longer have the exact link. so that uploaded the 
file.

### Tools

- Python-data analysis and  data creating
- MySQL-data manipulating
- PowerBi-data visualisation

### Exploratory Data analysis

- What are the top 10 highest revenue-generating products?
- What are the top 5 highest selling products in each region?
- Find the month over month growth comparison(2022 vs 2023)?
- Find the highest sales month for each category?
- find the sub-category with highest profit growth in 2023 vs 2022?

### Process

- Verify data for missing values adjusted column names and data types.
- Created the calculation column for further analysis and find answer for objectives.
- Explore the data to MySQL and find the answer for the objects.
- Create dashboard for result in PowerBi.

### Results/Findings
- top 10 highest revenue-generating products
  - TEC-CO-10004722
  - OFF-BI-10003527
  - TEC-MA-10002412
  - FUR-CH-10002024
  - OFF-BI-10001359
  - OFF-BI-10000545
  - TEC-CO-10001449
  - TEC-MA-10001127
  - OFF-BI-10004995
  - OFF-SU-10000151
- top 5 highest selling products in each region
  - Central	OFF-BI-10000301	
  - Central	OFF-BI-10000756	
  - Central	OFF-BI-10000546	
  - Central	OFF-BI-10001249	
  - Central	FUR-CH-10002304	
  - East	OFF-PA-10001970	
  - East	OFF-BI-10003656	
  - East	FUR-FU-10004848	
  - East	OFF-FA-10000621	
  - East	OFF-FA-10002780	
  - South	OFF-ST-10003716	
  - South	OFF-BI-10004728	
  - South	FUR-CH-10000513	
  - South	OFF-BI-10000014	
  - South	FUR-FU-10001731	
  - West	TEC-AC-10003832	
  - West	OFF-BI-10000174	
  - West	OFF-BI-10001036	
  - West	OFF-BI-10001670	
  - West	OFF-ST-10002486	 
- month over month growth comparison
    om	2022_sales	2023_sales
  -	1	   94712.5	   88632.6
  -	2	   90091.0	   128124.2
  -	3	   80106.0	   82512.3
  -	4	   95451.6	   111568.6
  -  5	   79448.3	   86447.9
  -  6	   94170.5	   68976.5
  -	7	   78652.2	   90563.8
  -	8	   104808.0	   87733.6
  -	9	   79142.2	   76658.6
  -	10	 118912.7	   121061.5
  -	11	 84225.3	   75432.8
  - 12	 95869.9	   102556.1
- Highest sales month for each category
    category	      ym	 sales	
   -Furniture	       8	 71649.5	
   -Office Supplies	 2	 77959.5	
   -Technology	      10	 103021.1	
- Sub-Category with highest profit growth in 2023 vs 2022
  sub_category	2022_profit	2023_profit	(2023_profit-2022_profit)*100/2022_profit
 -	 Machines	     7243.2	      10878.5	    50.189143
 -	 Supplies	     1500.7	       1937.4	    29.099753
 -	 Binders	     8685.5	      10523.1	    21.157101
 -	 Storage	     8907.4	      10630.6	    19.345713
 -	 Phones	      13024.7	      15343.6	    17.803865
 -	 Accessories	 7387.2	       8057.4	     9.072450
 -	 Envelopes	    607.2	        640.0	     5.401845
 -	 Chairs	      14725.3	      15089.8	     2.475332
 -	 Art	          924.1	        935.7	     1.255275
 -	 Paper	       3058.9	       2942.4	    -3.808559
 -  Bookcases	   5459.5	       5036.6	    -7.746131
 -  Labels	        349.6	        295.3	    -15.532037
 -  Tables	      10315.9	       8275.3	    -19.781115
 -  urnishings	   4236.2	       3342.1	    -21.106180
 -  Copiers	     8780.3	       5718.6	    -34.870107
 -  ppliances	   6374.4	       3893.3	    -38.922879
 -  Fasteners	     40.1	          8.8	    -78.054863

### Final Conclusion

To make smart business decisions, focus on the top 10 products that bring the most revenue. Each region has its own top 5 best-selling products, which can guide regional marketing. Sales grew and drop month by month from 2022 to 2023, showing overall positive and negative trends. Different product categories had peak sales in different months, which helps in planning promotions. The sub-category with the highest profit growth in 2023 should be prioritized for investment and scaling, loss in 2023 should be stop selling that sub category products.






