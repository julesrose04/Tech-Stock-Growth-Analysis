# Tech-Stock-Growth-Analysis
Analyzed top stock companies performance from March 2024-2025. We use `curve_fit` in SciPy to find the best fit parameters for our data.

The functions we used for growth over time is the continuous compounding function: 
$$
A(t) = A_0 \cdot e^{rt}
$$

Where, 

A = starting value (initial stock price)

r = growth rate

t = time (in days)

As well as 7 day log returns to quantify the high performing stocks in a single 7 day period

$$
\text{7-Day Log Return}_t = \sum_{i=0}^{6} \ln\left(\frac{P_{t-i}}{P_{t-i-1}}\right)
$$

