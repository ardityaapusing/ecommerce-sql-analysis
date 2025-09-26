# 📊 E-Commerce Sales Analysis

[![Python](https://img.shields.io/badge/python-3.11-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![Kaggle Dataset](https://img.shields.io/badge/Dataset-Kaggle-blue)](https://www.kaggle.com/datasets/ertugrulesol/online-retail-data)

This repository contains a comprehensive **exploratory data analysis (EDA)** of an e-commerce transactions dataset using Python and Jupyter Notebook.  
The goal is to uncover insights about **customer purchasing behavior, product performance, and sales trends across countries**, providing actionable information for business strategy and decision-making.

---

## 🗂️ Project Structure
```
ecommerce-sales-analysis/
│
├─ data/ # (Optional) Raw dataset (excluded, see Data Source)
│ └─ sample_data.csv # Small sample for demo runs
├─ notebooks/ # Jupyter notebooks
│ └─ ecommerce_analysis.ipynb
├─ requirements.txt # Python dependencies
├─ README.md # Project documentation
└─ .gitignore # Files/folders to ignore
```

---

## 📂 Data Source
The dataset used in this analysis is the **[Online Retail Data](https://www.kaggle.com/datasets/ertugrulesol/online-retail-data)** from Kaggle.  

> ⚠️ Due to licensing and size restrictions, the full raw dataset is **not included** in this repository.  

To reproduce the analysis:  
1. Download the dataset from Kaggle.  
2. Place the CSV file inside the `data/` directory.  
3. The notebook will automatically load data from `data/online_retail.csv`.  

---

## 🔍 Analysis Overview
<details>
<summary>Click to expand</summary>

1. **Top-Selling Products**  
   - Identified the 10 products with the **highest total sales quantities**.  
   - Example: *Paper Craft, Little Birdie* and *Medium Ceramic Top Storage Jar* dominate sales.

2. **Top Countries by Sales**  
   - United Kingdom contributes the majority of transactions.  
   - Other significant markets: Netherlands, Germany, France, and Australia.

3. **Monthly Sales Trend**  
   - Sales show strong seasonal patterns.  
   - Peak sales occur in **November**, likely due to holiday shopping.

4. **Customer Purchase Behavior** *(Optional expansion)*  
   - Repeat purchases, average order quantity, and customer segmentation.

</details>

---

## 📊 Visualizations
- **Bar chart**: Top 10 Best-Selling Products  
- **Horizontal bar chart**: Top 10 Countries by Sales Quantity  
- **Line plot**: Monthly Sales Trend  
- *(Optional advanced visuals: heatmaps, pivot charts, distribution plots)*

---

## 🛠️ Tools & Libraries
- **Python**: Programming language for analysis  
- **Pandas / NumPy**: Data cleaning, transformation, aggregation  
- **Matplotlib / Seaborn**: Visualization and styling  
- **Jupyter Notebook / Lab**: Interactive analysis environment  
- *(Optional: Plotly for interactive charts, Scikit-learn for clustering/segmentation)*

---

## 🚀 Key Insights
- **Product concentration:** A small set of products drives the majority of sales.  
- **Market focus:** United Kingdom dominates, international sales are smaller.  
- **Seasonality:** Peak sales in Q4; potential marketing opportunity.  
- **Business recommendation:** Optimize inventory for high-performing products and plan seasonal promotions.

---

## ⚙️ Setup & Reproducibility

### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/ecommerce-sales-analysis.git
cd ecommerce-sales-analysis

```
### 2. Create a virtual environment
```bash
python -m venv venv
```
Activate the virtual environment:
```bash
# Linux/Mac
source venv/bin/activate

# Windows
venv\Scripts\activate
```
### 3. Install dependencies
```bash
pip install -r requirements.txt
```
### 4. Add dataset
Download the dataset from Kaggle and place it in the data/ folder:
`data/online_retail.csv`

### 5. Run the notebook
```bash
jupyter lab
```
Open notebooks/ecommerce_analysis.ipynb and run all cells to reproduce the analysis.

## 📌 Best Practices Implemented
- Modular project structure (notebooks/, data/, requirements.txt)
- Clear explanation of purpose, insights, and reproducibility
- Professional formatting with emoji headers, badges, and collapsible sections
- Encourages scalability for future analysis notebooks or scripts

## 🖋️ Author
**Arditya Apusing**  
- Data Analyst | Statistics Enthusiast  
- 📧 Email: [ardityasulistya6@gmail.com](mailto:ardityasulistya6@gmail.com)  
- 🔗 LinkedIn: [linkedin.com/in/ardityaapusing](https://www.linkedin.com/in/ardityaapusing/)  
- 💻 GitHub: [github.com/ardityaapusing](https://github.com/ardityaapusing)  

## 📄 License
This project is licensed under the [MIT License](LICENSE).
