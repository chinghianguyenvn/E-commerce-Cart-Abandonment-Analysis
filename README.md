# E-commerce Cart Abandonment: An Experimental Analysis (A/B Testing)

## Project Overview
This project investigates various underlying causes of cart abandonment in an e-commerce platform using an **Experimental Design** approach. The analysis is divided into two major phases to evaluate both marketing promotional strategies and technical UI/UX frictions.

## Phase 1: The Impact of Promotions (Loyalty Programs & Coupons)
* **Research Question:** How do loyalty program membership and coupon usage frequency impact the cart abandonment rate?
* **Methodology:** A **Two-Way ANOVA** model was utilized to examine the causal inference between promotional tactics and cart abandonment rate.
* **Findings & Implications:** Loyalty programs and coupon usage showed no significant impact (p-values > 0.05). E-commerce platforms should not rely on current promotional distributions as the primary strategy to reduce cart abandonment.

## Phase 2: The Impact of UI/UX Friction (Device Type & Payment Method)
* **Research Question:** How do device type and preferred payment method impact the cart abandonment rate?
* **Methodology:** A subsequent **Two-Way ANOVA** was applied to test whether technical and financial frictions act as the true drivers of abandonment.
* **Findings & Implications:** There is a marginally significant interaction effect (p-value = 0.0565) between device type and payment method. Management is advised to conduct targeted UI/UX testing on cross-platform payment flows rather than investing further in promotional discounts.

## Tools & Skills Demonstrated
* **R / R Markdown:** Clean code with detailed comments, reproducible research, and professional HTML/PDF reporting.
* **Statistical Methods:** Two-Way ANOVA, Causal Inference.
* **Data Visualization:** `ggplot2` (Boxplots, Interaction plots).

> *Please view the attached `.pdf` / `.html` files in this repository to read the full code, mathematical equations, and data visualizations.*
