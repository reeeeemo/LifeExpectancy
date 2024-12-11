# Final Project for CSCA 5622: Supervised Learning
## What is this Project?
This is a project that takes a user's current age, and gender (optional), and outputs their predicted life expectancy.

## What is the algorithm / task?
This uses a **Polynomial Regression** algorithm, that is fit upon data gained from **Statistics Canada** about [Life Expectancy across Canada](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1310083701)

This algorithm also uses weights to lessen the impact of COVID-19 for the years of 2020-2022, for more accuracy.

## Why create another Life Expectancy Algorithm?
I actually used this in a larger project (unrelated to my final assignment), you can find it [here](https://github.com/reeeeemo/GBLC). This project took your age, gender, and initial investment, and returned a inflation-adjusted return when you invest into Canadian government bonds over your lifespan.

This project used this algorithm alongside 2 targeted monte-carlo simulations to create predictions for the future life expectancy, inflation, and government bond prices in Canada.

**Why only Polynomial Regression for this assignment then?**
It was a great experience to come back to multi-linear regression and explore polynomial regression a little deeper. I felt like I only scratched the surface of what it was, and after this course I explored the idea of modifying the algorithm to get a more accurate result!