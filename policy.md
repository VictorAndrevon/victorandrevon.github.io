---
layout: post
title: "Who Was Left Behind? Business Recovery, Policy, and Inequality"
date: 2025-04-30
permalink: /policy/
show_excerpts: false
---

![Shuttered storefront in Tremont](assets/images/bronx_shuttered.jpg)

# Who Was Left Behind?

While headlines touted New York City’s comeback, not every community felt the recovery equally. From minority-owned businesses in the Bronx to immigrant-run storefronts in Flushing, many entrepreneurs found themselves locked out of aid, delayed in reopening, or left to navigate a broken safety net.

Using a combination of NYC Open Data, demographic census data, and spatial business license trends, we ask a difficult but necessary question: **Who was left behind?**

---

## Policy on Paper, Gaps in Practice

Billions were allocated to support small businesses post-COVID—from federal PPP loans to New York’s SBS neighborhood grant programs. But as [the NYC Comptroller’s MWBE Recovery Report](https://comptroller.nyc.gov/reports/minority-and-women-owned-businesses-at-risk-impact-of-covid-19-on-new-york-city-firms/) highlights, Minority- and Women-Owned Business Enterprises (MWBEs) received just a fraction of the support relative to their need.

> “While Black-owned businesses accounted for 26% of all small businesses pre-pandemic in NYC, they received only 4.8% of federal relief dollars.”  
> – NYC Comptroller, 2023

---

## Where Aid Missed the Mark

Using geospatial mapping of NYC business license data and SBA/PPP coverage by zip code, we identified stark mismatches between **aid availability** and **community need**.

<iframe src="/assets/images/aid_vs_race.html" style="width:100%; height: 600px; border:none;"></iframe>

**Observations:**
- Several neighborhoods with large Black and Hispanic populations received below-median levels of aid.
- Aid was concentrated in commercial corridors with more access to financial infrastructure (banks, accountants, etc.)
- Language barriers and digital exclusion hindered immigrant-owned businesses from applying.

---

## A Tale Told by Demographics

We merged business license losses with ACS racial/ethnic and income data per NTA (Neighborhood Tabulation Area).

| Neighborhood | Majority Race/Ethnicity | Median Income | License Loss % |
|--------------|--------------------------|----------------|----------------|
| Tremont–Morrisania | Black/Hispanic | $29,800 | -58.4% |
| Chinatown–LES       | Asian | $36,200 | -49.7% |
| SoHo–Tribeca        | White | $110,000 | -14.2% |
| Flatbush            | Black/Caribbean | $42,000 | -45.9% |

> 🔎 These disparities highlight how COVID-19 intersected with long-standing structural inequalities—not just in health, but in economic recovery.

---

## Race, Income, and Recovery: A Crossplot

We visualized the correlation between median income, racial makeup, and business license loss at the neighborhood level.

<iframe src="/assets/images/race_income_closures.html" style="width:100%; height: 600px; border:none;"></iframe>

Key trends:
- NTAs with higher proportions of Black and Hispanic residents saw steeper declines.
- Recovery was positively correlated with income and pre-existing commercial capital.

---

## Policy Lessons from the Fallout

The data leaves little doubt: **Universal aid was not universally felt.** If future crises are to be met equitably, targeted recovery frameworks must:

- **Partner with local BIDs and MWBE networks** to distribute aid.
- **Expand language access and digital tools** in immigrant-heavy neighborhoods.
- **Overlay demographic and commercial data** when designing policy zones.

As SBS Commissioner Dynishal Gross said:

> “Policies and programs that make it possible for small businesses to operate successfully in neighborhood commercial spaces contribute to safety, lead to job creation and help entrepreneurial New Yorkers live out their dreams.”

---

## The Path Forward

If we want a just recovery, we must **build economic resilience where it was weakest**. The story isn’t just about recovery—it’s about redesigning the systems that failed when New Yorkers needed them most.

> Recovery is a verb. For many communities, it hasn’t happened yet.

---

### Last updated: 30 April 2025  
*Created for DTU Social Data 2025 — Final Project (“The Viz & the Notebook”)*

**Authors:** Anshjyot Singh (s215806) & Victor Jules René Andrevon-Canut (s232481)

---

### Sources

- [NYC Open Data - Issued Business Licenses](https://data.cityofnewyork.us/Business/Issued-Licenses/w7w3-xahh)  
- [NYC Comptroller – MWBE Recovery Report](https://comptroller.nyc.gov/reports/minority-and-women-owned-businesses-at-risk-impact-of-covid-19-on-new-york-city-firms/)  
- [ACS Demographics – 2020](https://www.census.gov/programs-surveys/acs)  
- [Federal Reserve Bank of NY – COVID Business Impact](https://www.newyorkfed.org/)  
- [SBA PPP Distribution Data](https://data.sba.gov/)
