# Why Do Users Browse But Don’t Buy?
### E-Commerce Funnel & Engagement Analysis

## 📖 Project Overview
This project analyzes user behavior on an e-commerce website to understand **why a large proportion of users browse products but do not complete a purchase**.

Using exploratory data analysis, funnel analysis, and behavioral segmentation, the project identifies key drop-off points in the user journey and proposes **data-driven hypotheses** that can be validated through experimentation (A/B testing).

---

## 🎯 Business Problem
Although thousands of users actively explore product pages, only a small fraction convert into buyers.

**Key question:**
> Where are users dropping off in the funnel, and what behavioral patterns differentiate buyers from non-buyers?

---

## 📂 Dataset
- **Source:** Online Shoppers Purchasing Intention Dataset
- **Sessions:** 12,330
- **Features:** 18 behavioral, contextual, and outcome variables
- **Target Variable:** `Revenue` (Purchase outcome)

---

## 🧠 Analysis Approach

### 1️⃣ Exploratory Data Analysis (EDA)
- Purchase vs non-purchase distribution
- Product pages viewed
- Time spent on product pages
- Bounce and exit rates
- Visitor type behavior

### 2️⃣ Funnel Analysis
Defined funnel stages based on user behavior:
1. **Session Started**
2. **Product Discovery** (Viewed at least one product page)
3. **Deep Engagement** (High product page duration)
4. **Purchase**

Measured user drop-off at each stage.

### 3️⃣ Engagement Segmentation
Users were segmented into:
- Low Engagement
- Medium Engagement
- High Engagement  
based on product-related time spent.

### 4️⃣ Conversion Analysis
Compared conversion rates across:
- Engagement levels
- Visitor types
- Weekend vs weekday
- Monthly trends

---

## 🔍 Key Insights

- Only **~15% of sessions result in a purchase**
- Buyers:
  - View significantly more product pages
  - Spend much more time on product pages
  - Have lower bounce and exit rates
- The **largest drop-off (~50%) occurs between Product Discovery and Deep Engagement**
- High-engagement users convert at substantially higher rates
- Conversion varies by visitor type and time context

---

## 📊 Dashboards

### User Engagement Behavior Dashboard
Analyzes browsing depth and time spent to understand pre-purchase behavior.
  
*(Power BI screenshots included in `/dashboard`)*

### Conversion & Revenue Performance Dashboard
Examines conversion rates across engagement levels, visitor segments, time, and weekends.

---

## 🧪 Hypotheses & Assumptions (Root Cause Exploration)

> ⚠️ Note: This dataset is **observational**, not experimental.  
> The following hypotheses are **proposed**, not proven, and are intended for validation through controlled experiments.

### Hypothesis 1 — Insufficient Product Information
Users drop off after browsing because product pages lack sufficient details to support confident decision-making.

**Proposed Test:**  
Enhance product pages with richer descriptions, reviews, and comparison tables.

---

### Hypothesis 2 — Decision Fatigue from Too Many Choices
Users abandon sessions due to cognitive overload caused by excessive or similar product options.

**Proposed Test:**  
Introduce curated recommendations (e.g., “Top Picks” or “Recommended for You”).

---

### Hypothesis 3 — Lack of Trust Signals
Returning users hesitate to convert due to missing trust indicators such as guarantees, reviews, or return policies.

**Proposed Test:**  
Display trust badges, delivery timelines, and return policies near the purchase CTA.

---

### Hypothesis 4 — Purchase Friction
Highly engaged users still fail to convert due to checkout complexity or friction.

**Proposed Test:**  
Reduce checkout steps or enable guest checkout.

---

### Hypothesis 5 — Intent Varies by Time & Context
User intent fluctuates based on timing (month, weekend vs weekday), impacting conversion likelihood.

**Proposed Test:**  
Run time-based promotions or personalized nudges during low-intent periods.

---

## 🛠 Tools & Technologies
- **Python:** Pandas, Matplotlib, Seaborn
- **BI Tools:** Power BI
- **Analysis:** EDA, Funnel Analysis, Segmentation
- **Version Control:** Git & GitHub

---

