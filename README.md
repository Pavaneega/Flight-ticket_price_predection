# Flight-ticket_price_predection

---

## 🔧 Tech Stack
| Component | Tools |
|----------|------|
| Programming | Python |
| Libraries | Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Gradio |
| Model Used | Random Forest Regressor |
| Deployment | Local Flask / Gradio Interface |

---

## 📊 Model Performance
| Metric | Score |
|--------|------|
| MSE | 4,780,296 |
| R² Score | 0.99 |

✅ The Random Forest model performed best and is used for predictions.

---

## 🧠 How It Works
1️⃣ Load and clean airline dataset  
2️⃣ Preprocess — encode categorical features & extract time features  
3️⃣ Train multiple ML models  
4️⃣ Evaluate using MAE, MSE & R² Score  
5️⃣ Deploy best model for user prediction

---

## ▶️ How to Run Locally

### 🔹 Step 1 — Clone the Repository
```bash
git clone https://github.com/Pavaneega/Flight-ticket_price_predection.git
cd Flight-ticket_price_predection
pip install -r requirements.txt
python app.py
