# Credit-Default-Risk-Engine
**Headline**

Minimizing Capital Loss in Unsecured Lending using Cost-Sensitive Machine Learning.

**Executive Summary**

Developed a credit scoring engine to predict loan defaults. The initial model achieved 74% accuracy but failed to capture 66% of high-risk defaults. I re-engineered the solution to prioritize Capital Preservation over raw accuracy.

**The Solution**

**Algorithm:** Random Forest Classifier with Class Weighting to penalize false negatives.

**Threshold Tuning:** Adjusted the probability acceptance threshold from 50% to 30%, creating a stricter "Risk-Averse" policy.

**Business Impact:**

**Risk Reduction:** Reduced the False Negative rate (missed defaults) from 39 to 12.

**Financial Modeling:** On a simulated portfolio of 1,000 loans (£10k avg), this optimization prevented a theoretical £270,000 in bad debt write-offs compared to the baseline model.
