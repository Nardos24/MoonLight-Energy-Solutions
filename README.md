# Solar Investment Analysis for MoonLight Energy Solutions

## Overview

This project aims to develop a strategic approach to enhance operational efficiency and sustainability through targeted solar investments. The analysis was performed on environmental measurements provided by the engineering team, focusing on identifying key trends and insights that support data-driven decision-making.

## Objectives

- Analyze environmental data to identify high-potential regions for solar installations.
- Address data quality issues to ensure reliable analysis.
- Provide actionable recommendations aligned with the company's long-term sustainability goals.

## Datasets

The analysis was conducted on three environmental datasets from different regions:

1. **Togo (Dapaong)** - `togo-dapaong_qc.csv`
2. **Sierra Leone (Bumbuna)** - `sierraleone-bumbuna.csv`
3. **Benin (Malanville)** - `benin-malanville.csv`

These datasets include key metrics such as Global Horizontal Irradiance (GHI), Direct Normal Irradiance (DNI), Diffuse Horizontal Irradiance (DHI), and various temperature metrics.

## Key Findings

- **Solar Potential**:
  - Benin shows the highest mean GHI at 240.56 W/m², indicating significant solar potential.
- **Data Quality Issues**:
  - High counts of negative values for GHI and DNI suggest potential sensor errors.
  - The "Comments" column in all datasets is largely empty and may not provide useful insights.
- **Outliers**:
  - Several outliers were detected in GHI and DNI across all datasets, which could skew analysis results.

## Recommendations

1. **Focus on High-Potential Regions**:
   - Prioritize investments in Benin (Malanville) due to favorable solar metrics.
  
2. **Enhance Data Quality**:
   - Collaborate with the engineering team to rectify data collection issues and validate sensor accuracy.
  
3. **Conduct Further Analysis**:
   - Implement longitudinal studies to monitor solar metrics over time.
   - Utilize geospatial analysis to align solar potential with community needs.

4. **Pilot Program**:
   - Launch a pilot project in Benin to assess solar technology effectiveness and gather additional data.

## Getting Started

### Prerequisites

- Python 3.x
- Required libraries:
  - `pandas`
  - `numpy`
  - `seaborn`
  - `matplotlib`
  - `scipy`

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Nardos24/MoonLight-Energy-Solutions.git
    cd MoonLight-Energy-Solutions
    ```

2. Create a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required libraries:
    ```bash
    pip install pandas numpy seaborn matplotlib scipy
    ```

### Running the Analysis

To run the analysis, execute the following command:

```bash
python main.py
