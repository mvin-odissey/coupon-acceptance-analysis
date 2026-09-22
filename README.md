# Will a Customer Accept the Coupon?

## Overview

This project analyzes survey data on driving scenarios to understand which customers are more likely to accept coupons for restaurants, coffee houses, bars, and takeaway establishments.

The analysis was completed as part of the UC Berkeley Machine Learning and Artificial Intelligence program. It uses Python, pandas, Matplotlib, and Seaborn for data cleaning, exploratory analysis, and visualization.

## Key Findings

Across all coupon types, approximately 57% of the offered coupons were accepted.

Existing customer behavior was strongly associated with acceptance. For bar coupons, customers who visited bars more than three times per month accepted approximately 77% of coupons, compared with approximately 37% among less frequent bar visitors.

A similar pattern appeared for Coffee House coupons: acceptance increased from approximately 19% among customers who never visited Coffee Houses to around 65–69% among those visiting at least once per month.

Age may provide additional information for Coffee House coupons. Customers below 21 showed higher acceptance than customers aged 21+ even when comparing customers with similar Coffee House visiting frequencies. However, the younger groups were relatively small, so this result should be interpreted cautiously.

## Business Recommendations

The results suggest that coupon targeting could benefit from using customers’ existing behavior rather than sending the same offers broadly. Bar coupons could be prioritized for customers who already visit bars frequently, while Coffee House coupons could be prioritized for existing Coffee House visitors.

Demographic characteristics such as age may provide additional targeting information, but they should be considered together with existing customer behavior rather than interpreted in isolation.

Because this analysis is based on observational survey data, the results show associations rather than causal effects. They should therefore be treated as evidence for targeting hypotheses rather than definitive targeting rules.

## Next Steps

Further analysis could investigate whether demographic and situational characteristics remain associated with coupon acceptance after accounting for existing customer behavior. Larger samples or statistical modeling could also help assess the reliability of the observed differences, particularly among customers below 21.

## Jupyter Notebook

The complete analysis, including data preparation, calculations, visualizations, and detailed observations, is available in the prompt.ipynb.

## Repository Structure

- `prompt.ipynb` — complete analysis
- `data/` — source dataset
- `images/` — visualizations generated during the analysis
- `README.md` — project summary
