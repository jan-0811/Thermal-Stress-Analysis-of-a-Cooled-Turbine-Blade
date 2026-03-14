# Thermal-Stress-Analysis-of-a-Cooled-Turbine-Blade

This project presents a **thermal and structural analysis of a cooled turbine blade** using a simplified computational approach. Turbine blades in gas turbines operate under extremely high temperatures, and **internal cooling passages are used to reduce thermal loads**. However, temperature gradients between the hot external surface and the cooled interior generate **thermal stresses**, which may lead to material failure.

The objective of this project is to simulate the **temperature distribution and thermal stresses** in a turbine blade with internal cooling passages.

---

## 🔍 Project Overview

- Modeling of a **turbine blade with 10 internal cooling passages**
- Simulation of **heat transfer between blade and coolant**
- Implementation of a **reduced-order thermal-fluid model** for efficient computation
- Coupled **steady-state thermal and structural analysis**
- Evaluation of **temperature distribution, fluid temperature rise, and von Mises stress**

---

## ⚙️ Modeling Approach

- The coolant flow inside each passage is treated as **one-dimensional flow**
- Heat transfer between the blade and coolant is modeled using **empirical convection film coefficients**
- Cooling passages are modeled using **FLUID116 elements**
- The turbine blade solid region is modeled using **SOLID278 elements**
- The external blade surface is maintained at a **constant temperature boundary condition**

---

## 🧪 Simulation Setup

- **10 cooling holes** with different mass flow rates and inlet temperatures
- Convection-based heat transfer between the blade and coolant
- Steel blade material with defined thermal and mechanical properties
- Linked **steady-state thermal analysis and static structural analysis**

---

## 📊 Results

The simulation provides:

- Temperature distribution in the **solid blade**
- Temperature rise in the **coolant flow**
- Temperature variation along cooling passages
- **Von Mises stress distribution** due to thermal loads

### Key Observations

- Blade temperature is **lower near cooling passages**
- Coolant temperature **increases along the flow path**
- Maximum stresses occur near **hole number 10**

---

## 📈 Summary of Results

| Result Type | Value |
|--------------|------|
| Solid Region Temperature (max) | 568 K |
| Solid Region Temperature (min) | 338.29 K |
| Fluid Temperature (max) | 562.32 K |
| Fluid Temperature (min) | 333.99 K |
| Solid Surface Temperature (max) | 562.62 K |
| Solid Surface Temperature (min) | 338.29 K |
| Maximum Von Mises Stress | 2.7959 × 10⁹ Pa |

---

## 🚀 Applications

This project demonstrates how simplified thermal-fluid modeling can be used to:

- Predict **thermal stresses in turbine components**
- Study the **effectiveness of cooling designs**
- Reduce computational cost compared to **full CFD simulations**



