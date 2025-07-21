# 🚚 Transportation & Facility Location Models

This project presents two key supply chain models:  
1. The **Transportation Problem** – optimizing shipment plans from facilities to customers.  
2. The **Facility Location Problem** – selecting which factories to open in order to minimize total cost.

Both were solved using **Microsoft Excel + Solver** as part of the Supply Chain Management course at **Hofstra University (New York, USA)**.

---

## 📦 Model 1: Transportation Optimization  
**File:** `03_transportation_model.xlsx`  
📄 Reference: `Transportation and Location Models copia.pdf`

A company distributes products from 3 warehouses (A, B, C) to 4 customer zones.  
Each warehouse has a limited supply, each zone has a fixed demand, and each route has a known shipping cost.

### 🔢 Input Data

| From / To | Zone 1 | Zone 2 | Zone 3 | Zone 4 | Supply |
|-----------|--------|--------|--------|--------|--------|
| A         | 2      | 3      | 11     | 7      | 100    |
| B         | 1      | 0      | 6      | 1      | 300    |
| C         | 5      | 8      | 15     | 9      | 300    |
| Demand    | 200    | 225    | 275    | 0      |        |

🎯 **Goal:** Minimize total transportation cost while satisfying all demand and respecting all supply constraints.

---

## 🏭 Model 2: Facility Location with Fixed Costs  
**File:** `03_facility_cost_solver.xlsx`  
📄 Reference: `Additional Transportation Problems.pdf`

This is a **more advanced model**, where the company must decide:

- Which of the 4 factories to keep open  
- How much to ship from each open plant to each of the 5 customers  
- How to **minimize total cost**, which includes both **fixed costs per plant** and **variable shipping costs**

### 📊 Input Example (simplified):

- **Fixed Costs per Plant**:  
  - Facility A: $50,000  
  - Facility B: $60,000  
  - Facility C: $70,000  
  - Facility D: $65,000

- **Capacities and customer demands provided in spreadsheet**

🎯 **Goal:** Decide **which facilities to open**, then assign shipping quantities to minimize the combined cost (fixed + variable).

---

## 🧠 Learning Objectives

- Apply linear programming to minimize transportation cost  
- Understand trade-offs between **fixed facility costs** and **shipping efficiency**  
- Use **binary decision variables** in Solver for facility selection

---

## 📁 Files Included

- `03_transportation_model.xlsx` – Classic LP model with supply/demand matrix  
- `03_facility_cost_solver.xlsx` – Facility selection + shipping assignment  
- `Transportation and Location Models copia.pdf` – Problem 1 description  
- `Additional Transportation Problems.pdf` – Problem 2 description

---

## 🔍 Key Concepts

- Transportation problem  
- Facility location  
- Binary variables in optimization  
- Excel Solver  
- Fixed vs. variable cost tradeoffs  
- Supply-demand balance

---

## 👩‍💻 Author

Belén Llatas Beny  
📍 Valencia, Spain  
📧 belenllatas1@gmail.com  
🔗 [www.linkedin.com/in/belénllatasbeny](https://www.linkedin.com/in/belénllatasbeny)

---

## 🌍 Language & Availability

This project was developed in English for academic and professional purposes.  
I'm fully available to explain it in **Spanish**, and can provide translated materials or live explanation if needed.
