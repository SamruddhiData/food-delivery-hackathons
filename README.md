# food-delivery-hackathons
Food delivery data analysis project using Python and Pandas. Data merged from CSV, JSON, and SQL sources to analyze user behavior, revenue trends, cuisine performance, and membership impact.
# 🍔 Food Delivery Data Analysis – Hackathon Project

This project focuses on analyzing a food delivery dataset by integrating data from multiple sources and deriving meaningful business insights.

---

## 📂 Datasets Used

1. **orders.csv**
   - Contains transactional order-level data
   - Includes order date, total amount, user ID, and restaurant ID

2. **users.json**
   - Contains user master data
   - Includes user ID, city, and membership type (Gold / Regular)

3. **restaurants.sql**
   - Contains restaurant master data
   - Includes restaurant ID, cuisine type, city, and rating

---

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- SQLite
- Jupyter Notebook

---

## 🔗 Data Integration Logic

- `orders.csv` is LEFT JOINED with `users.json` using **user_id**
- Resulting dataset is LEFT JOINED with `restaurants.sql` using **restaurant_id**
- LEFT JOIN ensures all orders are retained

---

## 📊 Key Analysis Performed

- Total orders by Gold vs Regular members
- City-wise revenue analysis
- Cuisine-wise average order value
- Rating vs revenue analysis
- Quarterly revenue trends
- High-value customer identification

---

## 📁 Final Output

- `final_food_delivery_dataset.csv`  
  Consolidated dataset containing order, user, and restaurant details.

---

## 📓 Notebook

- **Food_Delivery_Analysis.ipynb**
  - Complete data loading
  - Data merging logic
  - Analysis and answers for MCQs and numerical questions
  - Reproducible results

---

## ✅ How to Run

1. Clone the repository
2. Open the Jupyter Notebook
3. Ensure all dataset files are in the same directory
4. Run cells sequentially

---

## 📌 Author
**Samruddhi Gunjal**

