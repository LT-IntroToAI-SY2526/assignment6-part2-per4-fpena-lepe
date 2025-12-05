# Assignment 6 Part 2 - Writeup

---

## Question 1: Feature Importance

Based on your house price model, rank the four features from most important to least important. Explain how you determined this ranking.

**YOUR ANSWER:**
1. Most Important: Bedrooms
2. Bathrooms
3. Age
4. Least Important: Squarefeet

**Explanation:**
To find out which feature was the most important, I looked at the coefficients in front of each of the variables in the terminal because it was printed from most to least important and the coefficients were shown. The most important variable is bedrooms because that is what affects the price the most. A larger coefficient means the model changes more when the feature changes, so it has a larger impact.



---

## Question 2: Interpreting Coefficients

Choose TWO features from your model and explain what their coefficients mean in plain English. For example: "Each additional bedroom increases the price by $___"

**Feature 1:**
Bedrooms: each additional bedroom in the house increases the price by $6649

**Feature 2:**
Each additional bathroom increases the predicted house price by  $3859

=== Feature Importance ===
1. Bedrooms: 6648.9741
2. Bathrooms: 3858.8966
3. Age: 950.3509
4. SquareFeet: 121.1137

## Question 3: Model Performance

What was your model's R² score? What does this tell you about how well your model predicts house prices? Is there room for improvement?

**YOUR ANSWER:**
R² Score: 0.9936
It means that the model explains 99.36% of the variation in house prices. This means the model fits the training and testing data very well. There is technically slight room for improvement, the other 0.64% could be explained by location, neighborhood and other variables.

---

## Question 4: Adding Features

If you could add TWO more features to improve your house price predictions, what would they be and why?

**Feature 1:**
Location (neighborhood or ZIP code)

**Why it would help:**
The location of a house is one of the biggest factors affecting its price. Homes in highly desirable neighborhoods or near good schools tend to cost more, while houses in less popular areas sell for less.

**Feature 2:**
Lot Size  square feet of the FULL property

**Why it would help:**
The size of the property itself can significantly impact price. Even if two houses have the same square footage inside, a larger lot size could give more space for expansion (like a pool or something).

---

## Question 5: Model Trust

Would you trust this model to predict the price of a house with 6 bedrooms, 4 bathrooms, 3000 sq ft, and 5 years old? Why or why not? (Hint: Think about the range of your training data)

**YOUR ANSWER:**
I would not fully trust this model to predict a house with those variables. This is because a lot of those variables are outside of the training data for the model. If you predict a house with variables far off from the training data your prediction would likely be unreliable.

