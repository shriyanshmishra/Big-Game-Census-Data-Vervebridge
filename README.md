## **Big Game Census Data Visualization**

### **Project Description**  
This project analyzes the birthplace distribution of Super Bowl players using data from the U.S. Census Bureau and player information from Yahoo Sports. The primary goal is to visualize this data using Power BI, exploring insights such as which states contribute the most players to the NFL relative to their population size. The project includes data cleaning, preparation in Python (Google Colab), and building an interactive dashboard in Power BI.

### **Objective**  
- To create an interactive Power BI dashboard to visualize Super Bowl player birthplaces.
- To compare player count by state to population estimates.
- To identify patterns and fun facts about player distribution across states and their corresponding populations.

### **Technologies Used**  
- **Google Colab:** For data cleaning and preprocessing.
- **Python (Pandas, NumPy):** For merging datasets, cleaning data, and preparing it for visualization.
- **Power BI:** To create interactive data visualizations and dashboards.
- **Data Sources:**  
  1. **All Places Census 2016 Population Estimates**  
  2. **All States Census 2017 Population Estimates**  
  3. **Big Game Census Data**  

### **Steps Followed**  
1. **Data Collection & Preparation:**  
   - Collected datasets from the U.S. Census Bureau and Yahoo Sports.
   - Merged and cleaned the data using Google Colab to ensure compatibility between the population and player data.
   
2. **Data Cleaning in Google Colab:**  
   - Merged datasets based on player birthplace.
   - Removed missing values and blank entries.
   - Grouped the data by state and calculated the total number of players per state.
   - Added population estimates from the census data.

3. **Dashboard Creation in Power BI:**  
   - Imported the cleaned dataset into Power BI.
   - Created visualizations including a map showing player distribution by state and bar charts comparing player counts to state populations.

### **Key Takeaways**  
- The dashboard clearly highlights which states produce the most NFL players relative to their population.
- Insights like population-to-player ratio were derived, showing which states are more "player-rich" compared to others.

### **Project Difficulties**  
- Merging datasets with inconsistent geographical identifiers.
- Handling missing or incomplete data in certain columns.

### **Future Improvements**  
- Expand the dataset to include more recent Super Bowl player data.
- Add more detailed insights into individual cities and colleges.
- Incorporate additional player metrics, such as performance statistics or draft history.


### **How to Run This Project**  
1. Clone the repository.
2. Run the data cleaning notebook in Google Colab.
3. Use the exported CSV file to build your own Power BI dashboard or import it into any visualization tool of your choice.
