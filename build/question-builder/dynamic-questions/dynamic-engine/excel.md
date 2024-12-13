---
description: This article will teach you about the Excel blocks in our Dynamic Engine.
---

# Excel

## What Is an Excel Block?

Excel blocks are functions that use predefined formulas in Microsoft Excel.

The functions perform calculations using specific values, called arguments, in a particular order, or structure. All you need to do is fill in the specific values for each argument.

## The Excel Blocks

There are two kinds of _excel_ blocks you can use in the Dynamic Engine:

1. Financial Function
2. Statistical Function

### Excel: Financial

The **financial function** block supports the following financial functions:

<figure><img src="../../../../.gitbook/assets/Screen Shot 2024-06-04 at 10-51-05 AM-png.webp" alt=""><figcaption></figcaption></figure>

* **DB**: Returns the depreciation of an asset for a specified period using the fixed-declining balance method.
* **DDB**: Returns the depreciation of an asset for a specified period using the double-declining balance method or some other method you specify.
* **EFFECT**: Returns the effective annual interest rate, given the nominal annual interest rate and the number of compounding periods per year.
* **FV**: Calculates the future value of an investment based on a constant interest rate. You can use FV with either periodic, constant payments, or a single lump sum payment.
* **IRR**: Returns the internal rate of return for a series of cash flows
* **NOMINAL**:  Returns the nominal annual interest rate, given the effective rate and the number of compounding periods per year.
* **NPER**: Returns the number of periods for an investment based on periodic, constant payments and a constant interest rate.
* **PMT**: Calculates the payment for a loan based on constant payments and a constant interest rate.
* **PPMT**: Returns the payment on the principal for a given period for an investment based on periodic, constant payments and a constant interest rate.
* **PV**: Calculates the present value of a loan or an investment, based on a constant interest rate. You can use PV with either periodic, constant payments (such as a mortgage or other loan), or a future value that's your investment goal.
* **RATE**: Returns the interest rate per period of an annuity. RATE is calculated by iteration and can have zero or more solutions. If the successive results of RATE do not converge to within 0.0000001 after 20 iterations, RATE returns the #NUM! error value.

{% hint style="info" %}
For specific rules and syntax of financial functions, refer to [Microsoft's Support Page for Financial Functions](https://support.microsoft.com/en-gb/office/financial-functions-reference-5658d81e-6035-4f24-89c1-fbf124c2b1d8)
{% endhint %}

### Statistical Functions

The **statistical function** block supports the following financial functions:

<figure><img src="../../../../.gitbook/assets/Screen Shot 2024-06-04 at 10-52-03 AM-png.webp" alt=""><figcaption></figcaption></figure>

* **CORREL**: Returns the correlation coefficient of two cell ranges. Use the correlation coefficient to determine the relationship between two properties. For example, you can examine the relationship between a location's average temperature and the use of air conditioners.
* **COVARIANCE.P**: Returns population covariance, the average of the products of deviations for each data point pair in two data sets. Use covariance to determine the relationship between two data sets. For example, you can examine whether greater income accompanies greater levels of education.
* **COVARIANCE.S**: Returns the sample covariance, the average of the products of deviations for each data point pair in two data sets.
* **FREQUENCY**: The FREQUENCY function calculates how often values occur within a range of values, and then returns a vertical array of numbers. For example, use FREQUENCY to count the number of test scores that fall within ranges of scores. Because FREQUENCY returns an array, it must be entered as an array formula.
* **INTERCEPT**: Calculates the point at which a line will intersect the y-axis by using existing x-values and y-values. The intercept point is based on a best-fit regression line plotted through the known x-values and known y-values. Use the INTERCEPT function when you want to determine the value of the dependent variable when the independent variable is 0 (zero). For example, you can use the INTERCEPT function to predict a metal's electrical resistance at 0°C when your data points were taken at room temperature and higher.
* **LOGNORMIST**: Returns the lognormal distribution of x, where ln(x) is normally distributed with parameters Mean and Standard\_dev. Use this function to analyze data that has been logarithmically transformed.
* **NORMDIST**: Returns the normal distribution for the specified mean and standard deviation. This function has a very wide range of applications in statistics, including hypothesis testing.
* **SLOPE**: Returns the slope of the linear regression line through data points in known\_y's and known\_x's. The slope is the vertical distance divided by the horizontal distance between any two points on the line, which is the rate of change along the regression line.

{% hint style="info" %}
For specific rules and syntax of financial functions, refer to [Microsoft's Support Page for Statistical Functions](https://support.microsoft.com/en-us/office/statistical-functions-reference-624dac86-a375-4435-bc25-76d659719ffd)
{% endhint %}

***

## Example Question

Consider the following Multiple Choice question in EXAMIND.

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 10.43.46 AM.png" alt=""><figcaption></figcaption></figure>

This question will allow us to use the Declining Balance function Excel Block.

Here is what the Dynamic Engine would look like:

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 10.47.21 AM.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
EXAMIND mirrors the idiosyncratic behaviour that comes with functions in Excel, such as a requirement for a value that is not "0" in the salvage value in the DB example above. You can blame Microsoft for that.
{% endhint %}

Here is what the sample question would look like (values highlighted in blue for convenience):

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 10.44.00 AM.png" alt=""><figcaption></figcaption></figure>
