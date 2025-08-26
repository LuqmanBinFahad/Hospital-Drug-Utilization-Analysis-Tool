# Hospital Drug Utilization Analysis Tool

A comprehensive, interactive framework for hospital pharmaceutical cost management and utilization analysis. This tool enables hospitals, clinics, and healthcare administrators to collect, analyze, and visualize drug utilization data to optimize pharmaceutical expenditures and support data-driven decision making.

## Features

- **Data Collection & Preparation**  
  Clearly outlines required data points for a robust drug utilization analysis, including drug identification, transaction data, financial data, patient information, and prescriber data.
- **Analysis & Calculation**  
  Automates cost calculations and ABC analysis to categorize drug classes by cost impact and utilization patterns.
- **Reporting & Visualization**  
  Interactive dashboards and charts (powered by Chart.js) for cost distribution, ABC classification, and utilization patterns.
- **Sample Results & Summary Cards**  
  Ready-to-use sample tables and cards for quick insights into pharmaceutical expenditures and class breakdowns.

## How It Works

### 1. Data Collection & Preparation

- Gather drug dispensing, cost, and patient data from hospital systems.
- Standardize drug names and map each to the ATC (Anatomical Therapeutic Chemical) classification.
- Aggregate data to summarize costs and usage by drug class.

### 2. Analysis & Calculation

- For each ATC drug class, the tool calculates total cost, cost percentage, average unit cost, and utilization volume.
- Implements ABC analysis (Pareto principle) to classify drugs:
  - **Class A:** Top 20% of classes, ~80% of costs (high priority management).
  - **Class B:** Next 30% of classes, ~15% of costs (moderate oversight).
  - **Class C:** Remaining 50% of classes, ~5% of costs (routine monitoring).
- Utilization patterns are identified (e.g., high-cost/low-volume).

### 3. Reporting & Visualization

- **Drug Class Cost Distribution:** Pie chart visualizing expenditure across major drug classes.
- **ABC Analysis:** Bar chart showing distribution of costs among ABC classes.
- **Sample Data Table:** Example ATC class breakdown with cost, percentage, ABC class, and utilization pattern.
- **Summary Cards:** Quick stats on total expenditure and ABC class distributions.

## Usage

1. **Clone or Download the Repository**
    ```bash
    git clone https://github.com/LuqmanBinFahad/Hospital-Drug-Utilization-Analysis-Tool.git
    ```
2. **Open `index.html` in Your Browser**
    - No server setup required—everything runs client-side.

3. **Customize for Your Data**
    - Replace sample data and structure with your hospital’s actual datasets.
    - Integrate backend data sources as needed for automated updates.

## Technology Stack

- **HTML5, CSS3**: Responsive UI and clean design.
- **JavaScript**: Client-side interactivity.
- **Chart.js**: Dynamic charts and visualizations.

## Example Visualizations

- **Cost Distribution Pie Chart**
- **ABC Analysis Bar Chart**
- **Data Table of Drug Classes**
- **Summary Cards for Expenditure Breakdown**

## Customization

- Update the sample data in JavaScript to reflect your actual hospital drug usage and cost.
- Modify the table structure, chart labels, and UI colors as needed.

## Author

Designed and developed by [Luqman Bin Fahad](https://github.com/LuqmanBinFahad)
