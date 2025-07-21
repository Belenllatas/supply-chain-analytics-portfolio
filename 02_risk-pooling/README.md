# 📦 Risk Pooling – Inventory Optimization in Supply Chains

This project explores how centralized distribution can reduce inventory costs through **risk pooling**.  
It includes two models developed during the Supply Chain Management course at **Hofstra University (New York, USA)**.

---

## 🧠 What’s Included

- `02_risk-pooling_epson_case.xlsx` → 📄 Real-world scenario (Epson printer case – Quiz 4)  
- `02_risk-pooling_class_model.xlsx` → 📊 Simplified class exercise (fictional demand)  

---

## 🖨️ Case 1: Epson Risk Pooling – Quiz 4  
**File:** `02_risk-pooling_epson_case.xlsx`

Epson manufactures printers in **Taiwan** and sells them in six European countries.  
Currently, it assembles and packages printers **separately for each country**, which leads to higher inventory levels.

To reduce excess inventory, Epson is considering a **centralized Distribution Center (DC)** in Europe.  
In this new model, **base printers** (without power supplies or manuals) would be shipped from Taiwan  
with a **lead time of 8 weeks**, then customized and delivered on demand.

### 📊 Input Data (Weekly Demand):

| Country   | Mean Demand | Std. Deviation |
|-----------|-------------|----------------|
| France    | 3,000       | 2,000          |
| Germany   | 4,000       | 2,200          |
| Spain     | 2,000       | 1,400          |
| Italy     | 2,500       | 1,600          |
| Portugal  | 1,000       | 800            |
| UK        | 4,000       | 2,400          |

- Lead time: **8 weeks**  
- Target service level: **95%** (z = 1.645)

### ❓ Problem Statement

> a. How much **safety inventory** does Epson need under the current decentralized model?  
> b. How much inventory could Epson save by moving to a **centralized European DC**?

📚 Based on *Quiz 4 – Risk Pooling* by Prof. Ping Su

---

## 📊 Case 2: Class Exercise – Centralization Logic  
**File:** `02_risk-pooling_class_model.xlsx`

This spreadsheet demonstrates the core logic of risk pooling using **fictional demand data** across three independent regions.

### Example Input:

| Region   | Weekly Mean Demand | Std. Deviation |
|----------|--------------------|----------------|
| East     | 1,000              | 400            |
| Central  | 800                | 300            |
| West     | 1,200              | 500            |

It compares the total **safety stock** in:

- A **decentralized** system (each region holds its own safety inventory)  
- A **centralized** system (all demand is pooled into one location)

---

## 🎯 Learning Objectives

- Understand the concept of **demand aggregation**
- Apply the formula for **safety stock** in normal distributions
- Quantify the effect of centralizing inventory across multiple markets

---

## 🔍 Key Concepts

- Risk pooling  
- Inventory centralization  
- Safety stock  
- Normal distribution  
- Z-score (`NORM.INV`)  
- Demand variability

---

## 👩‍💻 Author

Belén Llatas Beny  
📍 Valencia, Spain  
📧 belenllatas1@gmail.com  
🔗 [www.linkedin.com/in/belénllatasbeny](https://www.linkedin.com/in/belénllatasbeny)

---

## 🌍 Language & Availability

This project was developed in English for academic and professional use.  
However, I’m fully available to explain the logic, formulas, and results in **Spanish**, and I can provide translated materials upon request — especially useful for roles in Spanish-speaking companies or international teams.
