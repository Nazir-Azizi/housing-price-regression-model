# Housing Price Prediction with multiple features

This project uses **Multiple Linear Regression(Linear Regression with Multiple features)** to predict house price based on size in square meters and number of bedrooms.
It simulates a real state agency that can help people buy houses.

---

## Project Overwiew

As a real state agent, you want to predict house prices accurately.
You already have the following data available:

- **Size (square meter)**
- **Number of bedroons**

By training a multiple linear regression model on this data, you can predict the price of the house.

---

## Machine Learning Concept

This project demonstrates a simple but powerful concept:
> The relationship between **size of a house**, **number of bedrooms** and **price of the house** can be modeled using a straight line in 3 dimensional space (mulitple linear regression)

Equation used:
\[
house_price = `θ_2` x house_size + `θ_1` x bedroom_number + `θ_0`
\]

The model learns parameters `θ_2`, `θ_1` and `θ_0` using **gradient descent** method.

---

## Tech Stack

- **Language:** Python
- **Libraries:** NumPy
- **Algorithm:** Multiple Linear Regression (Supervised Learning)
