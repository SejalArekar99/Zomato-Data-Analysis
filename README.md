# Zomato-Data-Analysis
It helps to analysis restaurant data 
# 🍽️ Zomato Data Analysis Project

A beginner-friendly exploratory data analysis (EDA) project on Zomato restaurant data using Python. This project uncovers insights about restaurant types, ratings, votes, ordering modes, and spending patterns.

---

## 📁 Dataset

**File:** `Zomato data .csv`

| Column | Description |
|---|---|
| `name` | Restaurant name |
| `online_order` | Whether online ordering is available (Yes/No) |
| `book_table` | Whether table booking is available (Yes/No) |
| `rate` | Customer rating (out of 5) |
| `votes` | Total number of votes received |
| `approx_cost(for two people)` | Approximate cost for two people (in ₹) |
| `listed_in(type)` | Type/category of restaurant |

---

## 📊 Analysis Performed

### 1. Type of Restaurant
- Visualized the distribution of restaurant types using a count plot.
- **Finding:** Majority of restaurants fall in the **Dining** category.

### 2. Votes by Restaurant Type
- Plotted total votes received per restaurant type.
- **Finding:** Dining restaurants have received the **maximum votes**.

### 3. Rating Distribution
- Plotted a histogram of restaurant ratings.
- **Finding:** Majority of restaurants received ratings between **3.5 and 4**.

### 4. Average Spending by Couples
- Analyzed approximate cost for two people using a count plot.
- **Finding:** Most couples prefer restaurants with an approximate cost of **₹300**.

### 5. Online vs Offline Order Ratings
- Used a box plot to compare ratings for online vs offline orders.
- **Finding:** **Online orders** received slightly higher ratings than offline orders.

### 6. Heatmap – Order Mode vs Restaurant Type
- Created a pivot table heatmap showing the relationship between restaurant type and online ordering.
- **Finding:** Dining restaurants predominantly receive **offline orders**, while cafes and quick bites lean towards online orders.

---

## 🛠️ Technologies Used

- **Python 3**
- **Pandas** – Data loading and manipulation
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualizations
- **Jupyter Notebook / Google Colab** – Development environment

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/zomato-data-analysis.git
cd zomato-data-analysis
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the notebook

```bash
jupyter notebook Zomato_Data_Analysis_Project.ipynb
```

> **Note:** If using Google Colab, upload the CSV file to `/content/` and run all cells.

---

## 📂 Project Structure

```
zomato-data-analysis/
│
├── Zomato data .csv                    # Dataset
├── Zomato_Data_Analysis_Project.ipynb  # Main analysis notebook
├── requirements.txt                    # Python dependencies
└── README.md                           # Project documentation
```

---

## 🙋 Author

Made with ❤️ as a mini data analysis project.
Feel free to fork, star ⭐, and contribute!
