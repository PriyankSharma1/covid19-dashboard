# Covid-19 Dashboard

This project contains a Power BI dashboard that provides insightful visualizations and analysis of the Covid-19 pandemic. The dashboard is designed to present key metrics and trends using interactive visual elements.

## 📊 Dashboard Overview
- **Data Visualizations:** Track confirmed cases, recoveries, and fatalities.
- **Comparative Analysis:** Evaluate country-wise and region-wise trends.
- **Trend Analysis:** Visualize case growth, recovery rates, and mortality rates.
- **Interactive Filters:** Allow users to customize views by date, region, or specific metrics.

## 🛠️ Dashboard Structure
The dashboard consists of 4 pages:

1. **Title Page:**
    - A landing page with navigation links to view the **World Outbreak** or **India Outbreak** pages.
2. **Introduction Page:**
    - Brief overview explaining Covid-19, how it spread, and how it became a pandemic.
3. **World Outbreak Page:**
    - Visualizes global Covid-19 data using an interactive map with tooltips that show the country name, total deaths, confirmed cases, and incidence per 100k population.
    - Card visualizations display total affected, total deaths, and total recoveries with rotating titles.
    - A slicer is available to filter data by specific regions or countries.
    - A table presents detailed country-wise confirmed cases.
4. **India Outbreak Page:**
    - Similar visualizations as the World Outbreak page but with additional filters for country-specific data.
    - Highly interactive — selecting one visualization will dynamically update the others.

## 🔎 Additional Features
- **Bookmarks and Navigation:**
    - Home page icon on the header.
    - Back and front page navigation buttons.
    - Refresh date display.
    - Custom interactive buttons for easy navigation.
- **Measures:**
    - Created various DAX measures to perform calculations for key visualizations.
    - Measures include total cases, total deaths, recovery rates, incidence per 100k, and mortality rates.
    - Dynamic measures to support interactivity and filtering.

## ⚙️ Data Preparation
The following steps were taken to prepare the data:
1. **Data Download:**
    - Downloaded raw Covid-19 data from a public repository as a CSV file.
2. **Data Cleaning:**
    - Promoted headers.
    - Changed column data types and renamed columns.
3. **Custom Column:**
    - Added a custom column to calculate the population for each country.

## 🚀 Getting Started
Follow these steps to view and explore the dashboard:

1. **Download the Dashboard:**
    - Download the `Covid Dashboard.pbix` file from this repository.
2. **Install Power BI Desktop:**
    - Ensure you have [Power BI Desktop](https://powerbi.microsoft.com/downloads/) installed.
3. **Open the File:**
    - Launch Power BI Desktop and open the `.pbix` file.

## 📦 Data Source
- The data used for this dashboard is sourced from [reliable public datasets](https://ourworldindata.org/coronavirus).
- Any data transformations and calculations were performed using Power BI’s built-in tools.

## 📸 Screenshots
![image](https://github.com/user-attachments/assets/d2866ba4-cad0-453f-9a99-2a87c4024bf5)
![image](https://github.com/user-attachments/assets/16dbfe51-2a6c-472b-b062-ecc439cd5acd)
![image](https://github.com/user-attachments/assets/1bc47df2-c23c-48ce-a182-f8e9bab1f248)
![image](https://github.com/user-attachments/assets/ff4ad946-35ff-4455-ac10-d297b6be1872)

## 📝 Insights
- Highlighted the countries with the highest number of confirmed cases and fatalities.
- Identified trends in recovery rates across regions.
- Visualized the impact of Covid-19 over time using time-series charts.

## ⚖️ License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing
Contributions are welcome! If you have suggestions for improvements, feel free to create a pull request.

## 📬 Contact
For any questions or feedback, please reach out via GitHub or LinkedIn.

---

**Make sure to star ⭐ this repository if you find it helpful!**

