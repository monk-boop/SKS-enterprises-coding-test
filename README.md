# SKS-enterprises-coding-test
NLP test for SKS enterprises coding interview
## Approache to the Problem
- In the first question, it only needs us to find the face value of the coupons. This was done using some regular expressions.
- In the second qustion, we had to find all the products in the coupons. The initial approach was to try and use spacy's already available and trained models for the coupons but that did not give very good results. So, in the next approach, we created a blank english class and gave some training data for the model to learn the products from. This gave decent results.

## Results
- The results can be improved by taking a larger amount of data. We only took 10 data points for a dataset of 884 values.
