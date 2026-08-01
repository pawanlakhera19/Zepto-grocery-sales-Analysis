## ZEPTO GROCERY SALES ANALYSIS

An Excel-based sales analysis project on Zepto's grocery dataset, uncovering revenue drivers, outlet performance, and customer rating patterns across item types, tiers, and store formats.

## THE CHALLENGE I IDENTIFIED
Zepto's grocery sales data was scattered across raw transaction-level records with no clear view of what was actually driving revenue. I wanted to break down the ₹9L+ in sales by item category, outlet size, location tier, and store type to figure out where the real business value was coming from, and where it wasn't.

## WHAT I WORKED WITH
- 8,523 records across 14 columns
- Key fields: Item Fat Content, Item Type, Item Weight, Item Visibility, Outlet Identifier, Outlet Establishment Year, Outlet Location Type (Tier 1/2/3), Outlet Size, Outlet Type, Sales, Rating, Profit
- Tool: Microsoft Excel (PivotTables + PivotCharts for the dashboard)

## HOW I PREPARED THE DATA
I checked the raw data for consistency issues across categorical fields (fat content labels, outlet type naming) before building pivot tables on top of it. I structured the sheet into a clean raw-data layer separate from the dashboard/reporting layer, so the pivots stay dynamic and easy to refresh. I built summary PivotTables for sales by fat content, item type, outlet establishment year, outlet size, location tier, and outlet type, each feeding directly into the dashboard visuals.

## WHAT I FOUND
- Total Sales: ₹9,02,122 across 6,390 items sold, with an average customer rating of 3.97
- Supermarket Type1 is the clear revenue engine, ₹5,90,188 in sales from 4,186 transactions, dwarfing Grocery Store (₹1,14,720), Supermarket Type2 (₹98,944), and Supermarket Type3 (₹98,269)
- I noticed that Tier-3 cities outperform Tier-1, ₹3,53,540 vs ₹2,51,949, which challenged my assumption that bigger cities would naturally drive more sales
- Medium-sized outlets lead overall sales (₹3,76,137), ahead of Small (₹3,32,646) and High (₹1,93,339) outlets
- Low Fat items outsell Regular items by nearly 2:1 (₹5,82,657 vs ₹3,19,465), and this gap holds consistently across all three location tiers
- Snack Foods, Household, and Frozen Foods are the top-selling item categories, while Breakfast and Hard Drinks sit at the bottom of the revenue list
- Outlets established in 2018 posted the single highest sales figure by establishment year (₹1,53,757), notably ahead of every other year in the dataset

## WHAT I RECOMMENDED
I recommend doubling down on the Supermarket Type1 format given its outsized share of both sales volume and transaction count. I recommend re-evaluating expansion assumptions that favor Tier-1 cities, since Tier-3 outlets are already outperforming them here. I recommend prioritizing shelf space and stock depth for Snack Foods, Household, and Frozen Foods categories, while re-assessing the low-performing Breakfast and Hard Drinks segments.

## TOOLS I USED
Microsoft Excel (PivotTables, PivotCharts, dashboard design)

## WHAT I LEARNED
I learned that intuitive assumptions about city tiers and store size don't always hold up once you actually break the numbers down. I realized how much a clean pivot-table structure simplifies building a multi-view dashboard from a single raw dataset.

---
This is a self-driven project, built independently to strengthen Excel-based data analysis and dashboard storytelling skills.
LinkedIn: https://www.linkedin.com/in/pawan-lakhera-738429174
GitHub: https://github.com/pawanlakhera49
