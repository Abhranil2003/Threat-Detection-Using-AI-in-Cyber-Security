# Threat Detection Using AI in Cyber Security
**Author:** Abhranil Poddar

This project leverages artificial intelligence and machine learning techniques to enhance threat detection in the field of cybersecurity. The goal is to identify, analyze, and mitigate potential threats using advanced data processing and modeling.

## Project Structure

### `attack-division.ipynb`
- Divides and organizes data specific to various types of cyberattacks.
- Provides insights into the distribution and characteristics of attack data.
- Includes visualizations to better understand the impact and frequency of different types of threats.

### `feature-selection.ipynb`
- Implements feature selection techniques such as correlation analysis and mutual information.
- Reduces dimensionality by identifying the most relevant features for threat detection.
- Improves model performance by eliminating irrelevant or redundant attributes.

### `machine-learning-sep.ipynb`
- Applies various machine learning algorithms, including:
  - Decision Trees
  - Random Forests
  - Support Vector Machines (SVM)
  - Neural Networks
- Evaluates model performance using metrics like accuracy, precision, recall, and F1-score.
- Compares results to determine the most effective model for threat classification.

### `pre-process.ipynb`
- Focuses on data cleaning and transformation:
  - Handles missing values and outliers.
  - Normalizes data for consistent scaling.
  - Encodes categorical variables for compatibility with machine learning algorithms.
  - Utilizes the `CIC-IDS2017` dataset stored in CSV format for preprocessing and analysis.
    The CIC-IDS2017 dataset can be accessed through [here](https://www.unb.ca/cic/datasets/ids-2017.html).
- Prepares the dataset for further analysis and modeling.

## Features

- End-to-end pipeline for cybersecurity threat detection.
- Preprocessing and feature selection for effective modeling.
- Machine learning models for accurate classification of threats.
- Insights into attack-specific data organization.

## Requirements

- Python 3.x
- Jupyter Notebook
- Required Python Libraries:
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`

Install the dependencies using:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/threat-detection-ai.git
   cd threat-detection-ai
   ```

2. Install the required dependencies.

3. Open the Jupyter Notebooks and execute the cells in sequence for each phase of the project:
   - Data preprocessing (`pre-process.ipynb`)
   - Feature selection (`feature-selection.ipynb`)
   - Attack-specific analysis (`attack-division.ipynb`)
   - Model training and evaluation (`machine-learning-sep.ipynb`)

## Results

- A well-defined pipeline for cybersecurity threat detection.
- Visualization and insights derived from the data.
- Performance metrics of machine learning models.

## Contribution

Contributions are welcome! If you wish to improve the project or add new features, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---
