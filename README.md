# Veteran Suicide Probability Analysis

This project applies **Bayes' Theorem** to calculate the probability of suicide among U.S. military veterans compared to the general population, using real-world data from 2022. The goal is to raise awareness about the elevated suicide risk faced by veterans and provide a simple, reproducible data science example.

## Overview
Using Python and Jupyter Notebook, this project:
- Estimates the probability of suicide given veteran status.
- Visualizes the disparity between veterans and the general population with a Seaborn bar plot.
- Highlights that veterans are approximately **2.6 times more likely** to die by suicide than non-veterans.

In 2022, **6,392 veterans** died by suicide—an average of 17.5 per day—underscoring the urgency of mental health support for this community.

## Data Sources
- **U.S. Population**: ~333 million (U.S. Census Bureau, 2022 estimate).
- **Total Suicides**: 49,476 (CDC National Center for Health Statistics, 2022).
- **Veteran Population**: ~16.5 million (VA, 2022).
- **Veteran Suicides**: 6,392 (VA 2024 National Veteran Suicide Prevention Annual Report).

**References**:
- [VA 2024 National Veteran Suicide Prevention Annual Report](https://www.mentalhealth.va.gov/suicide_prevention/data.asp)
- [CDC WONDER Database](https://wonder.cdc.gov/)

## Results
- Probability of suicide (general population): **0.0001486** (~148.6 per million).
- Probability of suicide (veterans): **0.0003876** (~387.6 per million).
- Veterans face a significantly higher risk, emphasizing the need for targeted interventions.

See the plot in `veteran_suicide.ipynb` for a visual comparison.

## Prerequisites
- Python 3.6+
- Libraries: `numpy`, `seaborn`, `matplotlib`
- Jupyter Notebook

Install dependencies:
```bash
pip install numpy seaborn matplotlibgit status
