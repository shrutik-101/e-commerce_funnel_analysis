# 📊 E-commerce Funnel Analysis Dashboard

An end-to-end funnel analysis project designed to evaluate user behavior across an e-commerce journey, identify key drop-off points, and uncover factors impacting conversion and revenue.

---

# 🎯 Objective

Analyze user progression through the funnel:

**Browse → Add to Cart → Checkout → Purchase**

and answer critical business questions:

* Where are users dropping off the most?
* Which user segments underperform?
* What factors are impacting conversion and revenue?
* How can conversion be improved through data-driven decisions?

---

# 🧰 Tools & Technologies

* **SQL (SQLite)** → Data modeling and business query analysis
* **Python (Pandas, Faker)** → Synthetic data generation and preprocessing
* **Power BI** → Interactive dashboard development and data storytelling

---

# 📁 Dataset Overview

A synthetic dataset (~1000 sessions) simulating real-world user behavior:

* **Users** → device type, traffic source
* **Sessions** → session timestamps
* **Events** → user actions across funnel stages
* **Orders** → transaction details, revenue

---

# 📊 Key Metrics

* **Total Sessions:** 1000
* **Total Orders:** 360
* **Conversion Rate:** **36%**
* **Total Revenue:** **204,000**
* **Average Order Value (AOV):** **567**

---

# 🔥 Key Insights (Quantified)

* **46.7% drop-off occurs between Add to Cart → Checkout**, indicating a major friction point in the checkout stage
* Only **36% of users complete a purchase**, showing moderate funnel efficiency with clear room for improvement
* **Cart abandonment rate is approximately 47%**, leading to significant revenue loss
* **Mobile conversion (~34%) is lower than desktop (~38%)**, suggesting possible UX or performance issues
* **Organic traffic delivers higher conversion quality compared to paid sources**, indicating better user intent
* Conversion improvements have a **direct impact on revenue growth potential**

---

# 🧠 Root Cause Hypothesis & Recommendations

This section focuses on identifying *why* users drop off and how to solve these issues using data-driven strategies.

---

## 🔻 Problem 1: High Drop-off at Checkout Stage (46.7%)

### 📉 Possible Causes:

* Complex or multi-step checkout process
* Mandatory account creation or login barriers
* Unexpected additional costs (shipping, taxes)
* Limited or slow payment options
* Poor UI/UX, especially on mobile devices

### 💡 Recommendations:

* Enable **guest checkout** to reduce friction
* Simplify checkout into fewer steps (ideally single-page checkout)
* Display **total cost upfront** to avoid surprises
* Integrate faster payment options (UPI, wallets, autofill)
* Improve UI clarity and reduce form complexity

---

## 📱 Problem 2: Lower Mobile Conversion Rate

### 📉 Possible Causes:

* Poor mobile responsiveness
* Slow loading speed on mobile devices
* Difficult form inputs and navigation
* Poor button visibility or placement

### 💡 Recommendations:

* Optimize mobile UI for responsiveness and speed
* Reduce page load time using performance optimization techniques
* Simplify forms and enable autofill where possible
* Improve CTA visibility (clear and accessible checkout buttons)

---

## 🛒 Problem 3: High Cart Abandonment (~47%)

### 📉 Possible Causes:

* Users comparing alternatives before purchasing
* Lack of urgency to complete the purchase
* Absence of trust indicators (reviews, secure payment badges)
* Uncertainty around delivery or pricing

### 💡 Recommendations:

* Implement **cart recovery strategies**:

  * Email reminders
  * Push notifications
* Introduce urgency (limited-time offers, stock indicators)
* Add trust signals (ratings, secure checkout badges)
* Provide incentives such as discounts or free shipping

---

## 🌐 Problem 4: Low-Quality Traffic from Paid Sources

### 📉 Possible Causes:

* Ineffective ad targeting
* Mismatch between ad messaging and landing page
* Users in early stages of the buying journey (low intent)

### 💡 Recommendations:

* Optimize targeting to attract high-intent users
* Align landing page content with ad messaging
* Reallocate budget towards **high-converting channels (organic)**
* Use retargeting strategies for users who showed intent but did not convert

---

# 📈 Analytical Features Implemented

* Funnel analysis to track user progression across stages
* Drop-off identification and quantification
* Conversion rate analysis by device and traffic source
* Revenue and AOV tracking
* Time-based trend analysis
* Interactive filtering for dynamic exploration

---

# 🧠 What This Project Demonstrates

* Strong understanding of **funnel analytics and user behavior**
* Ability to **identify problems and propose actionable solutions**
* Data-driven decision-making approach
* Integration of **SQL, Python, and Power BI**
* Effective and structured data storytelling

---

# 🚀 Project Outcome

The analysis identified a **critical bottleneck at the checkout stage**, where nearly **half of the users drop off before completing a purchase**.

Addressing this issue through checkout optimization, mobile improvements, and better traffic targeting can significantly improve conversion rates and drive higher revenue.

---
