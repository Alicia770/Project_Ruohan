# Product Development at Uber Analysis

## Problem Statement

High rider cancellations during peak commute hours were reducing retention and limiting profitability. We aimed to test whether adjusting wait times dynamically by time-of-day could improve rider satisfaction without increasing operational costs.

## Approach

*Summarization: Conducted A/B testing using Python (SciPy) to evaluate the impact of wait-time adjustments on rider behaviour, applying t-tests and hypothesis testing to assess statistical significance across time-of-day segments.*


- Experimental Design

1) Built an A/B testing framework in Python (SciPy).

2) Split riders into control (current wait times) and treatment (adjusted wait times).

3) Applied t-tests and hypothesis testing to validate statistical significance.

- Segmentation

1) Evaluated results across time-of-day segments (morning/evening peak vs. off-peak).

2) Controlled for confounding variables such as route length and rider demographics to ensure robustness.


## Key Findings

*Summarization: Identified that shorter wait times during peak commute hours led to a significant drop in cancellations without raising operational costs, enabling the development of a dynamic, hour-specific strategy that improved rider retention and boosted profitability.*


Peak Hours: Reducing wait times by 5 minutes led to a significant drop in cancellations (p < 0.05).

Off-Peak Hours: No material change in behaviour, suggesting that reducing wait times is unnecessary during low demand.

Operational Impact: Shorter wait times did not increase fleet or operating costs, making changes cost-neutral.


## Business Impact

- Informed development of a dynamic, hour-specific scheduling strategy.

- Improved rider retention and boosted profitability for Uber.

- Provided a scalable, data-driven framework for future demand management.







