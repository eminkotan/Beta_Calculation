# 📊 Beta Calculation with Python [ENG] -> [TR açıklama aşağıda]

This repository provides a Python-based implementation for estimating the **Beta (β)** of a stock relative to the market using **linear regression**. It demonstrates the core concept of systematic risk and how a stock's return is influenced by market movements — a key component of the **Capital Asset Pricing Model (CAPM)**.

---

## 🧮 Methodology

The beta coefficient is estimated using the following linear regression model:

```latex
R_i = \alpha + \beta R_m + \varepsilon
```

Where:

- \(R_i\): Return of the individual asset (e.g., AMD)
- \( R_m \): Return of the market (e.g., S&P 500)
- \( \beta \): Sensitivity of the asset to market movements
- \( \alpha \): Stock-specific return (intercept)

---

## 📁 Files

- `Beta Calculation.ipynb`: Main Jupyter Notebook containing data loading, processing, regression, and visualization
- `data.csv`: Contains historical closing prices for AMD and S&P 500 (user must provide or update)

---

## 🛠️ Requirements

- Python 3.8+
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- statsmodels

Install dependencies with:

```bash
pip install pandas numpy matplotlib statsmodels
```
 # 📈 Python ile Beta Hesaplama [TR]


Bu depo, bir hissenin **Beta katsayısını (β)** tarihsel fiyat verileri ve doğrusal regresyon kullanarak Python'da nasıl hesaplayabileceğinizi gösterir.

---

## 🔍 What's Inside? / İçerik

- Daily return calculation for **S&P 500** and **AMD**
- Linear regression using `statsmodels`
- Visualization with `matplotlib`
- Scatter plot and regression line
- Interpretation of Beta and Alpha

---

## 📊 Example Output / Örnek Çıktı

Beta Coefficient (β): 1.9455
Alpha (α): -0.0017


> 🧠 **Interpretation:** AMD stock is highly sensitive to market movements.  
> 🧠 **Yorum:** AMD hissesi piyasa hareketlerine oldukça duyarlıdır.

---

## 🛠️ Requirements / Gereksinimler

- Python 3.8+
- pandas
- matplotlib
- statsmodels
- numpy

### Install dependencies / Kütüphanelerin kurulumu:

```bash
pip install pandas matplotlib statsmodels numpy
```
🚀 How to Run / Nasıl Kullanılır

Clone the repository / Reposityory’yi klonlayın:
```bash
git clone https://github.com/eminkotan/Beta_Calculation.git
```
Open the Jupyter notebook / Jupyter defterini açın:
```bash jupyter notebook "Beta Calculation.ipynb" ```



Run the notebook cells / Hücreleri çalıştırın ve sonuçları inceleyin.
📚 Notes / Notlar

#Data range: 2022–2024 daily returns
You can easily customize this notebook for other stock/market comparisons
Bu çalışma 2022-2024 tarihleri arasındaki günlük getirilerle yapılmıştır. Başka hisse veya piyasa verileri ile kolayca uyarlanabilir.
👨‍💻 Author / Yazar

Emin Kotan
Economics student passionate about finance, valuation, and data science.
Finans, değerleme ve veri bilimiyle ilgilenen bir iktisat öğrencisi.

