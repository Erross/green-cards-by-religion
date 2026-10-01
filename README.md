# Green Cards by Faith Majority

An interactive page charting U.S. green cards and immigrant visas grouped by the religious majority of each person's country of birth.

**Live page:** https://erross.github.io/green-cards-by-religion/

## What's in it

1. **Green cards (lawful permanent residents), FY2011–FY2024.** One chart with all groups, a totals table, and one chart per group showing its largest countries. Source: DHS Office of Homeland Security Statistics, Yearbook of Immigration Statistics, Table 3 (persons obtaining LPR status by country of birth). FY2011–14 from the 2020 Yearbook, FY2015–24 from the 2024 Yearbook.
2. **Immigrant visas issued abroad, monthly, March 2017–February 2026.** Source: U.S. State Department, Monthly Immigrant Visa Issuance Statistics, by foreign state of chargeability. This is a different count: it covers only people processed at consulates overseas (roughly half of all green cards) and excludes adjustment of status inside the U.S. (refugees, asylees, parolees, most employment cases). September 2020 was never published. Each month was checked against its published grand total.

Dashed vertical lines mark presidential inaugurations. Lettered markers on the visa chart flag the March 2020 COVID suspension, the June 9, 2025 entry ban, and the January 21, 2026 pause on immigrant visas for 75 countries.

## Method

- Each country is tagged by the faith held by more than 50% of its population, using Pew Research Center's *Global Religious Landscape* (2010) estimates, held fixed across all years. Countries with no group above 50% (e.g. Nigeria, Vietnam, South Korea, Taiwan) are "No majority".
- Country of birth is not the person's religion. This shows where people come from, not what they believe.
- Not classified: "Unknown", "All other countries", births in the former USSR or Czechoslovakia, and the U.S. country-of-birth row.

## Data files

- `data/dhs_green_cards_by_group.csv` — annual green cards by group, FY2011–2024
- `data/state_immigrant_visas_monthly_by_group.csv` — monthly immigrant visas by group, 2017-03 to 2026-02

## Sources

- [DHS OHSS Yearbook 2024](https://ohss.dhs.gov/topics/immigration/yearbook/2024) and [Yearbook 2020](https://ohss.dhs.gov/topics/immigration/yearbook/2020)
- [State Department, Monthly Immigrant Visa Issuance Statistics](https://travel.state.gov/content/travel/en/legal/visa-law0/visa-statistics/immigrant-visa-statistics/monthly-immigrant-visa-issuances.html)
- [Pew Research Center, The Global Religious Landscape](https://www.pewresearch.org/religion/2012/12/18/global-religious-landscape-exec/)
