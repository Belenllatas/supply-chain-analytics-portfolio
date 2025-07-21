# 📦 Risk Pooling – Inventory Optimization for Multinational Distribution

This project analyzes the benefits of **risk pooling** in a multinational distribution context, using Excel to compare safety inventory requirements in decentralized and centralized systems.

## 🗂️ Context

The model is based on a classroom quiz from the Supply Chain Management course at **Hofstra University (New York, USA)**. The case simulates **Epson's printer distribution strategy in Europe**, where weekly demand varies by country and is uncertain.

Currently, Epson manufactures printers in **Taiwan** and ships them to Europe with a **lead time of 8 weeks**. Each printer is assembled and packed specifically for the destination country, with localized power supplies and manuals.

Epson is considering a new strategy: building a **centralized European Distribution Center (DC)**. The idea is to ship **base printers** (without power supply or manuals) from Taiwan to the DC. Once an order is received, the DC would customize the units and deliver them to the appropriate country.

The project compares these two configurations:

- **Decentralized model**: 6 countries are served independently.
- **Centralized model**: a single DC pools demand across Europe.

> 📚 The scenario is adapted from *Quiz 4 – Risk Pooling* by Prof. Ping Su.

## 🎯 Objective

- Calculate the total **safety inventory** required across six countries with 8-week lead time and 95% service level.
- Evaluate the impact of **centralizing** inventory at a single DC.
- Quantify the **inventory savings** achieved through risk pooling.

## 📈 Input Data

| Country   | Mean Demand | Standard Deviation |
|-----------|-------------|--------------------|
| France    | 3,000       | 2,000              |
| Germany   | 4,000       | 2,200              |
| Spain     | 2,000       | 1,400              |
| Italy     | 2,500       | 1,600              |
| Portugal  | 1,000       | 800                |
| UK        | 4,000       | 2,400              |

- Lead time from Taiwan: **8 weeks**
- Target service level: **95%**

## 🧠 Key Concepts

- Risk pooling  
- Safety stock  
- Service level and z-score  
- Demand aggregation  
- Normal distribution

## 🛠️ Tools Used

- Microsoft Excel  
- Statistical functions (`NORM.INV`, `SQRT`, etc.)

## 📁 Files Included

- `02_risk-pooling.xlsx`: Spreadsheet comparing decentralized and centralized safety stock levels with full demand data and analysis.

## 👩‍💻 Author

Belén Llatas Beny  
📍 Valencia, Spain  
📧 belenllatas1@gmail.com  
🔗 [Back to portfolio](../README.md)

---

### 📝 Note for Spanish-speaking recruiters 🇪🇸

Este proyecto fue desarrollado como parte del curso de Supply Chain Management en Hofstra University (Nueva York).  
Analiza cómo Epson puede reducir su inventario de seguridad consolidando la distribución de impresoras en Europa.  
El caso original plantea un plazo de entrega de 8 semanas desde la fábrica en Taiwán, y compara la estrategia actual (con montaje local en cada país) con una alternativa centralizada en un DC europeo.  
Si deseas una explicación más detallada o el archivo en español, estaré encantada de ayudarte.
