# 🚲 A/B Testing Simulation: Rainy Day Ride Patterns (Capital Bikeshare)

This project simulates an A/B test to evaluate the effectiveness of push notifications in increasing Capital Bikeshare e-bike rides on rainy mornings. The goal is to measure the uplift in ridership during peak morning hours (6–9 AM) due to targeted messaging.

## 🔍 Project Objective
To determine whether sending push notifications on rainy mornings increases e-bike rides during commuter hours.

## 🧪 Experiment Setup
- **Control Group**: Users who received no notifications.
- **Test Group**: Users who received a motivational push notification before 6 AM on rainy mornings.
- **Metric**: Number of e-bike rides from 6 AM to 9 AM.
- **Hypothesis**:
  - H₀: There is no difference in ride counts between control and test groups.
  - H₁: The test group shows a higher mean ride count.

## 🛠️ Tools & Techniques
- **Python**: Main programming language
- **Pandas**: ETL pipeline for weather + ride data
- **SciPy**: Two-tailed t-test to validate uplift
- **Matplotlib / Seaborn**: Visualization
- **Weather API**: Collected historical weather (rainy conditions)
- **Synthetic Data**: Simulated uplift of ~20%

## 📈 Results
- Observed a **statistically significant uplift** in ride activity during rainy mornings for the test group.
- **p-value = 0.0025** indicates strong evidence against the null hypothesis.
- The uplift suggests push notifications may be an effective engagement strategy during inclement weather.


