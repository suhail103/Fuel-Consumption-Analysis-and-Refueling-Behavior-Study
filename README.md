# Fuel Consumption Analysis and Refueling Behavior Study

This project analyzes **global fuel consumption patterns**, **vehicle fuel efficiency**, and **consumer refueling behavior** using a large, crowdsourced dataset.  
The study includes both a **global analysis** and a focused look at **South African fuel price behavior**, providing insights into efficiency trends and consumer decisions.

---

## 🚀 Project Overview
The dataset contains refueling logs with details such as:
- Dates of refueling and data capture  
- Vehicle odometer readings  
- Gallons filled and total cost  
- Currency information (proxy for country)  
- Vehicle make, model, and year  

The project explores:
1. **Global Vehicle Fuel Efficiency**  
   - Identifying popular vehicles and their efficiency levels.
   - Understanding seasonal variations in fuel consumption.
   - Detecting outliers and unrealistic entries.

2. **South African Refueling Behavior**  
   - Examining how weekly fuel price changes affect consumer behavior.
   - Comparing refueling activity before and after price adjustments.
   - Visualizing patterns in fuel price trends over time.

---

## 🛠️ Key Steps
- **Data Cleaning**
  - Handling invalid dates, missing values, and inconsistent formats.
  - Standardizing units (gallons → litres, miles → kilometres).
  - Extracting clean numeric values for calculations.

- **Feature Engineering**
  - Creating new columns like litres per 100 km (L/100km) for standardized fuel efficiency.
  - Extracting vehicle attributes and user identifiers from raw URLs.

- **Analysis and Visualization**
  - Plotting distributions, trends, and correlations.
  - Detecting outliers for cleaner, more reliable results.

- **Machine Learning**
  - Using Random Forest to identify factors influencing fuel efficiency.
  - Highlighting risks of data leakage in predictive modeling.

---

## 📊 Key Findings
- Plug-in hybrids dominate fuel efficiency rankings globally, while small budget cars are most efficient in South Africa.  
- Seasonal trends show higher fuel consumption during winter months.  
- In South Africa, refueling activity spikes **fourfold before price increases**, showing strong anticipatory behavior.

---

## 🗂 Repository Structure
