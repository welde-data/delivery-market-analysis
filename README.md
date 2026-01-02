# Delivery Market Analysis (Belgium)

The **Delivery Market Analysis** project explores trends, customer preferences, and market dynamics in Belgium’s food delivery industry. It focuses on the performance of three major platforms: **TakeAway**, **UberEats**, and **Deliveroo**.

Using real-world databases, the project delivers actionable insights for both **restaurant partners** and **consumers**. The goal is to support better strategic decisions, improve market positioning, and ultimately enhance the overall user experience.

## Project Highlights

- **Consumer Preferences:** Identifies top-rated restaurants across key food categories, helping users make more informed dining choices.  
- **Platform Comparisons:** Compares TakeAway, UberEats, and Deliveroo across pricing, delivery fees, and the overall **price-to-rating** relationship to highlight strengths and weaknesses.  
- **Regional Trends:** Analyzes geographic patterns across Belgium to uncover service gaps (“dead zones”) and local food preferences.

## 📦 Repo Structure

```text
delivery-market-analysis/
├── data/
│   ├── exports/
│   ├── deliveroo.db
│   ├── takeaway.db
│   └── ubereats.db
├── notebooks/
│   ├── 00_schema_di…     (notebook)
│   ├── Analysis_quest…   (notebook)
│   ├── CSV_export.ip…    (notebook)
│   ├── data_explor.ip…   (notebook)
│   └── NiceToHave…       (notebook)
├── venv/
├── .gitignore
└── README.md

```
# 🎯 Must-have Features

## Key Business Questions

- What is the price distribution of menu items?
- What is the distribution of restaurants per location?
- Which are the top 10 pizza restaurants by rating?
- Map locations offering kapsalons and their average price.

## Additional Questions

- How do delivery fees vary across platforms and locations?
- Which restaurants have the best price-to-rating ratio?
- Where are the delivery “dead zones” — areas with minimal restaurant coverage?
- How does the availability of vegetarian and vegan dishes vary by area?
- How do ratings of similar restaurants differ across Uber Eats, Deliveroo, and Takeaway?

All of the questions above are addressed in this analysis.

## ⏱️ Project Timeline

- **Initial setup:** completed in **4 days**  
- **Context:** developed as part of my **7-month AI & datascience training bootcamp** at **BeCode (Ghent, Belgium)**