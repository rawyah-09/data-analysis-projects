# Market Basket Analysis
This assignment uses supermarket data from kaggle link of the data :(https://www.kaggle.com/code/kirollosashraf/apriori-algorithm-on-mba-market-basket-analysis/input ) the objective Using Apriori model and Association Rule Learning techniques to identify relationships between items purchased in customer transactions. the number of rows and columns: (522064, 7) and there are missing values, we found Missing Values: BillNo (0) ,Itemname (1455) ,Quantity (0) ,Date (0) ,Price (0) CustomerID (134041) ,Country (0) we dropped rows of missing values , and duplicate data .

after prepared data we moved to Using Apriori model and Association Rule and we got Top 5 Discovered Rules: 1.Rule: Antecedent: 60 Teatime Fairy Cake Cases Consequent: Pack of 72 Retrospect Cake Cases Support: 0.0617 Confidence: 0.6495 Lift: 4.45 Real-World Application: Customers who purchase one type of cake cases are likely to buy another type. This suggests potential for bundling cake case sets.

2.Rule: Antecedent: Alarm Clock Bakelike Red Consequent: Alarm Clock Bakelike Green Support: 0.0607 Confidence: 0.6868 Lift: 9.25 Real-World Application: Customers who buy one color of the alarm clock tend to buy another color. Offering promotions for multiple colors or "buy one, get one in a different color" could increase sales.

3.Rule: Antecedent: Alarm Clock Bakelike Green Consequent: Alarm Clock Bakelike Red Support: 0.0607 Confidence: 0.8182 Lift: 9.25 Real-World Application: Similar to the previous rule, but in reverse. Cross-selling strategies for the alarm clocks in different colors would be beneficial.

4.Rule: Antecedent: Alarm Clock Bakelike Pink Consequent: Alarm Clock Bakelike Red Support: 0.0512 Confidence: 0.7746 Lift: 8.76 Real-World Application: Pink and red alarm clocks are often purchased together. Offering a "color combo" discount could boost sales.

5.Rule: Antecedent: Baking Set Spaceboy Design Consequent: Baking Set 9 Piece Retrospect Support: 0.0559 Confidence: 0.8219 Lift: 6.15 Real-World Application: Different baking sets are frequently bought together, indicating an opportunity for bundling similar baking products.
