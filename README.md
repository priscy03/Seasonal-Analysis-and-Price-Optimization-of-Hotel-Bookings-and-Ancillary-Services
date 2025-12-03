# Seasonal-Analysis-and-Price-Optimization-of-Hotel-Bookings-and-Ancillary-Services

# Project Background

Grand Meridian Hotel (GMH), a four-star hotel, opened its doors in 2004 in one of the historic cities of England. Designed to blend modern comfort with classic Georgian architecture, the hotel quickly became popular with both business travelers attending regional conferences and leisure guests drawn to the city’s cultural attractions.

Over the past two decades, GMH has expanded modestly, now offering 182 guest rooms, a small but well-equipped conference suite, an on-site bistro, and a spa treatment room. The hotel positions itself as a premium option for visitors who value personalized service, central location, and a more intimate atmosphere compared to large chain hotels

Despite maintaining strong occupancy, management struggled to pinpoint which guest segments and if pricing strategies drove the most profit. This project was initiated to uncover revenue performance patterns across room types, booking channels, and guest segments, assess the impact of discounts and seasonal adjustments, and develop an approach to strategic pricing, marketing focus, and long-term revenue optimization.

Insights and recommendations are provided on the following key areas:

•	Possible missed opportunities to focus on the most profitable segment.

•	Marketing funds may be diluted by targeting both segments equally.

•	Service offerings may not align with the highest-value guest preferences.

An interactive Tableau dashboard used to report and explore revenue and pricing trends can be found here [(https://public.tableau.com/views/SeasonalAnalysisandPriceOptimizationofHotelBookingsandAncillaryServices/PricingDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)].

# Data Structure & Initial Checks

Grand Meridian Hotel database structure as seen below consists of three tables: Hotel-Bookings, Ancillary _Services, Room _Rates Table, with a total row count of 12,397 records.

A description of each table is as follows:

• Table 1: hotel_bookings_data

• Table 2: ancillary _services

• Table 3: room _rates

<img width="610" height="183" alt="image" src="https://github.com/user-attachments/assets/79062bfc-0cee-4cf5-9f7f-e3125cb6157d" />

# Executive Summary

•	This project analyzed GMH’s hotel performance to understand revenue drivers, guest segmentation, and the impact of pricing strategies.

•	Through analysis identified that room revenue dominates, ancillary services are underutilized, and discounts dilute profitability without boosting revenue.

•	Corporate guests remain the most stable segment, while leisure guests show strong seasonality but lower yield.

•	The findings highlight opportunities to optimize pricing, strengthen direct bookings, and grow ancillary revenue for improved profitability.



The following sections will expand on general overview the hotel bookings data, optimize pricing, and grow ancillary revenue for improved profitability. 

# Insights Deep Dive

## Overview

Number of Guest – 6,888

Guest Segments: Leisure guests dominate (60%) compared to corporate (40%)

Booking Channels: Online and OTA channels are strong contributors, with Direct trailing.

Loyalty Members: Only ~21% of guests are loyalty member’s; weak retention.

Ancillary Services: Dining (35%) is the biggest contributor, followed by Events and Spa.

Room types Occupation: Guest use standard rooms (~45.14%) predominantly followed by deluxe (~33.09%) and suites (~21.78%) respectively.

# Revenue Analysis


<img width="666" height="98" alt="image" src="https://github.com/user-attachments/assets/6c3c24aa-bd0e-44e8-962a-dcae4c4e7235" />


Key indicators ;

Total Revenue: £11.9M (Rooms + Ancillary).

ADR (Average Daily Rate): £240.74,

Occupancy: 68.7%;

•	The room rates are high, suggesting the hotel attracts guests willing to pay premium prices, a sign of pricing strength.

•	However, the occupancy below 70% implies that demand elasticity is at play i.e., raising or maintaining high rates may be suppressing bookings slightly.

RevPAR: £165.48; 

•Healthy but not maximized; it reflects that revenue per available room is solid, yet occupancy constraints prevent stronger returns.


<img width="625" height="113" alt="image" src="https://github.com/user-attachments/assets/febd0aad-d4b9-458f-a2b8-fd7eb43c4254" />


Segment Performance

•	Leisure guests contribute ~53% of total revenue, slightly higher than corporate guests (~47%).

•	Corporate RevPAR trends upward until June, dips mid-year (June–November), and recovers towards year-end, aligning with Leisure RevPAR — indicating seasonal demand differences.

•	Both segments peak in June, suggesting this is the hotel’s high season


<img width="625" height="117" alt="image" src="https://github.com/user-attachments/assets/9fa5315c-17f4-418a-a863-95fcd9b7b02a" />

Revenue & Occupancy Trends

•	From January to August, occupancy outpaces revenue, suggesting discounting or low-rate bookings during high-demand months.

•	From August to December, revenue and occupancy align, showing improved pricing consistency and possibly reduced discounting.

Revenue by Room Type

•	Suites generate the highest revenue, followed by Deluxe Rooms, with Standard Rooms contributing the least, this reflects value of rooms surpass the frequency of use.


<img width="975" height="179" alt="image" src="https://github.com/user-attachments/assets/f6dab168-9b44-4170-b23d-8e60def48f28" />

•	The hotel is overly dependent on room sales, with ancillary services underutilized.

•	Expanding non-room revenue streams (spa, dining, events, transport) could:

o	Enhance total revenue per guest,

o	Smooth out seasonal fluctuations,

o	Increase guest retention through experience-based offerings.


# Pricing Analysis 


<img width="625" height="112" alt="image" src="https://github.com/user-attachments/assets/ea8d6db2-74b2-45ce-9007-61dc7b7db7df" />


•	Suites clearly dominate the ADR structure , occupying the largest block, showing not the highest price point as it has the least frequency in use .Deluxe rooms follow, while Standard rooms significantly lag behind.

GMH’s pricing ladder is functioning well at the top end (Suite & Deluxe), but Standard rooms may be priced too low or lack value perception, pulling down overall ADR performance.

•	There is no Positive Relationship Between Discounts and Revenue (Revenue vs Discount %) ; Corporate and leisure both show no clear upward pattern as discounts increase.

o	Leisure revenue drops sharply at ~2–3% discount.

o	Corporate revenue remains flat and unresponsive to discounting.

Implication:

Discounts are not driving incremental revenue. The £140K discount adjustments are not generating significant uplift ; meaning GMH is giving away rate without gaining demand volume.


<img width="624" height="103" alt="image" src="https://github.com/user-attachments/assets/dc9ac1a6-1222-4d6f-999d-d9391817f97b" />

LOS does not influence ADR (ADR vs LOS);

•	Both corporate and leisure LOS clusters are tight and flat.

•	ADR remains similar regardless of whether a guest stays 1 night or 7 nights.

GMH is not using LOS-based pricing, which is a missed opportunity


ADR Stability with Seasonal Dips (ADR Trend)

•	ADR dips noticeably around February to May (£155.89)

•	It then stabilizes for the rest of the year, with a consistent premium level above £220.

 Early-year dip suggests a shoulder-season pricing opportunity



<img width="975" height="176" alt="image" src="https://github.com/user-attachments/assets/6f449a24-44ff-445a-9831-19e2049cd499" />


•  Discounts are cutting noticeably into finalized revenue.

•  Seasonal adjustments appear minimal meaning GMH may not be leveraging seasonal uplift fully.

This may imply  the hotel is not maximizing peak-season pricing and / or over-relying on discounts across Standard and Deluxe rooms to boost revenue


# Stratigic Recommendation 

## Revenue 

1.Improve Occupancy While Keeping Rates High

•	Introduce off-peak promotions and value-added packages (not discounts).

•	Use advance-purchase and weekday offers to fill low-demand months.

2. Tighten Pricing Consistency
   
•	Reduce early-year discounting by applying stronger rate fences and dynamic pricing.

•	Adjust rates based on seasonal patterns (peak in June, mid-year dip).

3. Strengthen Corporate Segment
   
•	Offer mid-year corporate incentives and renegotiate contract rates.

•	Build partnerships with travel management companies to stabilize demand.

4. Maximize High-Value Room Types

•	Push upselling for Suites and Deluxe Rooms through digital and front-desk prompts.

•	Create premium experience packages to lift average spend.

5. Grow Ancillary Revenue

•	Expand promotions for F&B, spa, events, and local experience add-ons.

•	Assign monthly ancillary revenue targets for each department.

6. Refine Segment & Seasonal Marketing

•	Launch early summer campaigns for leisure.

•	Target corporate groups and events during low months.

7. Improve Performance of Standard Rooms
   
•	Minor upgrades + bundle them in value packages to boost occupancy.


## Pricing 

1. Reduce Ineffective Discounting
   
Discounts are not increasing revenue ; GMH should limit broad discounts and replace them with targeted or value-add offers.

2. Adjust Standard Room Pricing
   
Standard rooms are dragging ADR; increase rates slightly or enhance value to strengthen the pricing ladder.

3. Introduce LOS-Based Pricing

ADR is flat across lengths of stay ; implement multi-night pricing or perks to boost revenue from longer stays.

4. Maximize Peak-Season Rates
   
Increase Suite and Deluxe rates during high-demand months where ADR remains strong.

5. Address Early-Year ADR Dip
   
Create seasonal packages and promotions (not discounts) to lift revenue between February and May.

6. Increase Suite Utilization

Promote upsells and packages to increase occupancy of high-margin Suites.

7. Strengthen Seasonal and Event-Based Pricing
   
Use dynamic price adjustments for peak periods, weekends, and events to better capture demand.

________________________________________

### Assumptions
These are conditions assumed to be true for the analysis to hold.

1. One Year of Data Represents Normal Operations
   
We assume the single year of data is typical and not affected by unusual events (renovations, city-wide disruptions, etc.).

2. Room Inventory Stays Constant (182 rooms)

We assume all rooms were available throughout the year (no closures or maintenance downtime).

3. Guest Segments (Corporate vs Leisure) Are Correctly Labeled

We assume bookings are correctly tagged by guest type and not misclassified.

4. ADR, RevPAR, LOS Calculations Follow Industry Standards

We assume standard formulas apply:

•	ADR = Total Room Revenue ÷ Rooms Sold

•	RevPAR = Total Room Revenue ÷ Total Available Rooms

________________________________________

### 🔶 Caveats (Limitations)
These are factors that may restrict the accuracy, completeness, or generalizability of your findings.

1. Only Revenue Data Provided — No Cost or Profit Data
   
We cannot evaluate profitability, only revenue performance.

2. No Visibility of Competitors or Market Rates

Pricing recommendations are made without benchmarking against the local market.

3. Single-Year Data Limits Seasonal Accuracy
   
Without multiple years, seasonal insights may be affected by abnormal events.

4. Discount Impact Not Segmented by Type
   
We cannot distinguish between:

•	corporate negotiated rates

•	seasonal promotions

•	occupancy-driven markdowns

Therefore, “discount effect” is averaged and may mask segment-level realities.



















 

