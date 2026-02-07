# Silent Shoppers: High-Value Infrequent Customer Segmentation & Basket Insights

## Overview
This project identifies “Silent Shoppers” — customers who shop infrequently but spend high amounts per visit — and converts their behavioural patterns into practical strategies to increase visit frequency. It combines transaction/basket analytics, customer segmentation, and basket/category clustering to support loyalty design, personalised promotions, and retention planning.

## Business Question
Who are the customers who shop infrequently but spend large amounts per visit, and how can we encourage more frequent engagement from this group?

## Data
- Transactional basket data with Basket ID, Barcode, Total Spend, Total Units, and Card ID.
- Product categories/subcategories mapped through barcodes.
- Derived analysis tables linking cards to baskets, baskets to category mixes, and customers to segmentation labels (Excel outputs).

## Methodology

### 1) Defining Silent Shoppers (High-Value Infrequent Customers)
Customers were segmented using a dual rule:
- Infrequent: bottom 25% of customers by visit frequency.
- High value: top 25% by average spend per transaction.

### 2) Core Metrics and Profiling
- Measured total revenue and revenue concentration from Silent Shoppers.
- Compared basket size and basket value of Silent Shoppers vs overall customers.
- Built category-level revenue contribution to understand product preference.

### 3) Basket Segmentation (Mission-Based Clusters)
Baskets were grouped based on category participation patterns to interpret shopping missions such as:
- Perishable Buyers
- Dairy Dominant
- Snacks & Drinks
- MixMatch Shoppers
- Household Essential Shopper
- Grocery Shoppers
- Cleanliness Enthusiasts

These clusters support mission-aligned offers rather than generic discounts.

### 4) Customer Affinity Segmentation
Customer groups were characterised using affinity scoring across categories (e.g., essentials-focused vs detergent-heavy vs fresh-focused), enabling targeted promotions and shelf/space prioritisation.

## Key Insights
- Silent Shoppers contribute a disproportionately large share of revenue despite low visit frequency.
- Their baskets are larger and higher value than the overall customer base.
- They prioritise fresh categories (especially Meat & Seafood and Dairy), with meaningful add-on demand in Snacks/Beverages and steady needs in Household and Health/Hygiene.
- Basket clusters reveal repeatable “shopping missions,” enabling more precise engagement tactics.

## Recommended Actions
- Frequency-based loyalty rewards (not only spend-based) focused on relevant high-margin categories.
- Mission-based bundles that match how Silent Shoppers shop (fresh + add-ons, essentials + replenishment).
- Personalised campaigns for the most represented demographic patterns (household and family-focused messaging).
- Convenience engagement (subscription/replenishment prompts for household and hygiene categories).
- Upselling through premium seasonal packs and limited-time curated offers.

## Outcome
A decision-focused segmentation that isolates a high-impact customer group, quantifies its value, explains what they buy and why, and proposes actionable interventions to increase engagement frequency without relying on blanket discounting.
