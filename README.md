# AI-Product-Recommendation-System-

🛍 AI Product Recommendation System
==================================================
📊 Sample Products Dataset:
   product_id              product_name      category  price  \
0           1  Wireless Bluetooth Headphones  Electronics  79.99   
1           2          Smart Fitness Watch   Electronics  199.99   
2           3             Laptop Backpack   Accessories   49.99   
3           4              Wireless Mouse   Electronics   29.99   
4           5         Mechanical Keyboard   Electronics   89.99   

                                         description  
0  High-quality wireless headphones with noise c...  
1  Fitness tracker with heart rate monitoring an...  
2  Durable laptop backpack with multiple compart...  
3  Ergonomic wireless mouse for comfortable use ...  
4  RGB mechanical keyboard with customizable keys...  

Total Products: 10

⭐ Sample Ratings Dataset:
   user_id  product_id  rating
0        1           1       5
1        1           3       4
2        1           5       3
3        1           7       5
4        2           2       4
Total Ratings: 28

============================================================
🤖 AI RECOMMENDATION ENGINE OUTPUT
============================================================

1. COLLABORATIVE FILTERING (User-based)
----------------------------------------

Collaborative Recommendations for User 1
============================================================
1. Smart Fitness Watch
   Category: Electronics
   Price: $199.99
   Score: 4.000 (collaborative - user_based)
   Description: Fitness tracker with heart rate monitoring and GPS...

2. Wireless Mouse
   Category: Electronics
   Price: $29.99
   Score: 3.667 (collaborative - user_based)
   Description: Ergonomic wireless mouse for comfortable use...

3. Smartphone Case
   Category: Accessories
   Price: $19.99
   Score: 3.500 (collaborative - user_based)
   Description: Protective case for smartphones with sleek design...

...

5. NEW USER SCENARIO (Cold Start Problem)
----------------------------------------

Recommendations for New User 100
============================================================
1. Wireless Mouse
   Category: Electronics
   Price: $29.99
   Score: 4.67 (popular - rating_based)
   Description: Ergonomic wireless mouse for comfortable use...

2. Wireless Bluetooth Headphones
   Category: Electronics
   Price: $79.99
   Score: 5.00 (popular - rating_based)
   Description: High-quality wireless headphones with noise c...

3. Smart Fitness Watch
   Category: Electronics
   Price: $199.99
   Score: 4.50 (popular - rating_based)
   Description: Fitness tracker with heart rate monitoring an...

📈 SYSTEM ANALYSIS
----------------------------------------
Total Users: 10
Total Products: 10
Total Ratings: 28
Average Rating: 4.07

Rating Distribution:
  2 stars: 1 ratings
  3 stars: 7 ratings
  4 stars: 11 ratings
  5 stars: 9 ratings

============================================================
✅ RECOMMENDATION SYSTEM IMPLEMENTED SUCCESSFULLY!
============================================================
