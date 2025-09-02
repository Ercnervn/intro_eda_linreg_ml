# EDA + Linear Regression — California Housing

**EN:** A compact exploratory data analysis and a few baseline linear regression experiments on the California Housing dataset. Includes quick visuals, simple feature prep, and MAE/RMSE evaluation.  
**TR:** California Housing veri seti üzerinde kısa bir keşifçi veri analizi ve birkaç temel lineer regresyon deneyi. Hızlı görselleştirmeler, basit özellik hazırlığı ve MAE/RMSE değerlendirmesi içerir.

---

## 📁 Project Structure
├─ CaliforniaHousePricesWork.ipynb
├─ data
└─ README.md

---

## 🔎 Highlights / Öne Çıkanlar
- **EDA:** distributions, correlations, simple feature engineering
- **Models / Modeller:** LinearRegression, Ridge, Lasso, ElasticNet (± CV)
- **Metrics / Metrikler:** MAE, RMSE, R²
- **Notebook:** `CaliforniaHousePricesWork.ipynb`

---

## 🧰 Dataset
- **Source / Kaynak:** `sklearn.datasets.fetch_california_housing`
- **Target / Hedef:** `MedHouseVal` (median house value)
- **Features / Özellikler (örnek):** MedInc, HouseAge, AveRooms, AveBedrms, Population, AveOccup, Latitude, Longitude

---

## 📊 Results (from the notebook) / Sonuçlar (notebook'tan)
| Model | MAE | RMSE | R² |
|---|---:|---:|---:|
| Linear Regression | 53152.41 | 73453.84 | 0.60 |
| Ridge | 53164.54 | 73454.69 | 0.60 |
| Lasso | 53153.26 | 73453.81 | 0.60 |
| ElasticNet | 57625.84 | 77792.28 | 0.55 |
| ElasticNetCV | 89703.80 | 113932.91 | 0.03 |

---

## 🙌 Acknowledgements / Teşekkür
- Tools: Python, Jupyter, NumPy, pandas, Matplotlib, scikit-learn



  