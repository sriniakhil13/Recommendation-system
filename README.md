# Recommendation-System

Through Collaborative Filtering, popularity and SVD based modelling to recommend amazon electronics to users.

## Dataset Description:
Data is of amazon users.
```
1. UserID: Every users has unique identifier
2. ProductID: Every product has unique indentifier
3. Rating: Rating of the corresponding product by corresponding user on scale 1 to 5
```

## Objective:
Build a recommendation system to recommend products to customers based on the their previous ratings for other products.

## Collaborative Filtering:
```
Here we are using Collaborative Filtering and not content-based recommendation system.

It doesn’t need anything else except users historical preference on a set of items. 
Because it’s based on historical data, the core assumption here is that the users who have agreed in the past tend to also agree in the future. 
In terms of user preference, it usually expressed by two categories. 
1. Explicit Rating, is a rate given by a user for a particular item. Our dataset contains this information.
2. Implicit Rating, suggests users preference indirectly, such as page views, clicks, purchase records.
```

