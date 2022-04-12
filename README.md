# PSM(Procurement and Supply Management) Assessment

The project is to solve a common issue for business with fair amount of physical assets especially when they are associated with frequent movement. Given the exact coordinates of current vendors / customers as well as their supply & demand QTY, in where should I open a new warehouse or how many  warehouses to decrease shipping cost and lead time, which in return bring more customer satisfaction.

Please note the script serve as a fundamental illustration of how this issue could be solved,  more complex metrics may be used to generate a result that align with your goal.

Step 1: Data Preparation – merge to one geodataframe for our analysis

Step 2: Data Understanding – find the optimal QTY of new warehouses to build using Elbow Method

Step 3: Data Mining – locate nearest centroid(s) using Weighted K Means Clustering

Step 4: Data Visualization – plot data points in a heat map with centroid(s) highlighted

Step 5: Make Recommendations – output physical addresses for new warehouse(s) using reverse geocoding
