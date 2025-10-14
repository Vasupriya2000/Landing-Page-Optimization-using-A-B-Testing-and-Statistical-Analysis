# 📊 Business Statistics Project: E-News Express

## 📰 Project Overview

**E-News Express**, a fast-growing digital news portal, is striving to improve user engagement and increase subscriber numbers. This project uses **statistical analysis and A/B testing** to evaluate the effectiveness of a redesigned landing page on user behavior and conversion rates.

> “The goal: Use data-driven insights to determine whether the new landing page converts more users into subscribers.”

---

## 📌 Problem Statement

E-News Express has noticed a **decline in new monthly subscribers** and suspects the current landing page is not engaging enough. A new landing page with a better outline and more relevant content has been designed.

This project investigates whether the new landing page:

- Encourages users to spend **more time** on the site
- Increases the **conversion rate** (turning visitors into subscribers)
- Has different impacts based on the users’ **preferred language**

---

## 🔍 Business Context

Digital news portals provide quick access to global events using multimedia technologies unavailable in traditional print. E-News Express seeks to capitalize on this by optimizing the user experience through data-driven decisions.

To address subscriber decline, an **A/B test** was run:

- **100 users** were randomly split into two groups:
  - **Control group:** saw the **old landing page**
  - **Treatment group:** saw the **new landing page**
- User interactions were logged for analysis.

---

## 🎯 Objectives

As a Data Scientist, you will assess the new landing page’s effectiveness by answering:

1. 📈 Do users spend **more time** on the new landing page?
2. 🔁 Is the **conversion rate** higher for the new page?
3. 🌐 Does conversion depend on the **preferred language**?
4. ⏳ Is the **time spent** on the new page the same across different languages?

*All hypotheses are tested at a 5% significance level.*

---

## 📂 Dataset Information

| Feature                 | Description                                      |
|-------------------------|------------------------------------------------|
| `user_id`               | Unique ID for each visitor                       |
| `group`                 | Group assignment: `control` or `treatment`      |
| `landing_page`          | Landing page version: `old` or `new`             |
| `time_spent_on_the_page`| Time (minutes) spent on the landing page         |
| `converted`             | Subscription status: `True` if converted, else `False` |
| `language_preferred`    | User’s chosen language to view the content       |

---

## 📊 Tools & Techniques Used

- Python (Pandas, NumPy, SciPy, Seaborn, Matplotlib)
- A/B Testing & Hypothesis Testing (T-tests, Chi-square tests)
- Exploratory Data Analysis (EDA)
- Data Visualization
- Contingency Tables

---

## 📌 Conclusion and Business Recommendations

### 📋 Conclusions

- ✅ The dataset is complete with **no missing values**, containing 100 rows.
- 🔢 Columns `group`, `landing_page`, and `converted` each have exactly **two unique values**.
- 👥 There are 50 users in the **control group** (old landing page), and **54 users converted** to subscribers overall.
- 🌎 **Spanish** is the most preferred language, chosen by 34 users.
- ⏱️ Average time spent on the website is approximately **5 minutes 37 seconds**, with a maximum around **10 minutes 71 seconds**.
- 🚫 No outliers found; median time spent is around **5 to 6 minutes**, with over 20 users spending this amount of time.
- 📈 Of 100 users, **54 subscribed** while 46 did not.
- ⏳ Median time on the **old landing page** is about **4 to 5 minutes**, compared to **6 to 7 minutes** on the **new landing page**.
- 📊 The new landing page has a higher **minimum time spent** (~3 minutes) than the old page (~0-1 minute).
- 🕒 Subscribers spend more time on the page (avg. **7 minutes**) than non-subscribers (avg. **4 minutes**).
- 🗣️ Users preferring **Spanish** and **English** spend about **6 minutes**, while **French** users spend roughly **5 minutes**.
- 🔄 The **new landing page** sees more time spent and **33 conversions** vs. **21** on the old page.
- 📈 The **conversion rate** is higher for the new landing page.
- 📉 Visuals show **French-speaking users** are more likely non-subscribers.
- 🌐 A clear relationship exists between **preferred language and conversion status**.
- 🇬🇧 English-preferred users on the new page spend more time than other languages.
- 📊 Time spent on pages follows a **normal distribution** with **equal variance**.
- ⚖️ Significant differences exist in time spent on the new page among different language users.

---

### 💡 Business Recommendations

- 🚀 Prioritize rolling out the **new landing page** to all users to boost engagement and subscriptions.
- 🎨 Expand the new page’s design focusing on features proven to increase time spent and conversions.
- 🎯 Target marketing efforts to specific language groups, especially **English speakers**, who convert more.
- 📢 Promote the new landing page through **advertising and campaigns** to increase reach.
- 🔍 Identify and enhance the **interactive features** or content that attract users to maximize engagement.
- 🌍 Provide **localized content and region-specific news** tailored for language groups to improve conversions.
- 🛠️ Implement features to increase time spent by non-subscribers, especially on the old page.
- 🕵️ Analyze and remove barriers causing low conversion rates in certain language groups or segments.
- 📝 Collect **user feedback** via surveys or reviews to understand preferences and continuously improve the landing page experience.

---

## 🚀 How to Use This Project

1. Clone this repository to your local machine.
2. Open the Jupyter Notebook or Python scripts.
3. Run the analysis to explore user engagement and conversion insights.
4. Use the findings to inform UI/UX and marketing strategies.

---

## 📫 Contact

For questions, suggestions, or collaborations, please open an issue or contact me at [YourEmail@example.com].

---

*Thank you for checking out this project! Feel free to ⭐ the repo if you found it helpful.*  
