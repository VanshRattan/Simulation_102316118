# 📊 Data Generation using Modelling and Simulation for Machine Learning
---

# 🎯 Objective

The objective of this assignment is to:

1. Select a simulation tool.
2. Generate synthetic data using modelling and simulation.
3. Run 1000 simulations.
4. Train multiple Machine Learning models.
5. Compare performance.
6. Report the best model.

---

# 🛠 Simulation Tool Used

**SimPy (Discrete Event Simulation Library in Python)**

Modeled a **Single Server Queue System**:

- Customers arrive randomly (Poisson distribution)
- Service time follows exponential distribution
- System capacity varies
- Output measured: Average Waiting Time

---

# ⚙️ Parameter Bounds

| Parameter | Lower Bound | Upper Bound |
|------------|------------|------------|
| Arrival Rate | 0.5 | 5.0 |
| Service Rate | 0.5 | 6.0 |
| Capacity | 1 | 3 |
| Simulation Time | 1000 | Fixed |

Total simulations generated: **1000**

---

# 🔄 Methodology Flowchart

```
Start
  ↓
Define Parameter Bounds
  ↓
Generate Random Parameters
  ↓
Run SimPy Simulation
  ↓
Record Average Waiting Time
  ↓
Repeat 1000 Times
  ↓
Create Dataset
  ↓
Train ML Models
  ↓
Evaluate Models (MAE, RMSE, R2)
  ↓
Select Best Model
  ↓
End
```

---

# 📊 Dataset Description

**Input Features:**
- arrival_rate
- service_rate
- capacity

**Target Variable:**
- avg_wait_time

Total Dataset Size: 1000 rows

---

# 📈 Result Graphs

##  Distribution of Average Waiting Time

<img width="685" height="461" alt="image" src="https://github.com/user-attachments/assets/471896ac-0fdd-4c1d-a3bb-b6fdcbd639c2" />

---

## 3️⃣ Model Performance Table
<img width="396" height="230" alt="image" src="https://github.com/user-attachments/assets/26974eda-685c-48a7-bebd-93789fa330f4" />


---

## 4️⃣ Model Comparison Graph (R2 Score)

<img width="945" height="465" alt="image" src="https://github.com/user-attachments/assets/e9d8268d-1339-493c-8643-3effa7925c23" />

---

# 🤖 Machine Learning Models Used

- Linear Regression  
- Decision Tree  
- Random Forest  
- Gradient Boosting  
- KNN  
- SVR  

---

# 📋 Model Performance Summary

| Model | R2 Score |
|--------|----------|
| KNN | 0.9842 |
| Random Forest | 0.9770 |
| Decision Tree | 0.9383 |
| Gradient Boosting | 0.9236 |
| Linear Regression | 0.4928 |
| SVR | 0.2040 |

---

# 🏆 Best Model

**K-Nearest Neighbors (KNN)**

Reason:
- Highest R2 Score
- Lowest RMSE
- Best performance for nonlinear queue behavior

---

# 🧠 Conclusion

This project demonstrates that:

- Simulation can generate realistic synthetic data.
- Machine Learning models can predict system performance.
- Nonlinear models perform better for queue systems.
- KNN achieved the best accuracy among tested models.

---
odel reported  

---
