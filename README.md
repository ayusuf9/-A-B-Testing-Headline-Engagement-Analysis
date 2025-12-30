# Upworthy Headline A/B Test Analysis

## Overview
This project analyzes **30,000+ A/B headline experiments** from the Upworthy Research Archive (2013-2015) to determine what drives user engagement and validate experimental reliability.

## Dataset
- **Experiments:** 30,000+ headline A/B tests
- **Period:** 2013–2015
- **Metrics:** Impressions, clicks, CTR
- **Variations:** Multiple headlines per test, sometimes with image changes

## Objectives
1. Identify headline features that **maximize engagement**
2. Separate **breakthrough insights** from data anomalies
3. Assess **result reliability** across different experiment types

## Research Questions
| Question | Hypothesis Tested |
|----------|-------------------|
| **1. Numeric Impact** | Do headlines with numbers (`"5 Ways..."`) outperform those without? |
| **2. Question Framing** | Do question-style headlines increase CTR vs. declarative formats? |
| **3. Length Efficiency** | Is there an optimal headline length for engagement? |
| **4. Sentiment Influence** | Do emotional (positive/negative) headlines beat neutral ones? |
| **5. Text-Only Effect** | When images are identical, does text alone determine performance? |
| **6. Result Robustness** | Do exploratory findings replicate in confirmatory tests? |

## Methodology
- **Statistical analysis** of headline variations
- **Feature engineering**: sentiment scoring, length, question detection, numeric flags
- **Comparative validation**: exploratory vs. confirmatory experiments
- **Replication testing** for reliability assessment

## Notebook Code
- upworthy_analysis.ipynb