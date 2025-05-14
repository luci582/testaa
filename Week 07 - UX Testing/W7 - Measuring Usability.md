While qualitative feedback from [[W7 - Usability Testing|usability testing]] provides rich insights into *why* users encounter problems, quantitative measures offer an objective way to assess *how usable* a system is. Measuring usability provides confidence to stakeholders, ensures resources are not wasted, and allows products or features to be benchmarked against previous iterations or competitors.

**Tags:** #Week7 #UXTesting #UsabilityMetrics #SUS #SystemUsabilityScale #UMUX #QuantitativeMeasures #UserSatisfaction

## Why Measure Usability?

* **Objective Assessment:** Provides quantifiable data on how easy a system is to use, moving beyond subjective opinions.
* **Stakeholder Confidence:** Numerical data can be more persuasive for stakeholders, demonstrating the effectiveness (or ineffectiveness) of a design.
* **Benchmarking:** Allows teams to:
    * Compare the usability of a product over time (e.g., after design changes).
    * Compare their product's usability against competitors.
* **Resource Allocation:** Helps to justify investment in usability improvements by quantifying the current state.
* **Identifying Areas for Improvement:** While not as diagnostic as qualitative feedback, poor scores can highlight that there *is* a problem.

## Key Aspects of Usability to Measure

Standardized usability questionnaires often aim to measure:

* **Effectiveness:** Can users successfully achieve their objectives with the system?
* **Efficiency:** How much effort and resources (e.g., time, cognitive load) are expended in achieving these objectives?
* **Satisfaction (Ease of Use):** Was the experience satisfactory from the user's perspective? How easy or pleasant was it to use the system?

## Standardized Usability Questionnaires

These are tried and tested tools for collecting quantitative usability data.

### 1. System Usability Scale (SUS)
* **What is it?** A widely used, reliable, and quick 10-item questionnaire with a 5-point Likert scale for responses. It provides a global view of subjective usability.
* **Developed by:** John Brooke at Digital Equipment Corporation in 1986.
* **Measures:** Perceived usability, encompassing aspects of effectiveness, efficiency, and satisfaction.
* **Questionnaire Structure:**
    * Consists of 10 statements (e.g., "I think that I would like to use this website frequently," "I found this website unnecessarily complex").
    * Five statements are positively worded, and five are negatively worded (to avoid acquiescence bias).
    * Respondents rate their agreement with each statement on a 5-point scale from "Strongly Disagree" to "Strongly Agree."
* **Scoring:**
    * A specific calculation method converts the raw scores into a single score ranging from 0 to 100.
    * **Important:** The SUS score is *not* a percentage. It's a percentile score.
    * An average SUS score is around 68.
    * Scores above 68 are considered above average; scores below are below average.
    * **Interpretation (from lecture slide):**
        * **0-50:** Not Acceptable (Poor)
        * **51-70:** Marginal (Okay)
        * **70-85:** Acceptable (Good)
        * **> 85:** Excellent (Best Imaginable)
* **When to Use:** Typically administered *after* a usability testing session where the participant has interacted with the system.

### 2. Usability Metric for User Experience (UMUX)
* **What is it?** A shorter, 4-item questionnaire designed as an alternative to the SUS, specifically targeting effectiveness, efficiency, and satisfaction.
* **Developed by:** Kraig Finstad and colleagues at Intel in 2010.
* **Purpose:** To offer a more concise way to measure general usability.
* **Questionnaire Structure:**
    * 4 statements: 2 positively worded, 2 negatively worded.
        1.  "[This system’s] capabilities meet my requirements." (Effectiveness)
        2.  "[This system] is easy to use." (Ease of Use/Satisfaction)
        3.  "Using [this system] is a frustrating experience." (Satisfaction - negative)
        4.  "I have to spend too much time correcting things with [this system]." (Efficiency - negative)
    * Respondents rate agreement on a 5-point or 7-point Likert scale.
* **Benefits:**
    * Shorter and quicker to administer than SUS.
    * More focused on specific usability attributes (effectiveness, efficiency, satisfaction).
    * Easier for participants to complete and simpler to analyze.

### 3. UMUX-Lite
* **What is it?** An even shorter, 2-item version of UMUX, containing only the two positively worded statements from the UMUX questionnaire.
* **Questionnaire Structure:**
    1.  "[This system’s] capabilities meet my requirements."
    2.  "[This system] is easy to use."
* **Benefits:**
    * More time-efficient.
    * Simpler to administer and analyze.
* **Use Case:** Best used as a quick "litmus test" of usability rather than a deep diagnostic tool.
* **Scoring & Reporting (UMUX/UMUX-Lite):** Scores can be averaged and reported, often correlated with SUS scores for benchmarking. The lecture slide included a visual showing a two-dimensional plot of "Capabilities" vs. "Ease of use."

## Connecting Measurements to Hypotheses

Quantitative usability data can be directly linked back to the [[W7 - Hypothesis Generation and Testing|hypotheses]] formulated during the planning phase.

* **Example 1 (Customer Attitudes - Insurance Payment):**
    * *Hypothesis:* "We will see more customers paying monthly..."
    * *Measuring Usability/Outcome:*
        * "X/Y customers assume they will save money if they make a one-off payment for the year."
        * "A/B customers would pay monthly... which is more than C/D who currently pay monthly."
* **Example 2 (Ease of Use - Insurance Price Calculation):**
    * *Hypothesis:* "...customers can easily see how much they will need to pay..."
    * *Measuring Usability/Outcome:*
        * "X/Y customers completed task successfully."
        * "Average rating X/5 for ease of use."
* **Example 3 (A/B Testing - Price Breakdown Clarity):**
    * *Hypothesis:* "...customers prefer seeing a price breakdown..."
    * *Measuring Usability/Outcome:*
        * "X/Y prefer version A because… and they don’t like version B because…" (and vice-versa).
        * "Clarity rating X/5 for Version A and Y/5 for Version B."

By collecting and analyzing these types of quantitative data alongside qualitative observations, UX teams can gain a comprehensive understanding of their product's usability and make informed decisions for improvement.

---
**Parent Topic:** [[Week 07 - UX Testing]]
**Previous Topic:** [[W7 - Hypothesis Generation and Testing]]
**Overall Course Context:** [[INFS3700 UX & IT Service Design - Main Summary]]