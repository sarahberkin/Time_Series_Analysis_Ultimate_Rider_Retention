# Ultimate Rider Retention Analysis

This project was completed as part of Springboard's Data Science Career Track curriculum. It consists of three parts: time series analysis, experiment design, and predictive modeling. The final model predicts rider retention and provides actionable business recommendations.

## 📊 Part 1: Login Time Series Analysis
- Parsed and aggregated login data into 15-minute intervals.
- Identified demand patterns such as daily activity cycles and weekday vs. weekend trends.
- Visualized login behavior to uncover peak usage periods.

## 🧪 Part 2: Experiment Design
- Designed an A/B test to evaluate the impact of toll reimbursements on cross-city driving behavior.
- Proposed using average revenue per driver from cross-city trips as the key success metric.
- Suggested a randomized control trial and outlined the statistical evaluation plan.

## 🤖 Part 3: Rider Retention Modeling
- Built a classification model using Gradient Boosting to predict user retention.
- Performed feature engineering based on EDA insights.
- Tuned decision threshold to improve recall for retained users.
- Achieved an accuracy of 78% and identified top predictors of retention.

## 🧠 Key Business Insights
- Early engagement (trips in the first 30 days) and use of premium services (Ultimate Black) are strong predictors of retention.
- City-level differences suggest opportunities for region-specific strategies.
- Proactive retention efforts (e.g., onboarding offers, loyalty perks) are recommended based on model predictions.

## 📁 Files
- `logins.json` – Login timestamps dataset (Part 1)
- `ultimate_data_challenge.json` – Rider dataset (Part 3)
- `eda_logins_json.ipynb` – Full notebook with analysis, model, and insights

---

🚀 Built using Python, Pandas, scikit-learn, and Matplotlib.
