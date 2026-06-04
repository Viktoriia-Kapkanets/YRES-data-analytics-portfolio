# YRES Signup & Coaching Analysis — Tableau

> Interactive Tableau dashboards built for YRES, a Canadian youth services 
> nonprofit, analyzing volunteer signup patterns and 1:1 coaching engagement.

## Live dashboards

These are part of a recurring weekly reporting series — sample weeks are 
published on Tableau Public:

📊 **[Volunteer Signup Analysis](link-to-tableau)** — multi-dimensional view 
across geography, day of week, time, placement type, age range, and referral

📊 **[1:1 Coaching Engagement Report](link-to-tableau)** — daily session 
tracking, weekly trends, running totals, and cancellation breakdowns 
across BC/AB and ON Volunteer Success Programs

## Business questions

**Signup analysis:** Where are YRES volunteers coming from (geographic, 
demographic, referral), and when do they typically register? This informs 
recruitment channel investment and timing of outreach campaigns.

**Coaching engagement:** How is 1:1 coaching uptake trending across the 
two regional programs? Where are cancellations clustering, and what's the 
running cumulative engagement?

## Approach

[here describe: tabbed multi-page structure, calculated fields you used, 
maps with custom geographic role assignments, color-coding by province, etc.]

## Techniques demonstrated

- **Multi-tab dashboard architecture** — separate analytical views (Total, 
  Province, City, Day, Time, Placement, Age, Referral) within one workbook
- **Geographic mapping** — Canadian province / city visualization with 
  custom color encoding
- **Calculated fields** — derived dimensions for time-of-day bucketing, 
  province grouping, referral source categorization
- **Cross-tab filtering** — slicer/parameter actions that filter across tabs

## Screenshots

![Dashboard overview](/screenshots/01_signup-overview.png)

## Data and privacy

Published with permission from YRES. No participant names, contact info, 
or identifying details are visible in any visualization.
