### Briefing on Archived Fruit and Vegetable Price Data

This briefing provides a detailed analysis of archived price data for selected fruits and vegetables from 2020 to 2022. The data is contextualized by an archived study from the USDA, Economic Research Service's (ERS) Fruit and Vegetable Prices data product, which examined the effect of replacing calorie-dense snacks with fruits or vegetables on household food budgets and caloric intake.

The original study, published in 2012, used Nielsen's 2010 Homescan panel data to show that such substitutions could reduce a child's caloric intake and potentially save a household money. The analysis below extends this perspective by examining how the retail and cup-equivalent prices of these items have changed in recent years, which would directly impact the budgetary effects discussed in the original research.

-----

### Methodology

The analysis was conducted using two pairs of CSV files, `Fruit-Prices-2020.csv` and `Fruit-Prices-2022.csv`, and `Vegetable-Prices-2020.csv` and `Vegetable-Prices-2022.csv`. Each file contains retail price and cup-equivalent price data for a consistent list of items.

The methodology for this briefing included the following steps:

1.  **Data Integration**: The 2020 and 2022 data for fruits and vegetables were combined into separate datasets.
2.  **Price Change Calculation**: The percentage change for both `RetailPrice` (price per pound or pint) and `CupEquivalentPrice` (price per half-cup serving) was calculated for each item between 2020 and 2022.
3.  **Trend Identification**: The average price changes were calculated for each category, and the items with the highest and lowest price changes were identified to highlight specific trends.

-----

### Key Findings and Analysis

The analysis reveals a **broad increase in the prices of fruits and vegetables** from 2020 to 2022, which would likely affect the budgetary implications of the snack substitution model proposed in the original USDA, ERS study.

#### Fruit Price Trends

The average retail price for fruits increased by **15.32%** between 2020 and 2022. The average cup-equivalent price showed a similar increase of **15.32%**. This suggests that, on average, the cost of a half-cup serving of fruit grew proportionally to its retail price.

  * **Highest Price Increases**: The most significant price hikes were observed in frozen and canned fruits. **Frozen raspberries** saw the largest increase, with a retail price increase of approximately **47.07%**. Other notable increases were for `Canned fruit cocktail` and `Fresh cherries`, which increased by **39.21%** and **36.08%** respectively.
  * **Price Decreases/Stability**: A few fruit items experienced price reductions or minimal changes. `Frozen concentrated oranges` had the most notable decrease, with a **-4.58%** change. `Dried mangoes` also saw a slight price drop of **-2.37%**.

#### Vegetable Price Trends

The price of vegetables also saw a significant increase, though slightly less than fruits on average. The average retail price and cup-equivalent price for vegetables increased by **12.45%** between 2020 and 2022.

  * **Highest Price Increases**: The most substantial price increases were seen in fresh leafy greens. **Fresh spinach** (both boiled and eaten raw forms) and **fresh kale** both increased by over **37%**. **Fresh broccoli** also experienced a major increase of over **33%**. This suggests that fresh produce, particularly items like leafy greens, have been subject to higher inflationary pressures.
  * **Price Decreases**: Several items, primarily canned vegetables, showed a decrease in price. **Fresh red peppers** had the most significant decrease, dropping by **-13.28%**. Canned items such as **beets** (-9.89%), **pumpkin** (-7.59%), and **olives** (-7.32%) also became less expensive relative to 2020.

-----

### Overall Conclusion

The consistent upward trend in fruit and vegetable prices from 2020 to 2022 highlights a potential shift in the economic landscape since the original 2012 USDA study. The average increases of over 12% for both categories suggest that replacing snacks with fresh produce may have become a more significant budgetary consideration for households. While some specific items, particularly canned vegetables, saw price decreases, the overall trend indicates that the cost-saving benefit of snack substitution may have diminished since the original study, even as the caloric benefits remain constant. This analysis suggests that a follow-up study on the current budgetary impact of snack substitutions is warranted to provide up-to-date guidance to households.
