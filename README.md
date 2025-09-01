# A/B Test Analysis: New Webpage Design Evaluation

## 1. Executive Summary

This project analyzes the results of an A/B test conducted to determine if a new webpage design would increase the user conversion rate for an e-commerce company. The analysis revealed that there was **no statistically significant difference** in conversion rates between the old and the new webpage designs.

**Key Finding:** The new page performed slightly worse than the old page, but the difference was not statistically significant (p-value = 0.21).

**Business Recommendation:** **Do not launch the new page.** Sticking with the existing design is the recommended course of action, as it avoids investing resources in a change that does not provide a proven improvement in performance.

---

## 2. The Business Problem

The design team has invested time and resources into creating a new version of our main landing page. Before a full-scale launch, the stakeholders needed a data-driven answer to a critical question:

> Does the new webpage design actually lead to more users converting compared to the old design?

Launching a new page that underperforms could lead to a significant loss in revenue. This A/B test was designed to mitigate that risk by providing clear evidence of the new design's impact.

---

## 3. Our Approach: A/B Testing Methodology

To answer the business question, we performed a randomized controlled experiment, or A/B test. A segment of users was randomly shown either the old page (the "control" group) or the new page (the "treatment" group). We then tracked their conversion behavior.

Our analysis followed a rigorous process:

1.  **Data Cleaning:** We first ensured the integrity of our data by removing any entries where users were incorrectly assigned to a group or saw the wrong page. We also removed duplicate user entries to guarantee each user was counted only once.

2.  **Hypothesis Formulation:** We established a clear hypothesis to test:
    * **Null Hypothesis ($H_0$)**: There is no difference in the conversion rate between the old and new pages.
    * **Alternative Hypothesis ($H_1$)**: There is a difference in the conversion rate between the old and new pages.

3.  **Statistical Analysis:** We used a **Z-test for proportions** to determine if the observed difference in conversion rates was statistically significant or simply due to random chance. We set a significance level (p-value threshold) of 0.05.

---

## 4. Key Findings & Visualization

The analysis of 286,690 unique users yielded the following results:

* **Control Group (Old Page):**
    * **Total Users:** 143,293
    * **Conversion Rate:** **12.03%**

* **Treatment Group (New Page):**
    * **Total Users:** 143,397
    * **Conversion Rate:** **11.89%**

The statistical test produced a **p-value of 0.21**.

### A/B Test Conversion Rate Comparison
<img width="701" height="532" alt="output" src="https://github.com/user-attachments/assets/79d490c8-b67c-43a0-8e31-3928147b178b" />


As the chart clearly shows, the conversion rates for both pages are nearly identical. The new page's performance is slightly lower, but the difference is well within the margin of what we would expect from random variation.

---

## 5. Business Impact & Recommendation

### How This Helps Our Stakeholders

This analysis provides a clear, low-risk path forward and directly answers the initial business question.

* **Prevents a Costly Mistake:** The data shows that the new design is not an improvement. Launching it would consume developer time and marketing resources for zero (or even negative) return on investment.

* **Data-Driven Decision Making:** Instead of relying on subjective opinions about which page "looks better," we have concrete evidence of how they actually perform. This fosters a culture of making decisions based on data, not intuition.

* **Focuses Future Efforts:** Knowing this design was not successful, the design and marketing teams can now refocus their efforts on creating and testing entirely new hypotheses that might lead to a significant uplift.

### Final Recommendation

**Do not dedicate resources to launching the new webpage design.** The existing page should remain in place. We advise the design team to analyze these results and ideate on a different approach for the next iteration.
