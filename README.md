# statistical-arbitrage
 Statistical arbitrage is a quantitative finance strategy used by traders to profit from pricing inefficiencies between related financial instruments

# Steps for [Augmented Dickey Fuller Test] (ADF_Test.ipynb)

1. **Understand the Problem**: 
    The ADF test helps us figure out if a time series data (like stock prices over time) behaves predictably or not. If it behaves predictably, it's called stationary; otherwise, it's non-stationary.

2. **Formulate Hypotheses**:
   - **Null Hypothesis (H0)**: The data has a unit root, meaning it's non-stationary (not predictable).
   - **Alternative Hypothesis (H1)**: The data doesn't have a unit root, meaning it's stationary (predictable).

3. **Collect Data**: 
    Get your time series data ready. This could be anything that changes over time, like daily temperatures or monthly sales figures.

4. **Calculate Test Statistic**: 
    The ADF test crunches numbers to give us a test statistic. It's like a special number that helps us decide if our data is stationary or not.

5. **Compare with Critical Values**: 
    We compare the test statistic with some critical values. These are like benchmarks that tell us if our test statistic is big or small enough to reject the null hypothesis.

6. **Make a Decision**:
   - If our test statistic is smaller than the critical value, we reject the null hypothesis. It means our data is predictable (stationary).
   - If our test statistic is bigger than the critical value, we can't reject the null hypothesis. It suggests our data is not predictable (non-stationary).

7. **Interpretation**: 
    If we reject the null hypothesis, we conclude that our data is stationary, which is good for making predictions. If we can't reject it, our data is non-stationary, which means it's harder to predict future values accurately.

Remember, the ADF test helps us understand the behavior of our data over time, which is crucial for making informed decisions in various fields like economics, finance, and climate science.

