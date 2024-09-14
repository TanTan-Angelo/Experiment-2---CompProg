# 🌠: Experiment 2 - Computer Programming 🌠:

## :bust_in_silhouette: Author
**Chance Angelo Tan**

## 🔍: Description
This project involves using the **Numpy** library to solve two problems related to data normalization and matrix operations.

## ❔: Intended Learning Outcomes
1. Identify the codes and functions incorporated in the Numpy library📚.
2. Apply and use various codes and functions to create a Python🐍 program using the Numpy library.

## 📝: Instructions
Write a Python script/code in a Jupyter Notebook to address the given problems. You may submit your Jupyter notebook in github and forward the link to the appropriate submission bin in Canvas.

### 🧙: Normalization Problem
Normalization is a fundamental preprocessing technique in data analytics involving centering and scaling. Centering is done by subtracting the data from the mean, and scaling is achieved by dividing by the standard deviation. Mathematically, normalization is expressed as:

\[ Z = \frac{X - \bar{x}}{\sigma} \]

where \( \bar{x} \) is the mean and \( \sigma \) is the standard deviation.

**My answer to Question 1 was formulated due to the following reasons:**

1. **Generate Random Array**💹: I used `np.random.random((5,5))` to create a `5 x 5` ndarray with random values. This function provides a diverse set of values which is useful for normalization.
2. **Calculate Mean and Standard Deviation**📏 : By calculating the mean and standard deviation with `x.mean()` and `x.std()`, I was able to center and scale the data.
3. **Normalize the Array** ➡️: Normalizing involves subtracting the mean from each element and then dividing by the standard deviation, which transforms the data to have a mean of 0 and a standard deviation of 1.


### 3️⃣: Divisible by 3 Problem
1. Create a `10 x 10` ndarray where each element is the square of the first 100 positive integers.
2. Determine all elements divisible by 3.
3. Save the result as `div_by_3.npy`.

## 📖: Author
-  Chance Angelo Tan
