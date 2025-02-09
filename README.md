# Network Intrusion Detection System (NIDS) Preprocessing

## Overview
This project focuses on preprocessing data for a **Network Intrusion Detection System (NIDS)**. The goal is to standardize, clean, and prepare network traffic data to improve the efficiency of machine learning models in identifying different types of cyber threats.

## Key Features
- **Feature Selection:** Identifies and removes low-variance or redundant features.
- **Standardization:** Normalizes data to enhance model performance.
- **Label Encoding:** Converts categorical attack labels into numerical representations.
- **Segmentation by Attack Type:** Processes data separately for various types of attacks to facilitate targeted model training.
- **Scalability:** Designed to handle large datasets efficiently.

## Dataset
The dataset contains network traffic logs labeled based on different attack categories (e.g., DoS, Probe, R2L, U2R). This data is used to train models for anomaly detection.

## Installation & Usage
1. Clone the repository:
   ```sh
   git clone (https://github.com/your-username/kdd-99.git)
   cd nids-preprocessing
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the preprocessing script:
   ```sh
   python preprocess.py
   ```

## Warnings & Considerations
- Some features may be automatically dropped due to zero variance.
- Ensure proper dataset formatting before running the script.
- The preprocessed data should be validated before model training.

## Future Enhancements
- Implement automated feature engineering.
- Explore deep learning-based feature selection.
- Optimize preprocessing for real-time applications.

## Contributors
- **Aditi Saxena**

## License
This project is open-source under the MIT License.

