# 🌍 World Happiness Report — Data Analysis & Insights


## 📌 Project Overview

This project performs in-depth **data analysis and visualization** on the World Happiness Report dataset covering **2,363 records across 165+ countries** from 2008 to 2023. The goal is to uncover what makes nations happy, identify global trends, and analyze the key factors that drive happiness scores worldwide.

---

## 📂 Dataset

- **Source:** [Kaggle — World Happiness Report 2024](https://www.kaggle.com/datasets/usamabuttar/world-happiness-report-2005-present)
- **File:** `World-happiness-report-2024.csv`
- **Size:** 2,363 records × 11 columns
- **Content:** Country, Year, Life Ladder (Happiness Score), GDP per Capita, Social Support, Life Expectancy, Freedom, Generosity, Corruption Perception, Positive/Negative Affect

---

## 🧹 Data Cleaning Steps

| Step | Action |
|------|--------|
| 1 | Removed duplicate records |
| 2 | Dropped rows with missing critical values (Life Ladder, GDP) |
| 3 | Created latest year snapshot for country-level analysis |
| 4 | Standardized column formatting |

---

## 📊 Analysis & Visualizations

| Chart | Description |
|-------|-------------|
| Top & Bottom Countries | Happiest vs least happy countries comparison |
| GDP vs Happiness | Scatter plot with trend line and country annotations |
| Happiness Trend | Top 5 countries happiness score over 15 years |
| Social Support vs Happiness | Relationship between support and happiness |
| Happiness Distribution | Global score distribution with mean and median |
| Freedom vs Happiness | Impact of freedom of choice on happiness |

---

## 💡 Key Insights

- **Total Records Analyzed:** 2,363 across 165+ countries
- **Date Range:** 2008 – 2023
- **Global Average Happiness Score:** ~5.5 / 10
- **GDP per capita** is the strongest predictor of happiness
- **Social support** is nearly as important as GDP
- **Freedom of choice** shows meaningful positive correlation
- **Generosity** shows the weakest link to happiness scores
- Nordic countries (Finland, Denmark, Iceland) consistently top the rankings

---

## 🇵🇰 Pakistan Insights

- Pakistan's happiness trend tracked over all available years
- Compared against global average for the latest year
- Analysis shows Pakistan's score relative to regional and global benchmarks

---

## 🛠️ Tools & Libraries

```
Python 3.10
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
```

---

## 📁 Repository Structure

```
world-happiness-analysis/
│
├── World_Happiness_Analysis_Muhammad_Iman_Khan.ipynb  # Main notebook
├── World-happiness-report-2024.csv                    # Dataset
├── charts/
│   ├── 01_top_bottom_countries.png
│   ├── 02_gdp_vs_happiness.png
│   ├── 03_happiness_vs_gdp.png
│   ├── 04_happiness_trend_top5.png
│   ├── 05_social_support_vs_happiness.png
│   ├── 06_happiness_distribution.png
│   └── 07_freedom_vs_happiness.png
└── README.md
```

---

## 🚀 How to Run

1. Clone the repository
```bash
git clone https://github.com/muhammadimankhan/world-happiness-analysis.git
cd world-happiness-analysis
```

2. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/usamabuttar/world-happiness-report-2005-present) and place the CSV in the root folder

4. Open the notebook
```bash
jupyter notebook World_Happiness_Analysis_Muhammad_Iman_Khan.ipynb
```

---

## 👤 Author

**Muhammad Iman Khan**
- LinkedIn: [linkedin.com/in/muhammadimankhan](https://linkedin.com/in/muhammadimankhan)
- GitHub: [github.com/muhammadimankhan](https://github.com/muhammadimankhan)
- Email: muhammadimankhan1@gmail.com

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).