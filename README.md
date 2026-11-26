---
license: cc-by-4.0
language:
- en
pretty_name: US online TRT clinic prices
tags:
- testosterone
- trt
- testosterone-replacement-therapy
- telehealth
- healthcare-prices
- mens-health
size_categories:
- n<1K
configs:
- config_name: prices
  data_files: trt-clinic-prices.csv
- config_name: first_year_cost
  data_files: trt-first-year-cost.csv
---

# US online TRT clinic prices

What US online testosterone replacement therapy (TRT) clinics charge in cash, and what a first year at each one comes to once its required membership, lab work and fees are added. Every figure is read on the clinic's own website, quoted in its own words, and dated. Published by [TRTcompare.co](https://trtcompare.co/data), which re-reads the clinics and keeps the live copy current; this repository holds the snapshot of **2026-11-25**.

- **64 cash prices** from **32 clinics**: testosterone injections, cream and oral capsules, enclomiphene, clomiphene, hCG and anastrozole (`trt-clinic-prices.csv`).
- **First-year cost at 28 clinics**, cheapest first, each total broken into medicine, membership, labs and fees, with the clinic's Trustpilot score, BBB grade and FDA warning letters (`trt-first-year-cost.csv`).
- Both tables with the column dictionary and the license in one file (`trt-clinic-prices.json`).

## The cheapest first years

The middle clinic comes to $1,788 a year; the dearest is Hendrx Health at $4,740.

| # | Clinic | First year | Advertised price | Trustpilot |
|---|---|---|---|---|
| 1 | [Hone Health](https://trtcompare.co/providers/hone-health) | from $701 | from $28/mo + membership | 4.8 (12,562 reviews) |
| 2 | [Vyta](https://trtcompare.co/providers/vyta) | $1,308 | $109/mo | 4 (4 reviews) |
| 3 | [Yes Clinic](https://trtcompare.co/providers/yes-clinic) | $1,320 | $110/mo | no rated profile |
| 4 | [TRT Nation](https://trtcompare.co/providers/trt-nation) | $1,329 | $99.99/mo, 2.5-month minimum | 2.2 (33 reviews) |
| 5 | [Atlas HRT](https://trtcompare.co/providers/atlas-hrt) | from $1,353 | from $92/mo | no rated profile |
| 6 | [Matrix Reformed](https://trtcompare.co/providers/matrix-reformed) | $1,440 | $120/mo | no rated profile |
| 7 | [TRT Kingdom](https://trtcompare.co/providers/trt-kingdom) | $1,486 | $99/mo | no rated profile |
| 8 | [DudeMeds](https://trtcompare.co/providers/dudemeds) | $1,499 | $345 per 84 days | 2.3 (11 reviews) |
| 9 | [Hims](https://trtcompare.co/providers/hims) | from $1,536 | from $79/mo + Care+ | 2.9 (9,829 reviews) |
| 10 | [Fridays](https://trtcompare.co/providers/fridays) | from $1,548 | from $129/mo | 4.2 (5,495 reviews) |

A first year is twelve months of the clinic's cheapest month-to-month testosterone (its shortest plan where it sells no monthly one), plus any membership the medicine cannot be had without, the first labs, the later panels its page prices within the year, and its fixed fees. Whatever a clinic's page leaves unpriced is named in `not_priced`, never guessed. Prepaid plans are given beside the total, not ranked.

## Every clinic in the data

Each clinic's page on TRTcompare.co sets its prices in context, with its public record and its terms:

- **AlphaMD**: [prices and plans](https://trtcompare.co/providers/alphamd), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/alphamd/legit)
- **ARSYNL Rx**: [prices and plans](https://trtcompare.co/providers/arsynl-rx), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/arsynl-rx/legit)
- **Atlas HRT**: [prices and plans](https://trtcompare.co/providers/atlas-hrt), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/atlas-hrt/legit)
- **Blokes**: [prices and plans](https://trtcompare.co/providers/blokes), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/blokes/legit)
- **BrightMeds**: [prices and plans](https://trtcompare.co/providers/brightmeds), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/brightmeds/legit)
- **Defy Medical**: [prices and plans](https://trtcompare.co/providers/defy-medical), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/defy-medical/legit)
- **DudeMeds**: [prices and plans](https://trtcompare.co/providers/dudemeds), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/dudemeds/legit)
- **FEEL30**: [prices and plans](https://trtcompare.co/providers/feel30), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/feel30/legit)
- **Fountain TRT**: [prices and plans](https://trtcompare.co/providers/fountain-trt), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/fountain-trt/legit)
- **Fridays**: [prices and plans](https://trtcompare.co/providers/fridays), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/fridays/legit)
- **GobyMeds**: [prices and plans](https://trtcompare.co/providers/gobymeds), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/gobymeds/legit)
- **Hendrx Health**: [prices and plans](https://trtcompare.co/providers/hendrx-health), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/hendrx-health/legit)
- **Henry Meds**: [prices and plans](https://trtcompare.co/providers/henry-meds), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/henry-meds/legit)
- **Heva Health**: [prices and plans](https://trtcompare.co/providers/heva-health), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/heva-health/legit)
- **Hims**: [prices and plans](https://trtcompare.co/providers/hims), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/hims/legit)
- **Hone Health**: [prices and plans](https://trtcompare.co/providers/hone-health), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/hone-health/legit)
- **Male Excel**: [prices and plans](https://trtcompare.co/providers/male-excel), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/male-excel/legit)
- **MangoRx**: [prices and plans](https://trtcompare.co/providers/mangorx), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/mangorx/legit)
- **Marek Health**: [prices and plans](https://trtcompare.co/providers/marek-health), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/marek-health/legit)
- **Matrix Reformed**: [prices and plans](https://trtcompare.co/providers/matrix-reformed), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/matrix-reformed/legit)
- **Maximus**: [prices and plans](https://trtcompare.co/providers/maximus), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/maximus/legit)
- **PeterMD**: [prices and plans](https://trtcompare.co/providers/petermd), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/petermd/legit)
- **Precision Telemed**: [prices and plans](https://trtcompare.co/providers/precision-telemed), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/precision-telemed/legit)
- **Rex MD**: [prices and plans](https://trtcompare.co/providers/rex-md), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/rex-md/legit)
- **Strut Health**: [prices and plans](https://trtcompare.co/providers/strut-health), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/strut-health/legit)
- **Taurus Meds**: [prices and plans](https://trtcompare.co/providers/taurus-meds), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/taurus-meds/legit)
- **Tonik Wellness**: [prices and plans](https://trtcompare.co/providers/tonik-wellness), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/tonik-wellness/legit)
- **TRT Kingdom**: [prices and plans](https://trtcompare.co/providers/trt-kingdom), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/trt-kingdom/legit)
- **TRT Nation**: [prices and plans](https://trtcompare.co/providers/trt-nation), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/trt-nation/legit)
- **TRTBOSS**: [prices and plans](https://trtcompare.co/providers/trtboss), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/trtboss/legit)
- **Tuyo Health**: [prices and plans](https://trtcompare.co/providers/tuyo-health), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/tuyo-health/legit)
- **Vyta**: [prices and plans](https://trtcompare.co/providers/vyta), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/vyta/legit)
- **Ways2Well**: [prices and plans](https://trtcompare.co/providers/ways2well), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/ways2well/legit)
- **Yes Clinic**: [prices and plans](https://trtcompare.co/providers/yes-clinic), [is it legit (Trustpilot, BBB, FDA)](https://trtcompare.co/providers/yes-clinic/legit)

Side-by-side pages for the clinics men weigh against each other (Maximus vs Hims, PeterMD vs Maximus, Taurus Meds vs Hims and more) are at https://trtcompare.co/providers/compare, the best clinics by a stated rule at https://trtcompare.co/best/online-trt-clinics, and every first year at https://trtcompare.co/cheapest/online-trt-clinics.

## Live access for AI assistants and apps

The same data is served live, with no key:

- **MCP server** (Streamable HTTP): `https://trtcompare.co/api/mcp`, registry name `co.trtcompare/trt-clinic-prices`. Tools: `compare_trt_clinics`, `get_trt_clinic`, `find_trt_prices`.
- **Web API** (OpenAPI 3.1): `https://trtcompare.co/openapi.json`, for example `GET https://trtcompare.co/api/v1/clinics?state=TX`.
- **Current files**: https://trtcompare.co/data/trt-clinic-prices.csv and https://trtcompare.co/data/trt-first-year-cost.csv

## Columns: trt-clinic-prices.csv

| Column | Meaning |
|---|---|
| `quote_id` | Stable identifier for the quote (clinic and product). |
| `clinic` | The online clinic that sells it. |
| `product` | The product as the clinic offers it, e.g. "Testosterone cypionate injections via Taurus Meds". |
| `medicine` | Testosterone, Enclomiphene, Clomiphene, hCG or Anastrozole. |
| `form` | injection, topical (cream or gel), capsule or tablet, when stated. |
| `compounded` | yes where the clinic says the product is compounded (every enclomiphene is). Compounded medicines are not FDA-approved. |
| `fda_approved` | yes where the clinic's page says FDA-approved or commercially made, or names an approved brand; no for compounded products and enclomiphene; not stated otherwise. |
| `price_kind` | What the price buys: the medicine, the medicine with care and labs, or a care plan alone with the medicine billed apart. |
| `membership_fee` | none when the clinic's page says no membership is charged beside the price; separate when one is; not stated otherwise. |
| `advertised_price` | The price as the clinic publishes it, e.g. "$149/mo" or "from $28/mo + membership". |
| `price_usd` | The advertised amount in US dollars (a month's price unless plan_months says otherwise). Empty when the clinic publishes no amount. |
| `plan_months` | Months the price commits to (1 = month to month), when stated. |
| `price_terms` | The clinic's own words the price was read from, quoted. |
| `checked_on` | The day (UTC) this price was last read on its source page (YYYY-MM-DD). |
| `review_status` | current within 21 days of checked_on; overdue after that, when the quote is kept only as a dated reference. |
| `source_url` | The clinic's page the price was read on. |
| `referral_program` | yes when TRTcompare.co may earn a referral fee from this clinic. It never changes a price order or a cheapest list. |
| `trtcompare_page` | The clinic's page on TRTcompare.co, with every price in context. |
| `notes` | Conditions, fees and caveats from the clinic's terms. |

## Columns: trt-first-year-cost.csv

| Column | Meaning |
|---|---|
| `rank` | Order by first_year_cost_usd, cheapest first. |
| `clinic` | The online clinic. |
| `first_year_cost_usd` | Twelve months of the clinic's cheapest month-to-month testosterone (its shortest plan where it has no monthly one), plus the membership it requires, the first labs, the later panels its page prices within the year and its fixed fees. |
| `starting_price` | yes when the testosterone price is a starting price ("from"). |
| `testosterone_product` | The testosterone product the year is built on. |
| `advertised_price` | Its price as the clinic publishes it. |
| `plan` | The plan the year is built on, in words. |
| `medicine_usd` | The year's medicine. |
| `membership_usd` | The year's required membership, 0 where none. |
| `labs_usd` | The year's priced lab work. |
| `fees_usd` | The year's fixed fees (consults, yearly visits). |
| `made_up_of` | Each part of the total in words, separated by semicolons. |
| `not_priced` | What a first year needs that the clinic's page does not price, separated by semicolons. |
| `prepaid_first_year_usd` | The same year on the clinic's lowest-priced longer prepaid plan, where it sells one. |
| `prepaid_plan` | That plan in words. |
| `states_served` | The states the clinic's own pages say it serves. |
| `trustpilot_score` | Trustpilot's TrustScore out of 5, where the clinic has a rated profile. |
| `trustpilot_reviews` | Trustpilot's review count. |
| `bbb_rating` | The Better Business Bureau's letter grade, or NR when BBB does not rate it. |
| `fda_warning_letters` | FDA warning letters found addressed to the clinic. |
| `clean_public_record` | yes for 4.0+ Trustpilot stars over 100+ reviews, a BBB grade above D and no FDA warning letter. |
| `checked_on` | The day (UTC) the testosterone price was last read. |
| `source_url` | The clinic's page the testosterone price was read on. |
| `referral_program` | yes when TRTcompare.co may earn a referral fee from this clinic. It never changes the rank. |
| `trtcompare_page` | The clinic's page on TRTcompare.co. |

## How the prices are read

Each price comes from the clinic's own price, plan or FAQ page, copied with the page's address and the day it was read. Nothing is taken from review sites, coupon sites or sales calls. A price older than 21 days stays in the file as a dated reference (`review_status` = overdue). Trustpilot, BBB and FDA records are read from those bodies' own pages. Clinics that may pay TRTcompare.co a referral fee are marked in `referral_program`; that never changes an order.

## Limits

These are advertised prices, not quotes: the dose, the state and the plan a clinician prescribes change them. Compounded medicines are not FDA-approved, and enclomiphene has no FDA approval in any form. Testosterone is a Schedule III controlled substance that needs a prescription. Nothing here is medical advice.

## License and citation

CC BY 4.0: free to share and adapt, commercial use included, with credit to TRTcompare.co and a link to https://trtcompare.co/data.

> TRTcompare.co. US online TRT clinic prices (read by 2026-11-25). https://trtcompare.co/data. Licensed under CC BY 4.0.
