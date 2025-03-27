# 📌 Malicious URL Detection - Dataset Processing Notebook

## 📖 Overview
This Jupyter Notebook is designed to process and clean datasets containing various types of URLs, including benign, phishing, malware, and defacement URLs. The dataset is merged from multiple sources, cleaned, and prepared for further analysis.

## 📂 Dataset Sources
The notebook loads data from the following sources:
- **Benign URLs** 🟢
- **Phishing URLs** 🎣
- **Malware URLs** 🦠
- **Defacement URLs** 🚨
- **Spam URLs** ✉️

These datasets are read from CSV files and merged into a single comprehensive dataframe.

## 🚀 Features
- ✅ **Data Loading**: Reads multiple datasets into Pandas DataFrames.
- ✅ **Data Cleaning**: Removes duplicates and standardizes column names.
- ✅ **Data Merging**: Combines all sources into a structured dataset.
- ✅ **Commented Code**: Each cell includes descriptive comments for clarity.
- ✅ **Formatted Code**: Code has been cleaned and optimized for better readability.

## 🛠️ Dependencies
Ensure you have the following Python libraries installed:
```bash
pip install pandas jupyter
```

## 🏁 Getting Started
1. Open the notebook in Jupyter:
   ```bash
   jupyter notebook cleaned_sample.ipynb
   ```
2. Run each cell sequentially to process the dataset.
3. The final cleaned dataset will be ready for further analysis or machine learning applications.

## 📊 Example Output
The processed dataset will have the following structure:
| URL | Type |
|------|------|
| example.com | benign |
| phishing-site.com | phishing |
| malware-link.net | malware |

## 📜 License
This project is open-source and available for educational and research purposes.

## 🤝 Contributions
Feel free to contribute by improving data cleaning techniques, adding new datasets, or optimizing the workflow!

---
✨ **Happy Coding!** ✨

