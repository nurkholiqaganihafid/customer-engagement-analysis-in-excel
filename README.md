<div id="top"></div>

# 📌Customer Engagement Analysis in Excel
- In 2022, **_365 company_** has high expectations for growth and student engagement by introducing new features such as an XP system, rewards, leaderboards, and an expanded course library.

- **This analysis aims** to determine whether the addition of these features has succeeded in increasing student engagement on the platform.

- **The results** of this analysis are expected to provide important insights into customer engagement strategies and future company success.

- The following information about column values: [Click here](#)

- Project content:
  - Descriptive Statistics
  - Confidence Intervals
  - Hypothesis Testing

# 📌Outline
- [Business Questions](#business-questions)
- [Results](#results)
  - [Descriptive Statistics](#descriptive-statistics)
    - [1st Question](#1st-question)
    - [2nd Question](#2nd-question)
  - [Confidence Intervals](#confidence-intervals)
    - [3rd Question](#3rd-question)
  - [Hypothesis Testing](#hypothesis-testing)
    - [4th Question](#4th-question)
    - [5th Question](#5th-question)
- [Conclusions](#conclusions)

# 🎯Business Questions
[👆](#outline)
Business questions that will be answered through this data analysis include:
1. How does their engagement compare between the two periods, Q4 2021 and Q4 2022? Calculate the **mean, median, and standard deviation** for these groups. Is there a difference in interactions between paid and free plan customers?
2. Calculate the skewness and kurtosis of students who watched content in Q4 2021 and Q4 2022. Consider paid- and free-plan students. Does the result contradict the mean and median values previously obtained?
3. For both groups, namely, students who have not subscribed to a paid plan and students who have subscribed to a paid plan, determine the minute interval at which you can be 95% confident that a randomly selected individual will be situated.
4. The null hypothesis should include the following: Is engagement (minutes watched) in **Q4 2021 higher or the same as engagement in Q4 2022** for free-plan students and paying students:
    - Comment on the results of committing a Type I or a Type II error in this study.
    - Which one would result in higher costs for the company?
5. The null hypothesis should include the following: The engagement (minutes watched) in **the US is higher than or equal to that in India** `(μ1 ≥ μ2)` or **the US is lower than that in India** `(μ1 < μ2)`. Test only free-plan students.
    - Is the engagement in the US higher than that in India?

# 🎯Results
## 📈Descriptive Statistics
### 1st Question
[👆](#outline)
How does their engagement compare between the two periods, Q4 2021 and Q4 2022? Calculate the **mean, median, and standard deviation** for these groups. Is there a difference in interactions between paid and free plan customers?

- Paid-plan Students
<p align="center">
  <img alt="Paid-plan Students" title="Paid-plan Students" src="https://github.com/nurkholiqaganihafid/customer-engagement-analysis-in-excel/assets/89395541/0c7317dc-20b2-4917-89f8-9b1e953c2660" width="750">
</p>

> **Mean**: Among students who watched between 1 and 100 minutes in 2021, the average minutes watched by paid-plan students increased significantly from Q4 2021 to Q4 2022, from approximately 33.80 minutes to about 273.02 minutes.

> **Median**: The median minutes these low-engagement-paid-plan students watched increased from Q4 2021 to Q4 2022, from 26.33 minutes to 40.28 minutes.

> **Standard Deviation**: The standard deviation for these low-engagement-paid-plan students increased substantially from 28.21 minutes in Q4 2021 to 854.58 minutes in Q4 2022. This indicates a much larger variability in the minutes watched by these students in Q4 2022 compared to Q4 2021.

- Free-Plan Students
<p align="center">
  <img alt="Free-Plan Students" title="Free-Plan Students" src="https://github.com/nurkholiqaganihafid/customer-engagement-analysis-in-excel/assets/89395541/ec6623c5-f8ad-4085-a8dc-03b51fcbdc01" width="750">
</p>

> **Mean**: Among students who watched between 1 and 100 minutes in 2021, the average minutes watched by free-plan students increased from about 25.39 minutes in Q4 2021 to about 117.64 minutes in Q4 2022.

> **Median**: Interestingly, the median minutes watched by these low-engagement-free-plan students decreased from Q4 2021 to Q4 2022, from 14.17 minutes to 11.83 minutes.

> **Standard Deviation**: The standard deviation for the low-engagement-free-plan students increased from 26.23 minutes in Q4 2021 to 468.93 minutes in Q4 2022.

### 2nd Question
[👆](#outline)
Calculate the skewness and kurtosis of students who watched content in Q4 2021 and Q4 2022. Consider paid- and free-plan students. Does the result contradict the mean and median values previously obtained?

> **Skewness** is a fundamental measure of probability distribution asymmetry in a dataset. It reveals whether the observations are concentrated more on one side of the distribution. This metric helps us understand how the data deviates from a normal distribution and provides insights into its underlying structure. A positive skewness value (higher than 0) indicates a right-skewed distribution, while a negative skewness value (lower than 0) points to a left-skewed distribution. A symmetrical distribution has a skewness value of 0, indicating a balanced data spread around the mean.

> **Kurtosis** measures the degree of tailedness—the weight of the tails relative to the rest of the distribution. In other words, it shows how much of the data is in the tails compared to the center. Located farthest from the center, the tails represent the regions where data points are more dispersed—suggesting the presence of more extreme values. If a distribution is heavy-tailed—i.e., more data in the tails—it exhibits high kurtosis. Meanwhile, a low kurtosis occurs when the data is more evenly distributed between the tails and the center or the distribution is light-tailed.

- Paid-plan Students
<p align="center">
  <img alt="Paid-plan Students" title="Paid-plan Students" src="https://github.com/nurkholiqaganihafid/customer-engagement-analysis-in-excel/assets/89395541/875743bb-904a-4ff9-bd87-f38171b398d0" width="750">
</p>

> The skewness increased from 0.63 in Q4 2021 to 7.07 in Q4 2022.

> The kurtosis increased from -0.85 in Q4 2021 to 58.48 in Q4 2022.

- Free-Plan Students
<p align="center">
  <img alt="Free-Plan Students" title="Free-Plan Students" src="https://github.com/nurkholiqaganihafid/customer-engagement-analysis-in-excel/assets/89395541/cf04385d-480e-481e-ab32-592e02830cd3" width="750">
</p>

> The skewness for free-plan students increased from 1.17 in Q4 2021 to 15.06 in Q4 2022, indicating positive skewness.

> The kurtosis increased from free-plan students—from 0.36 in Q4 2021 to 315.76 in Q4 2022. 

> **In both cases**, the mean is higher than the median (33.80 > 26.33 in 2021 and 273.02 > 40.28 in 2022). As a result, the mean is no longer a good central tendency indicator, and it cannot accurately reflect the typical value of the dataset. Note that skewness tells us the direction of outliers but doesn’t indicate the number that occurs.

## 📈Confidence Intervals
### 3rd Question
[👆](#outline)
For both groups, namely, students who have not subscribed to a paid plan and students who have subscribed to a paid plan, determine the minute interval at which you can be 95% confident that a randomly selected individual will be situated.

- Paid-Plan Students
<p align="center">
  <img alt="Paid-Plan Students" title="Paid-Plan Students" src="https://github.com/nurkholiqaganihafid/customer-engagement-analysis-in-excel/assets/89395541/fd49c833-ab7e-41a6-9372-43e9506ecd2a" width="750">
</p>

> For paid-plan students, there's an increase in engagement from Q4 2021 to Q4 2022. The confidence interval for the average minutes watched by paid-plan students increased from Q4 2021 (316.25 to 348.76 minutes) to Q4 2022 (351.91 to 384.72 minutes). This suggests that we can be 95% confident that the true average minutes watched by all paid-plan students in the population increased from Q4 2021 to Q4 2022.

- Free-Plan Students
<p align="center">
  <img alt="Free-Plan Students" title="Free-Plan Students" src="https://github.com/nurkholiqaganihafid/customer-engagement-analysis-in-excel/assets/89395541/baf97846-c35f-403b-a872-1d0ac334924a" width="750">
</p>

> Among free-plan students, there's a decrease in engagement from Q4 2021 to Q4 2022. The confidence interval for the average minutes watched decreased from Q4 2021 (129.92 to 137.95 minutes) to Q4 2022 (67.71 to 70.59 minutes). We then can be 95% confident that the true average minutes watched by all free-plan students in the population decreased from Q4 2021 to Q4 2022.

## 📈Hypothesis Testing
### 4th Question
[👆](#outline)
The null hypothesis should include the following: Is engagement (minutes watched) in **Q4 2021 higher or the same as engagement in Q4 2022** for free-plan students and paying students: Comment on the results of committing a Type I or a Type II error in this study. Which one would result in higher costs for the company?

- Paid-Plan Students
<p align="center">
  <img alt="Paid-Plan Students" title="Paid-Plan Students" src="https://github.com/nurkholiqaganihafid/customer-engagement-analysis-in-excel/assets/89395541/3de32659-7f21-40dc-a5f1-b5dbefff9dc5" width="750">
</p>

> **Reject**  because the calculated **t-statistic** is **lower than** the **critical value**.

- Free-Plan Students
<p align="center">
  <img alt="Free-Plan Students" title="Free-Plan Students" src="https://github.com/nurkholiqaganihafid/customer-engagement-analysis-in-excel/assets/89395541/06fcd9f5-ad34-45cc-b62a-871e5cf8d211" width="750">
</p>

> **Fail to Reject** because the calculated **t-statistic** is **higher than** the **critical value**.

### 5th Question
[👆](#outline)
The null hypothesis should include the following: The engagement (minutes watched) in **the US is higher than or equal to that in India** `(μ1 ≥ μ2)` or **the US is lower than that in India** `(μ1 < μ2)`. Test only free-plan students.
  - Is the engagement in the US higher than that in India?

<p align="center">
  <img alt="Hypothesis test between US and India" title="Hypothesis test between US and India" src="https://github.com/nurkholiqaganihafid/customer-engagement-analysis-in-excel/assets/89395541/f120e699-3962-4612-9f35-99268712dd30" width="750">
</p>

> **Fail to Reject**  because the calculated **t-statistic** is **higher than** the **critical value**.

<p align="center">
  <img alt="t-Test US and India" title="t-Test US and India" src="https://github.com/nurkholiqaganihafid/customer-engagement-analysis-in-excel/assets/89395541/f71d7745-34ea-4c67-bf86-00c06c08978e" width="750">
</p>

> **Fail to Reject**  because the **p-value** is **higher than** the **specified significance level α** (0.05).

# 📚Conclusions
- Conclusions
  - On average, low-engagement-paid students initially increased their watching time more significantly than the free-plan students from Q4 2021 to Q4 2022. This could suggest that paid-plan students find more value in the platform, possibly due to premium features or content that are available to them.In contrast, the median watch time decreased for free-plan students, suggesting that the typical free-plan student in this group did not increase their engagement. This discrepancy might indicate that the strategies or features designed to increase engagement are more effective for paid-plan students. It could also suggest that the monetary investment leads to increased usage due to a desire to get their money's worth.

  - The increase in skewness and kurtosis in both groups from Q4 2021 to Q4 2022 indicates a significant increase in the number of students who watch more content than the majority of students. This is especially true for **free-plan students**, who had **higher** skewness and kurtosis in Q4 2022 **than** **paid-plan students**.

  - Students with a paid-plan subscription watch substantially more than those without. The confidence interval for the average minutes watched in Q4 2022 was 61.71 to 70.59 minutes for free-plan students and 351.99 to 384.72 minutes for paid-plan students. We then can be 95% confident that paid-plan students watched significantly more minutes than free-plan students in Q4 2022. This aligns with the expectation that paid-plan students who have invested in the platform tend to be more engaged than free-plan users.

  - **A Type I error (false positive)** occurs when you reject the null hypothesis, which is true. This would mean concluding that engagement in 2022 is higher when it's not. The probability of making this error is the level of significance, α. **A Type II error (false negative)** occurs when you fail to reject the null hypothesis, but it’s false. In our case, this would mean that the engagement in 2022 is not higher than it is.

  - The cost to the company of each type of error would depend on the implications of incorrectly concluding that engagement has increased—potentially leading to over-investment in certain features or complacency about needing to improve features—versus incorrectly concluding that engagement has not increased—potentially missing out on recognizing successful features or identifying areas that need improvement.

  - If the hypothesis that US students watch more or an equal amount of content as Indian students is rejected, this suggests that US students watch less content on average than students in India.


<p align="right"><a href="#top">Back to top</a></p>
