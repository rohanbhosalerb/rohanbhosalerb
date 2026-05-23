<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:0d1117,50:0d2137,100:0d1117&height=180&section=header&text=Sales%20Analytics&fontSize=52&fontColor=00d9ff&animation=fadeIn&stroke=00d9ff&strokeWidth=2&fontAlignY=50&desc=Exploratory%20Data%20Analysis%20%7C%20Python%20%7C%20Pandas%20%7C%20Seaborn&descAlignY=70&descColor=8892b0&descSize=15"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&pause=1000&color=00D9FF&center=true&vCenter=true&width=700&lines=End-to-end+Sales+EDA+with+Python+%F0%9F%90%8D;Data+Cleaning+%E2%86%92+Analysis+%E2%86%92+Visualizations+%F0%9F%93%8A;1%2C000+Orders+%7C+5+Categories+%7C+4+Regions;Built+by+Rohan+Bhosale+%40+RWTH+Aachen" alt="Typing SVG" />

<br/>

[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Pandas](https://img.shields.io/badge/Pandas-2.0+-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![Seaborn](https://img.shields.io/badge/Seaborn-0.12+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://seaborn.pydata.org)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7+-11557c?style=for-the-badge&logo=python&logoColor=white)](https://matplotlib.org)
[![License](https://img.shields.io/badge/License-MIT-00d9ff?style=for-the-badge)](LICENSE)

</div>

---

### `> cat project.json`

```python
project = {
  "title"      : "Sales Analytics — EDA Pipeline",
  "author"     : "Rohan Bhosale",
  "dataset"    : "Synthetic retail sales (1,000 orders · 2023)",
  "stack"      : ["Python", "Pandas", "NumPy", "Matplotlib", "Seaborn"],
  "outputs"    : ["Monthly Revenue Trend", "Category Breakdown",
                  "Region × Category Heatmap", "Discount Impact Analysis"],
  "status"     : "✅ Complete"
}
```

---

### `> ls ./outputs`

<div align="center">

| Chart | Description |
|---|---|
| `monthly_revenue.png` | Revenue trend across all 12 months |
| `category_breakdown.png` | Bar + pie chart of revenue per category |
| `region_category_heatmap.png` | Revenue heatmap — region × category |
| `discount_impact.png` | How discount levels affect revenue & order volume |

</div>

---

### `> cat charts.md`

<div align="center">

**Monthly Revenue Trend**
![Monthly Revenue](monthly_revenue.png)

**Category Breakdown**
![Category Breakdown](category_breakdown.png)

**Region × Category Heatmap**
![Heatmap](region_category_heatmap.png)

**Discount Impact**
![Discount Impact](discount_impact.png)

</div>

---

### `> ./run.sh`

```bash
# 1. Clone the repo
git clone https://github.com/rohanbhosalerb/Sales-Analytics.git
cd Sales-Analytics

# 2. Install dependencies
pip install -r requirements.txt

# 3. (Optional) Regenerate dataset
python generate_data.py

# 4. Run the analysis
python analyze.py
```

---

### `> cat output.log`

```
=======================================================
📦  DATASET OVERVIEW
=======================================================
  Rows      : 1,000
  Columns   : 9
  Date range: 2023-01-01 → 2023-12-31

🧹  Cleaned: dropped 40 incomplete rows → 960 remaining

=======================================================
📊  KEY METRICS
=======================================================
  Total Revenue   : $1,424,149.07
  Avg Order Value : $1,483.49
  Top Category    : Electronics

  Revenue by Region:
    West     $369,854.51
    East     $361,340.30
    South    $357,381.09
    North    $335,573.17

✅  Analysis complete!
```

---

### `> ls ./project-structure`

```
Sales-Analytics/
├── analyze.py                  # Main EDA & visualisation script
├── generate_data.py            # Synthetic dataset generator
├── sales_data.csv              # Dataset (1,000 orders)
├── monthly_revenue.png         # Chart — monthly revenue trend
├── category_breakdown.png      # Chart — revenue by category
├── region_category_heatmap.png # Chart — region × category heatmap
├── discount_impact.png         # Chart — discount vs revenue
├── requirements.txt
├── .gitignore
└── README.md
```

---

### `> ping --connect`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bhosale-rohan/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rohanbhosalede@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rohanbhosalerb)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0d2137,100:0d1117&height=100&section=footer&stroke=00d9ff&strokeWidth=1"/>
