# GDP-analysis

Gross Domestic Product (GDP) is a measure of the size and health of an economy. It represents the total value of all goods and services produced within a country over a specific period of time, usually a year. GDP is considered a key indicator of a country's economic performance and is used to compare the economic output of different countries.

This project explores the analysis of global GDP data to provide an in-depth understanding of economic performance across various countries. The objective is to analyze growth patterns, make comparisons, and identify trends using interactive graphs and statistical tools. The analysis is divided into multiple structured steps:

---

## 📁 Dataset

The dataset includes GDP information for 56 countries over a range of years from 1960 to 2016. This data will be used to:
- Understand GDP growth for individual countries
- Compare GDP across countries
- Generate relevant visualizations to explore and demonstrate economic trends

---

## 🔍 Project Breakdown

### 1. Dataset Walkthrough

This step involves examining and understanding the dataset’s structure, including the variables, data types, and missing values. A dataset walkthrough is crucial to:
- Understand what data is available
- Identify any inconsistencies or missing entries
- Prepare the data for analysis and visualization

---

### 2. GDP Growth of a Country

GDP growth refers to the percentage increase in GDP from one year to the next. This step includes:
- Calculating annual GDP growth using the formula:

  \[
  \text{GDP Growth (\%)} = \left(\frac{\text{Current Year GDP} - \text{Previous Year GDP}}{\text{Previous Year GDP}}\right) \times 100
  \]

- Applying this formula for each year (excluding the first) for a specific country
- Adding the growth values as a new column to the dataset

---

### 3. GDP Growth on Whole Dataset

This step extends the GDP growth calculation to all 56 countries. It includes:
- Iterating over each country and computing yearly GDP growth
- Creating a new column to store these values
- Handling missing values or years without data
- Merging the results back into the original dataset

---

### 4. Plotting Graphs Using Plotly

Interactive visualizations are created using Plotly to analyze GDP data dynamically:
- Line graphs for individual countries showing year-wise GDP or GDP growth
- Features such as tooltips and zooming for better interactivity
- Saving each graph as an offline `.html` file to allow sharing and reviewing without running code

---

### 5. Plotting Graphs in Bulk

To simplify analysis across all countries:
- A script iterates through each country
- Automatically generates GDP graphs using Plotly
- Saves them as separate `.html` files in a dedicated output directory
- Makes large-scale analysis efficient and manageable

---

### 6. Compare GDP Across Countries

This step focuses on comparing the GDP growth of two or more countries:
- Filters the dataset to include only the selected countries
- Plots interactive line graphs to visualize GDP over time
- Includes customization such as titles, labels, and legends
- Enables meaningful comparisons between economies

---

### 7. Compare GDP Across Countries - Advanced

This is an enhanced version of the comparison step:
- Allows comparison between any number of countries
- Uses loops and reusable functions to automate the generation of multi-country comparison graphs
- Helps identify broader economic trends across regions or continents

---

### 8. GDP Growth Comparison - Automation

The final step automates GDP growth comparison for all countries:
- Handles missing data by excluding countries with multiple consecutive missing years
- Generates interactive line graphs for each country showing GDP growth over time
- Saves each graph as an HTML file for easy review
- Allows comprehensive and automated trend analysis

---

## 🛠️ Technologies Used

- **Python** (Data analysis and scripting)
- **Pandas** (Data manipulation)
- **Plotly** (Interactive graphing and visualizations)
- **OS** (File and directory handling)
