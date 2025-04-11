# 🚲 Yulu: Hypothesis Testing to Understand E-Bike Demand

This case study focuses on exploring the factors that significantly impact the demand for Yulu's shared electric cycles, using statistical hypothesis testing. The goal was to identify factors that significantly impact demand for e-bikes — and what that means for business decisions.

---

## 📍 Problem Statement

**About Yulu**

Yulu is India’s leading micro-mobility service provider, offering electric cycles designed for short-distance, eco-friendly commuting. With a strong presence around metro stations, office hubs, and residential areas, Yulu aims to make first and last-mile travel smooth, affordable, and sustainable.

**The Business Challenge**

Recently, Yulu has experienced a noticeable dip in revenue. To address this, they are specifically interested in understanding:
- Which variables significantly impact daily demand?
- How well these variables explain fluctuations in usage across time?

This project uses statistical hypothesis testing to explore those questions and support data-driven decision-making.

---

## 📊 What Was Done

- Cleaned and explored e-bikes rental usage data
- Defined a one-tailed hypothesis test
- Conducted a **two-sample t-test** using `scipy.stats.ttest_ind`
- Interpreted results and framed business takeaways

---

## ✅ Key Insight

The analysis revealed that factors like **hour of the day, month, temperature, humidity, windspeed, season, and weather** have a significant impact on e-bike demand. 
On the other hand, factors like **working day status, holidays, and day of the week** did not show a meaningful influence on usage.
This suggests that **demand varies with environmental and temporal conditions**, and not so much with calendar-based labels.

To improve usage during low-demand periods, **Yulu could introduce dynamic pricing** — for example, offering lower prices during hotter or off-peak hours — to encourage more rides and boost revenue.


---

## 📌 Techniques Used

- Python (Pandas, NumPy, SciPy, Seaborn)
- Data cleaning & aggregation
- Hypothesis testing
- One-tailed, two-sample t-test
- Business insight framing

---

## 🗂️ Files

| File | Description |
|------|-------------|
| `Yulu_HypothesisTesting.ipynb` | Main notebook containing analysis and test |
| `README.md` | Project overview and summary (this file) |

---

## 👤 About Me

I'm **Sarath Chandra TS**, a tech professional with 18+ years of experience, actively building skills in **Data Science and Machine Learning** through hands-on case studies and real-world business problems.

📫 [Connect on LinkedIn](https://www.linkedin.com/in/sarath-chandra-t-53895115/)

