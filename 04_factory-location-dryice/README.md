# Factory Location Optimization – DryIce Case (Quiz)

This project solves a factory location problem using **binary decision variables** in Excel Solver.  
It was developed during the Supply Chain Management course at **Hofstra University (New York, USA)**.

---

## 🧭 Problem Overview

A company is evaluating the best factory setup to serve customers across 4 regions.  
Each factory has:

- A **fixed cost** to open  
- A **variable cost per unit shipped**  
- A **capacity limit**  
- Some factories may be more expensive, but closer to customers

The objective is to **minimize total cost** (fixed + variable), while meeting all customer demand.

---

## 📊 Input Data (from Quiz 1)

- **Customers**: North, South, East, West  
- **Demand**:
  - North: 100 units  
  - South: 200 units  
  - East: 150 units  
  - West: 250 units  
- **Facilities**:
  - Each has:
    - Fixed operating cost  
    - Variable shipping costs to each region  
    - Maximum capacity

See full table in the attached file `Quiz 1 Description.pdf`.

---

## 📈 Excel Model Logic

**File:** `04_dryice_factory_location.xlsx`

The model uses:

- A matrix of shipping costs  
- Binary decision variables to indicate whether a facility is open  
- Constraints for:
  - Meeting all customer demand  
  - Not exceeding plant capacities  
  - Only shipping from open facilities

Solver is used to find the **lowest-cost configuration**.

---

## 📁 Files Included

- `04_dryice_factory_location.xlsx` – Excel optimization model with Solver  
- `Quiz 1 Description.pdf` – Original case with full data and context

---

## 🧠 Learning Objectives

- Use **binary variables** in Excel Solver  
- Model real-life facility location problems  
- Understand trade-offs between fixed and variable costs  
- Apply constraints for demand fulfillment and capacity

---

## 🔍 Key Concepts

- Binary decision variables  
- Excel Solver  
- Facility location  
- Fixed vs. variable cost  
- Demand satisfaction  
- Capacity constraints

---

## 📚 Attribution

This project is based on an academic quiz created by **Prof. Ping Su** at Hofstra University.  
The material was shared with students for educational purposes and is used here solely to demonstrate applied knowledge of supply chain modeling.  
If required, this file can be removed upon request from the author or institution.

---

## 👩‍💻 Author

Belén Llatas Beny  
📍 Valencia, Spain  
📧 belenllatas1@gmail.com  
🔗 [www.linkedin.com/in/belénllatasbeny](https://www.linkedin.com/in/belénllatasbeny)

---

## 🌍 Language & Availability

This project was developed in English for academic and professional use.  
I’m fully available to explain it in **Spanish**, and can provide translated files or live explanations upon request.
