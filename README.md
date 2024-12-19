# Peak Detection and Differentiation

This repository provides tools and scripts to detect and analyze peaks in datasets with time and voltage data. The project was developed as a response to a common data analysis challenge where certain peaks exhibit distinct characteristics from others, and the goal was to:

1. Visualize the data and highlight the detected peaks.
2. Extract the depth value at each peak.
3. Differentiate the unique characteristics of the first peak compared to others.

---

## Use Case

The tools in this repository can be applied in various fields, including:

- Signal processing to identify anomalies or key events.
- Industrial monitoring, such as detecting voltage or pressure peaks.
- Scientific data analysis for identifying and categorizing patterns in time-series data.

---

## Getting Started

### Prerequisites

Make sure you have the following installed:
- Python 3.8 or later
- Libraries listed in `requirements.txt`

Install the required dependencies with:

```bash
pip install -r requirements.txt
```

---

### Repository Contents

- **notebooks/peak_detection_analysis.ipynb**: Jupyter Notebook with step-by-step data analysis and peak detection.
- **scripts/peak_detection.py**: Script to identify peaks and extract depth values.
- **scripts/differentiate_peaks.py**: Script to differentiate the unique characteristics of the first peak.
- **data/**: Contains example datasets for testing the scripts.

---

### Usage

#### 1. Analyze Data in Jupyter Notebook

Run the Jupyter Notebook to visualize and explore the datasets:

```bash
jupyter notebook notebooks/peak_detection_analysis.ipynb
```

#### 2. Use the Scripts

- **Identify Peaks:**
  ```bash
  python scripts/peak_detection.py --input data/dataset1.csv
  ```

- **Differentiate Peaks:**
  ```bash
  python scripts/differentiate_peaks.py --input data/dataset1.csv
  ```

---

### Results

The analysis includes:
- **Peak Identification:** Depth values and timestamps for all detected peaks.
- **Peak Differentiation:** Unique characteristics of the first peak (e.g., height, prominence) compared to others.

---

### Examples

Below are example plots generated during the analysis:

*(Insert plots from your Jupyter Notebook here)*

---

### Contributing

Feel free to fork this repository, open issues, or submit pull requests to improve the project.

---

### License

This project is licensed under the MIT License.

