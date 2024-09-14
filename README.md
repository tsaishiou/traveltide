# Travel Tide Reward Program

## Overview

In today's competitive travel industry, customer retention is essential for growth. To improve customer engagement, the **Travel Tide** team initiated a customer segmentation project to design a personalized loyalty program. By identifying key customer groups and tailoring rewards to their preferences, we aim to enhance the travel experience, increase retention, and boost engagement.

This repository contains the key components of the project, including:
- A **Colab notebook** with the full analysis
- A **video presentation**
- **Presentation slides**
- An **executive summary** detailing the project's methodology and findings

## Project Goals

- **Personalize** the loyalty program by identifying customer segments
- **Enhance** the customer experience with tailored rewards
- **Increase** customer engagement and retention
- **Optimize** marketing efforts using data-driven insights

## Methodology

The project focused on customers who interacted with our platform between **January 5, 2023, and July 29, 2023**. Using a dataset of **5,998 customers**, we applied the following steps:

1. **Data Collection**: Focused on customers with at least 8 sessions during the period.
2. **Data Processing**: Utilized **SQL** and **Python** for data extraction, cleaning, and transformation.
3. **Clustering**: Applied **k-Means clustering** for segmentation, with **Principal Component Analysis (PCA)** to reduce dimensionality and improve clustering accuracy.

## Key Findings

We identified **six customer segments** through clustering:

1. **Luxury Long-Trip Travelers**: High spenders on long-distance trips.
2. **Price-Sensitive Travelers**: Price-conscious with higher cancellation rates.
3. **High-Spending Frequent Flyers**: Frequent travelers with high purchase rates.
4. **Standard Short-Trip Travelers**: Slightly older, booking shorter, more affordable trips.
5. **Young Leisure Travelers**: Younger, moderate spenders focused on leisure.
6. **Budget Travelers**: Low spenders with less frequent travel.

## Assigned Perks by Segment

We tailored rewards to match customer preferences, ensuring maximum engagement:

- **High-Spending Frequent Flyers**: Free hotel night with flight bookings
- **Luxury Long-Trip Travelers**: Free hotel night and free checked bag
- **Young Leisure Travelers**: Free checked bag
- **Standard Short-Trip Travelers**: Package discounts
- **Price-Sensitive Travelers**: No cancellation fees
- **Budget Travelers**: Free hotel meal

## Recommendations

1. **Tailor Perks**: Match rewards to each customer segment.
2. **Tiered System**: Introduce a tiered loyalty program to incentivize frequent flyers and high spenders.
3. **A/B Testing**: Use testing to optimize perks for each segment.
4. **Cohort Analysis**: Monitor segment behavior over time to fine-tune the program.

