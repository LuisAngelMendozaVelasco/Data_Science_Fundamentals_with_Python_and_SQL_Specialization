# Alpha (α) and P-value

Alpha and p-value are commonly used terms in statistical analysis.  We hear these two terms quite often and will be hearing them until the end of this course.  Both are used in hypothesis testing when we are trying to reject or fail to reject  a given hypothesis.

Alpha (α) is also known as the significance level. It is the probability of rejecting the null hypothesis when the null hypothesis is true. The value used is often 5%.  This means, that in a given  population or sample if we computed a range of values in which the mean lies, 5 out of 100 times, this range of values will not contain the mean values but we might have said it does. The alpha value is the risk you are willing to accept if you are wrong, it signifies the rejection region and any value that falls inside this region will not be accepted. Depending on the use case, you may be willing to go as high as 20%. That means that you are okay with the consequences of falsely rejecting the null hypothesis 20% of the time. In a field like medicine, we will set the significance level as low as possible, e.g. 0.1% if there was potential harm to patients - in this case, we can't afford to leave any room for error.

We can see in this image the rejection regions for different kinds of tests.

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/V90kv07AQOqdJL9OwBDq8A_665393034e954e8fb4406aa3b730df1e_alpha_level.jpg?expiry=1706400000000&hmac=YTBXtvS3M-sNgBrBXdvMiWO5tkYgXlAxfvNhsH0v_pk)

Note: In cases of a Two-Tailed test, the rejection region on both tails add up to the total value of alpha i.e. if α = 5%, the rejection region on both tails will be 2.5% each.

P-value is a calculated value and an output you get as part of conducting your hypothesis test. Depending on the test, the calculation will vary. The p-value can be interpreted as the probability of getting a result that is as extreme or more extreme when the null hypothesis is true i.e. the likelihood of observing that particular sample value if the null hypothesis were true. Therefore, if the p-value is smaller than your significance level, you will reject the null hypothesis. For example, we have a null hypothesis that:

Null Hypothesis: μ = 100

Alternative Hypothesis: μ > 100

If you conduct a test and you get a p-value of 0.02, this means that there is a 2% chance of obtaining a value of 100 or more than 100. If we picked a significance value of 5%, we will reject the null hypothesis, because 2% is less than 5%. If we picked a significance value of 1%, we will fail to reject the null hypothesis because 2% is greater than 1%.

To use both the p-value and significance level together,  you have to decide on a value for alpha after you state your hypothesis.  Suppose that is alpha = 0.10 (or 10%).  You then collect the data and calculate the p-value.  If the p-value is greater than alpha, you assume that the null hypothesis is true and you fail to reject.  If the p-value is less than alpha, you assume that the null hypothesis is false and you reject it. In cases when the p-value and the significance levels are approximately equal e.g. a p-value of 0.11, it is your call to decide to reject or fail to reject or you could decide to resample and collect more data.