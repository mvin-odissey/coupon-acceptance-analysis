# Will a Customer Accept the Coupon?

## Overview

<<<<<<< HEAD
This project analyzes customer coupon acceptance using survey data describing different driving scenarios, customer characteristics, and coupon types.

The analysis was completed as part of the UC Berkeley Machine Learning and Artificial Intelligence program using Python, pandas, Matplotlib, and Seaborn.

The goal is to explore which characteristics are associated with coupon acceptance and identify patterns that could help businesses improve coupon targeting.
=======
This project analyzes survey data on driving scenarios to understand which customers are more likely to accept coupons for restaurants, coffee houses, bars, and takeaway establishments.

The analysis was completed as part of the UC Berkeley Machine Learning and Artificial Intelligence program. It uses Python, pandas, Matplotlib, and Seaborn for data cleaning, exploratory analysis, and visualization.
>>>>>>> aceb87854a3ae6c0cd06898b7f63b1d538b9a2e7

## Key Findings

Across all coupon types, approximately 57% of the offered coupons were accepted.

<<<<<<< HEAD
Existing customer behavior was strongly associated with acceptance. For Bar coupons, customers who visited bars more than three times per month accepted approximately 77% of coupons, compared with approximately 37% among less frequent bar visitors.

A similar pattern appeared for Coffee House coupons: acceptance increased from approximately 19% among customers who never visited Coffee Houses to around 65–69% among those visiting at least once per month.

Age may provide additional information for Coffee House coupons. Customers below 21 showed higher acceptance than customers aged 21+ even when comparing customers with similar Coffee House visiting frequencies. However, several of the below-21 groups contained relatively few observations, so this result should be interpreted cautiously.

## Business Recommendations

The analysis suggests that existing customer behavior could be useful for coupon targeting.

Rather than distributing coupons uniformly, businesses could prioritize offers to customers who already engage with the corresponding type of establishment. For example:

- Bar coupons could be targeted toward customers who already visit bars regularly.
- Coffee House coupons could be prioritized for existing Coffee House visitors.
- Demographic characteristics such as age may provide additional targeting information, but should be validated before being used as targeting rules.

These results describe associations in survey data and should not be interpreted as evidence that these characteristics cause higher coupon acceptance.

## Next Steps

Further analysis could investigate:

- whether other customer characteristics, such as income, occupation, marital status, or passenger type, provide additional information beyond customers' existing behavior;
- how contextual factors, such as time of day, temperature, weather, destination, and direction of travel, are associated with coupon acceptance;
- whether characteristics of the offer itself, such as expiration time and coupon type, are associated with acceptance;
- whether customer characteristics and context interact — for example, whether Coffee House coupons perform differently by both visiting frequency and time of day.

Further work could also use larger samples or statistical methods to assess the reliability of observed differences, particularly for customers below 21, and test whether the patterns identified for Bar and Coffee House coupons generalize to other coupon types.

## Jupyter Notebook

The complete analysis, including data preparation, visualizations, calculations, and interpretation, is available here:

[View the Jupyter Notebook](prompt.ipynb)

## Repository Structure

- `prompt.ipynb` — complete exploratory analysis
- `data/` — source dataset used in the analysis
- `README.md` — project summary and key findings

## Tools

- Python
- pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
=======
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
>>>>>>> aceb87854a3ae6c0cd06898b7f63b1d538b9a2e7
