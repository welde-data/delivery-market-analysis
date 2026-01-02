
# Delivery Market Analysis

The **Delivery Market Analysis** project explores trends, customer preferences, and market dynamics in Belgium’s food delivery industry. It focuses on the performance of three major platforms: **TakeAway**, **UberEats**, and **Deliveroo**.

Using real-world databases, the project delivers actionable insights for both **restaurant partners** and **consumers**. The goal is to support better strategic decisions, improve market positioning, and ultimately enhance the overall user experience.

## Project Highlights

- **Consumer Preferences:** Identifies top-rated restaurants across key food categories, helping users make more informed dining choices.  
- **Platform Comparisons:** Compares TakeAway, UberEats, and Deliveroo across pricing, delivery fees, and the overall **price-to-rating** relationship to highlight strengths and weaknesses.  
- **Regional Trends:** Analyzes geographic patterns across Belgium to uncover service gaps (“dead zones”) and local food preferences.

## 📦 Repo Structure

```text
delivery-market-.../
├─ assets/
├─ data/
│  ├─ databases/
│  ├─ exports-takeaway-...
│  ├─ maps/
│  ├─ deliveroo.db
│  ├─ georef-belgium.ge...
│  ├─ takeaway.db
│  └─ ubereats.db
├─ notebooks/
│  ├─ 00_schema_discove...
│  ├─ Analysis_questions...
│  ├─ CSV_export.ipynb
│  ├─ data_explor.ipynb
│  └─ NiceToHave.ipynb
├─ venv/
├─ .gitignore
├─ README.md
└─requirements

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

## 📊 Visual Insights

<table>
  <tr>
    <td><img src="../assets/price_distribution_by_menu_items.png" width="250"></td>
    <td><img src="../assets/restaurant_distribution.png" width="280"></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="../assets/Top_10_pizza_restaurants_rating.png" width="250"></td>
    <td><img src="../assets/restaurants_ with_Kapsalon_location.png" width="300"></td>
  </tr>
</table>

**Additional Analysis:**

<table>
  <tr>
    <td><img src="../assets/veggie_dishes_distribution.png" width="300"></td>
    <td><img src="../assets/top_hammus_restaurants.png" width="250"></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="../assets/venn_diagram_restaurants.png" width="250"></td>
    <td><img src="../assets/dead_zone.png" width="400"></td>
  </tr>
</table>
<table>
  <tr>
    <td><img src="../assets/average_delivery_fee_postal_code.png" width="300"></td>
    <td><img src="../assets/number_of_restaurants.png" width="250"></td>
  </tr>
</table>

## ⏱️ Project Timeline

- **Initial setup:** completed in **4 days**  

## 👥 Contributors

This project is part of AI & Data Science Bootcamp training at **</becode** and it was done by: 

- Welederufeal Tadege [LinkedIn](https://www.linkedin.com/in/) | [Github](https://github.com/welde2001-bot) 