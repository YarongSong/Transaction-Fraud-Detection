# Transaction-Fraud-Detection

## Bullet Points:
1. Data is highly imbalanced with about 1% positive (fraudulent) and 99% negative (non-fraudulent) data.

2. Binary Search (T = n * logm) was used to identify country info based on ip_address, which took half of the time using the Brute Force (T = n * m).

3. The most predictive features for fraud detection are "interval_after_signup", "num_device_shared" and time related "hour_of_day"/"day_of_year" etc.

4. Random Forests and Gradient Boosting performed better than Logistic Regression.

5. Actionable operation recommendations/proposal were made for business.
