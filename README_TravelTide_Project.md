# TravelTide Customer Segmentation Analytics

**Masterschool Mastery Project – BI Track**  
**Author:** Dean Eyre  
**Date:** 16 May 2025

---

## 📌 Contents

- Project Overview and Major Tasks
- Business Context & Challenges
- Approach
- Customer Segmentation and Perks
- Overall Recommendations and Next Steps

---

## 1. Project Overview

TravelTide is a fast-growing e-booking startup offering flights and hotel bookings. CEO **Kevin Talanick** has identified issues in customer experience leading to **poor retention**.

Head of Marketing **Elena Tarrant** has been tasked with designing a **personalized rewards program** to improve retention.

### Major Tasks for the Data Analyst

- Perform **Exploratory Data Analysis (EDA)** to determine meaningful customer segmentation.
- Provide **segmentation recommendations**.
- Recommend **tailored perks** for each customer segment.

---

## 2. Business Context & Challenges

### 🔍 Problems and Limitations

- Overlapping segments (e.g., a *Business Traveler* who is also a *High Spender*).
- Data anomalies: negative/zero hotel nights, unreliable airport locations.
- Session data filtered to users with **>7 sessions** from **2023-01-04 to 2023-07-29**.

---

## 3. Approach

1. **EDA** – Understand the data
2. **Feature Engineering** – Define relevant metrics
3. **Customer Segmentation** – Use decision tree logic to assign users
4. **Presentation** – Communicate insights and perks

---

## 4. Customer Segments & Perks

| Segment               | Definition                                                                 | Limitations                                                     | Recommended Perk                     |
|-----------------------|---------------------------------------------------------------------------|------------------------------------------------------------------|--------------------------------------|
| **Business Traveler** | Solo weekday travel (Mon–Fri), 2+ such trips                              | Misses 'bleisure' travelers; risk of misclassification           | No Cancellation Fees                 |
| **High Spender**      | Top 25% of spenders (> $4,000)                                             | 25% overlap with Business Travelers                              | Free hotel night with flight         |
| **Bargain Hunter**    | >60% of bookings at discount                                               | May overlap with other segments                                 | 15% discount on next booking         |
| **Family with Kids**  | Children; books 3+ flight seats or 2+ hotel rooms                          | Small segment – may not justify separation                       | Free meal in hotel                   |
| **Dreamer**           | Browses or cancels bookings without completing a trip                     | Easiest to identify; debatable reward potential                  | 15% off first successful booking     |
| **Frequent Vacationer**| 3+ valid trips during period                                              | May overlap with Business or High Spender                        | Free checked bag                     |
| **General Vacationer**| All remaining users not captured above                                    | Broad segment; hard to personalize                               | 15% discount on next booking         |

---

## 5. Overall Recommendations & Next Steps

- ✅ **A/B Test perks**, starting with Business Travelers.
- 📊 **Cost/Benefit Analysis** to evaluate impact of perks on retention.
- 💡 Explore a **loyalty points scheme** (e.g., “TravelTide Points”).
- 🧠 Conduct **user research** to refine the loyalty model and address retention challenges.

---

## Conclusion

This segmentation framework allows TravelTide to personalize user experience and boost retention. The project recommends testing the impact of perks, enhancing loyalty with flexible models, and continuously iterating based on customer insights.
