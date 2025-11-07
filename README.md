# 🧠 Project 2 - Data Wrangling and Business Logic

### 🏢 Project Context
In this second stage of the **Store 1** project, you continue your role as a junior data professional, building on the foundation from **Project 1 - Data Cleaning and Exploration**.  

The company now aims to gain deeper insights into **customer behavior and purchasing trends** over time to design more personalized marketing campaigns.  

---

### 🎯 Objectives
- Automate the cleaning and transformation process from Project 1 by using **custom functions**.  
- Standardize customer data, including names, ages, and purchase categories.  
- Calculate **total company revenue** and identify **loyal customers** (total spending > $1500).  
- Apply **loops, conditionals, and functions** to process customer lists efficiently.  
- Extract business insights such as:
  - Customers under 30 years old.
  - Customers spending more than $1000.
  - Customers who purchased items from a specific category (e.g. “clothes”).

---

### ⚙️ Technical Tasks

#### 🧩 Step 1 – Create the `clean_user()` Function
Encapsulate cleaning logic into a reusable function:
- Remove spaces and underscores from names.  
- Convert ages to integers.  
- Split names into sublists `[first_name, last_name]`.  
- Normalize text to lowercase.  

#### 🔠 Step 2 – Normalize Categories
Convert all category names from uppercase to lowercase, storing them in a new list `fav_categories_low`.

#### 🔁 Step 3 – Iterate over All Users
Create a new list `users_categories_low` containing all users with lowercase categories.

#### 🧼 Step 4 – Integrate Category Cleaning
Extend `clean_user()` to include category normalization and apply it to the full user list.

#### 💵 Step 5 – Compute Total Company Revenue
Iterate through each customer’s spending list and sum all values to calculate total revenue.

#### 🎁 Step 6 – Identify Loyal Customers
Simulate new purchases using a `while` loop with random amounts between 30 and 80 until the total spending exceeds $1500.

#### 👶 Step 7 – Filter by Age
Display the names of all customers younger than 30 years.

#### 💰 Step 8 – High-Value Young Customers
Print names of customers under 30 with total spending above $1000.

#### 👕 Step 9 – Filter by Category
List the names and ages of customers who purchased items from the **"clothes"** category.

#### 🧮 Step 10 – Define `get_client_by_cat()`
A function that returns key information for customers filtered by a given category:

**Parameters:**
- `users`: List of all user records.  
- `id_index`, `name_index`, `age_index`, `category_index`, `amounts_index`: Indices for specific fields.  
- `filter_category`: Category name to filter by.  

**Returns:**
A list of sublists with:
1. Client ID  
2. `[first_name, last_name]`  
3. Age  
4. Total amount spent  

---

### 🧰 Tools and Technologies
- 🐍 **Python 3**
- 📓 **Jupyter Notebook**
- 🧮 **Lists**, **Loops**, **Conditionals**, **Functions**
- 🎯 **Data Cleaning**, **Iteration**, **Business Rule Automation**

---

### 🚀 Results
- Implemented a **fully functional data-wrangling pipeline** using pure Python.  
- Generated business insights about customer behavior and loyalty.  
- Structured reusable functions for future analytics and reporting pipelines.

---

### 🔍 Next Steps
In upcoming stages, Store 1 will integrate these cleaned and enriched datasets into a **data visualization dashboard** to support decision-making in marketing and customer retention.

---

### 👨‍💻 Author
**Diego Francisco Domínguez Aguilar**  
*Data Science Bootcamp – TripleTen (2025)*  
📧 [Connect on LinkedIn](https://www.linkedin.com/in/tu-url-aqui)
