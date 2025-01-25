

# Zomato Dashboard - City and User Insights

This Power BI dashboard provides an in-depth analysis of Zomato's performance metrics, focusing on city-level sales, user activity, and overall trends. Key features include interactive visuals for city-wise performance, user demographics, and yearly sales patterns. The dashboard is designed to help stakeholders make data-driven decisions with intuitive filters and insightful charts.

## Visualised File
  - <a href="https://drive.google.com/file/d/1akqCF9KR3Vlh6Fg1a78k99Y_zELzDXg9/view?usp=drive_link"> Visualisation File </a> 

### 1. **Index Page**
   - A visually appealing landing page with Zomato branding, setting the theme for the dashboard.

### 2. **Overview**
   - Snapshot of overall performance metrics, including:
     - Total Sales Amount
     - Quantity Sold
     - Customer Ratings
     - Total Orders
   - Segregated insights for Non-Veg, Veg, and Other Sales categories.
   - Yearly sales trends visualized in a line chart.

### 3. **User Performance**
   - Overview of active users and total user count.
   - Gender-wise analysis of user gains and losses.
   - Age group distribution of users.

### 4. **City Performance**
   - City-wise breakdown of sales, orders, and user metrics.
   - Key charts showing:
     - Sales Value by City
     - Rating Counts by City
     - Active Users by City
   - Highlights the top-performing cities for Zomato.

### 5. **Interactive Filters**
   - Toggle between Amount and Quantity metrics for granular analysis.
   - Dynamic filtering for Top 5, Top 10, and other city segments.

## Tools and Technologies

- **Power BI**: For creating interactive and visually rich dashboards.
- **Data Sources**: Data preparation and modeling within Power BI to structure insights effectively.

## Screenshots
![Index Dashboard](https://github.com/ridumjeetsingh/Data-Analysis-Zomato-Project/blob/main/Index%20Screenshot.png)
![Overview Dashboard](https://github.com/ridumjeetsingh/Data-Analysis-Zomato-Project/blob/main/Overview_Screenshot.png)
![User Dashboard](https://github.com/ridumjeetsingh/Data-Analysis-Zomato-Project/blob/main/User_Performance%20Screenshot.png)
![CityDashboard](https://github.com/ridumjeetsingh/Data-Analysis-Zomato-Project/blob/main/City%20Performance%20Screenshot.png)

### **Challenges Faced During the Project**

1. **Creating Relationships and Measures for Key Insights**  
   While working on the Zomato dashboard, I encountered difficulties in establishing relationships between distinct tables, such as **orders** and **restaurants**. This challenge became particularly evident when merging the tables to create new measures, such as calculating the **rating count for each restaurant**. Integrating this information into the dashboard as part of the main KPIs also required thoughtful data modeling and iterative testing to ensure accuracy.

2. **Dynamic Table Titles and Advanced Measures**  
   A significant challenge was building **dynamic table titles** that responded to slicers, such as switching between **Top 5, Top 10, Top 50, and All** data views. Additionally, crafting advanced DAX measures that incorporated multiple `IF` condition statements demanded a deep understanding of DAX logic and thorough debugging to achieve the desired outcomes.

3. **Interactive Features with Bookmarks**  
   Implementing interactive features, such as **hiding filters** using bookmarks and adding **action-driven icons or dropdown buttons**, was particularly challenging. This required mastering bookmark functionality and synchronizing it with visuals and user actions to ensure seamless interaction. Achieving a polished and user-friendly design involved multiple iterations and testing.

## Getting Started
1. Clone the repository.
2. Open the Power BI (.pbix) file to explore or modify the dashboard.
3. Ensure you have the required data source for live updates.

## Contributing
Contributions are welcome! Feel free to fork the repository and create a pull request.

#Feel free to adjust the content or provide additional information, and I can refine it further!
