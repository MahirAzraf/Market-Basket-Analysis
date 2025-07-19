
🛒 Market Basket Analysis with Apriori Algorithm
Welcome to my Market Basket Analysis project!
This project analyzes transactional retail data using the Apriori algorithm to uncover frequent itemsets and association rules — insights that can help with product bundling, cross-selling, and recommendation systems.

📂 Dataset
Source: Real-world retail dataset (Excel/CSV format)

Rows: 500,000+ transactions

Columns:

BillNo: Invoice number

Itemname: Product name

Quantity: Number of items purchased

Date: Purchase date & time

Price: Price per item

CustomerID: Unique customer identifier

Country: Country of the customer

🛠️ Tools & Libraries Used
Python (Pandas, NumPy, Matplotlib, Seaborn)

mlxtend for Apriori and association rules

Google Colab for implementation

🔍 Project Workflow
1. Data Cleaning & Preprocessing
Removed missing values (Itemname, CustomerID)

Corrected Price format (from comma , to dot . for float)

Filtered out negative or zero values

Converted dates to datetime format

2. Transaction Encoding
Grouped transactions by BillNo

Converted into a basket matrix of 0s and 1s (one-hot encoding)
Example:

mathematica
Copy
Edit
BillNo | Item A | Item B | Item C  
 10001 |   1    |   0    |   1
3. Frequent Itemset Mining
Applied Apriori algorithm with a minimum support threshold

Found combinations of products that are often bought together

4. Association Rule Generation
Extracted rules with metrics:

Support

Confidence

Lift

Conviction, Leverage, Jaccard, and more

Focused on high-confidence and high-lift rules for interpretation

5. Country-wise Analysis
Filtered transactions by country (e.g., UK, Germany)

Repeated analysis to discover regional buying patterns

📈 Visualizations
Bar Charts of top product associations (by lift or confidence)

Easy-to-understand graphs showing strong item relationships

Focused on visual clarity so non-technical viewers can understand too

🌟 Key Insights
Strong lift (17+) found between Green Regency Teacup and Pink Regency Teacup

Multi-item combinations revealed popular bundles

Product pairings vary across different countries — showing potential for localized marketing

✅ Business Applications
🛍️ Product bundling strategies

🔁 Upselling & cross-selling

🧠 Personalized recommendations

🌍 Country-specific marketing strategies

💼 About Me
I'm a beginner data scientist passionate about applying data to real-world problems.
This is part of my journey to build a strong portfolio and land exciting roles in Data Science, Analytics, or AI.

🔗 Project Notebook
You can view the full project in the Jupyter/Colab Notebook here.
(Replace with your actual GitHub or Colab link)

📬 Let's Connect
If you found this useful or want to collaborate, feel free to connect with me on LinkedIn or check out more projects on my GitHub!

