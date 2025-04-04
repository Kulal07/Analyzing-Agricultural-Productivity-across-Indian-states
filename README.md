# 📊 Analyzing Agricultural Productivity Across Indian States - Power BI Dashboard

## 🧭 Project Overview

This Power BI project provides a **data-driven visualization and analysis of agricultural productivity** across Indian states. It leverages key agronomic and environmental factors such as rainfall, fertilizer usage, and cropping patterns to uncover productivity trends and support effective agricultural planning and policy-making.

## 🔍 Objectives

- Visualize **state-wise agricultural performance** for various crops and years.
- Analyze the **impact of rainfall, fertilizers, and pesticide usage** on crop productivity.
- Identify **seasonal trends and regional disparities** in crop cultivation.
- Enable **interactive exploration** of crop yield and related factors through dashboards.

## 📂 Dataset Description

Each record in the dataset represents a unique crop grown in a particular season, state, and year, along with relevant agronomic and environmental data.

### 🧾 Column Descriptions

| Column Name       | Description                                                                    |
| ----------------- | ------------------------------------------------------------------------------ |
| `Crop`            | The name of the crop cultivated (e.g., Rice, Wheat, Maize).                    |
| `Crop_Year`       | The year in which the crop was grown.                                          |
| `Season`          | The specific cropping season (e.g., Kharif, Rabi, Whole Year).                 |
| `State`           | The Indian state where the crop was cultivated.                                |
| `Area`            | The total land area (in hectares) under cultivation.                           |
| `Production`      | The quantity of crop production (in metric tons).                              |
| `Annual_Rainfall` | The annual rainfall received in the crop-growing region (in millimeters).      |
| `Fertilizer`      | The total amount of fertilizer used (in kilograms).                            |
| `Pesticide`       | The total amount of pesticide used (in kilograms).                             |
| `Yield`           | The calculated crop yield (Production ÷ Area), i.e., productivity per hectare. |


## 🛠️ Tools & Technologies Used

- **Power BI Desktop** – for data modeling and dashboard creation
- **Power Query Editor** – for data cleaning and transformation
- **DAX (Data Analysis Expressions)** – for calculated fields and custom metrics
- **Microsoft Excel** – for initial dataset formatting and validation

## 📈 Dashboard Features

- 🗺️ **State-wise Crop Yield Map**: View geospatial distribution of yield across states.
- 📅 **Seasonal Trends**: Track how crop yield and inputs vary across Kharif, Rabi, and Whole Year.
- 🌧️ **Rainfall vs Yield Correlation**: Understand how rainfall impacts productivity.
- 🧪 **Fertilizer and Pesticide Impact Analysis**: See input-output efficiency across crops.
- 📊 **Crop-Wise Productivity Trends**: Compare productivity for different crops over the years.
- 🔍 **Interactive Filters**: Slice data by State, Crop, Year, Season, and more.

## 🚀 Getting Started

1. Clone or download this repository.
2. Open the `.pbix` file using Power BI Desktop.
3. Explore the visualizations using the built-in slicers and filters.
4. Analyze data interactively to discover insights.

## 🧠 Key Insights (Example)

- Wheat shows higher productivity in northern states during Rabi.
- States with consistent rainfall and moderate pesticide usage report better average yields.
- Fertilizer use doesn’t always correlate with high productivity – pointing toward optimization needs.

## 📌 Possible Enhancements

- Integrate **real-time weather API data** for forecasting.
- Add **district-level data granularity**.
- Implement **predictive analytics** to estimate future crop yields.
- Publish the report to Power BI Service for web access and sharing.

## 🤝 Contributing

Want to improve the report or add new datasets?\
Feel free to fork the repo, raise a pull request, or suggest enhancements via Issues!

## 📬 Contact

📧 Rohan Y S\
[rohankulal04@gmail.com](mailto\:rohankulal04@gmail.com)

