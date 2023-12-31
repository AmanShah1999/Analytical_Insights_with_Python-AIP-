# XRD Data Analysis

## Overview

This Jupyter Notebook focuses on the analysis of X-ray Diffraction (XRD) data, specifically sourced from research conducted at IITM. The objective is to provide insights into material characterization through a series of analytical steps.

## Notebook Information

- **Creator:** Aman Kumar Shah
- **Date Created:** 30/12/2023
- **GitHub Repository:** [Analytical_Insights_with_Python-AIP](https://github.com/Amanshah383/Analytical_Insights_with_Python-AIP-)

## Data Information

- **Data Source:** XRD_Sample_Data.txt
- **Format:** Text file (.txt)

## Analysis Steps

1. **Data Loading and Exploration ([Section 1](#1))**
   - Utilizing Pandas, the notebook loads XRD data, performs exploratory data analysis (`df.info()`, `df.head()`, `df.describe()`), providing a comprehensive overview of the dataset.

2. **Plotting the Data as Line Graph ([Section 2](#2))**
   - Utilizing Matplotlib, the XRD data is visually represented through a line graph, providing a clear depiction of the relationship between XRD angles (`2 theta`) and intensity values (`Intensity(a.u)`).

3. **Peak Detection and Plotting with the Peaks ([Section 3](#3))**
   - Leveraging the `peakdetect` library, the notebook identifies and visualizes significant peaks in the XRD data. Key parameters (`lookahead`, `delta`) impact the sensitivity and threshold for peak detection.

4. **Smoothing the Curve, Filtering the Noise ([Section 4](#4))**
   - The Savitzky-Golay filter is applied to the XRD data to reduce noise and enhance patterns. Parameters (`window_size`, `poly_order`) influence the size of the smoothing window and the polynomial order for fitting.

## How to Use

1. **Data Loading and Exploration**
   - Inspect the XRD data using `df.info()`, `df.head()`, and `df.describe()` in [Section 1](#1).

2. **Plotting the Data as Line Graph**
   - Visualize the XRD data through a line graph by running the code in [Section 2](#2).

3. **Peak Detection and Plotting with the Peaks**
   - Identify and visualize peaks in the XRD data using the `peakdetect` library in [Section 3](#3).

4. **Smoothing the Curve, Filtering the Noise**
   - Apply the Savitzky-Golay filter to smooth the XRD data in [Section 4](#4).

## Additional Notes

- This notebook is designed for educational and analytical purposes.
- The analysis is performed using essential Python libraries, including NumPy, Pandas, Matplotlib, Peakdetect, and SciPy.

## Acknowledgements

Special thanks to the contributors of the libraries used in this analysis.

---

**Note:** Some sections are marked for future updates, and additional features will be added over time.
