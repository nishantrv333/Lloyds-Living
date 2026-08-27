# Lloyds Living portfolio project

A single page walkthrough of the 980 home portfolio Lloyds Living signed with Barratt Redrow in July 2026. I built it to show how I would take a real property deal apart and present it, from the raw stock list through to the yield and the risks.

**Live version:** https://nishantrv333.github.io/Lloyds-Living/

Prepared by Nishant Vatnal, Analyst.

---

## Why I built it

I wanted a piece of work that showed the whole job rather than one slice of it. Anyone can produce a table of units. The harder part is knowing what the numbers mean, where the risk actually sits, and how to explain both to someone who has fifteen minutes and a decision to make.

So the page runs in four steps, in the order I would talk someone through the deal.

**Portfolio dashboard.** What we bought and when it reaches us. Filter by region or size of house, click a bar on the chart to isolate a delivery year, click any site to open the rent, the capital and the phasing behind it.

**Market note.** Where we sit against Grainger, Legal and General and M&G, and what the second quarter of 2026 did to the market. Written the way I would write an internal note, not a brochure.

**Committee pack.** One page, the whole deal, and the three things I need a decision on. It reads live off the model, so if the assumptions change it changes too.

**Financial model.** Five sheets. Asset register, rent assumptions, budget and yield, occupancy and arrears, and a sensitivity grid. Void rate and rent growth sit on sliders, and every figure recalculates as you move them. There is a formulas button that shows the working behind each sheet.

---

## What is real and what is mine

I have been careful to keep these apart, because the difference matters.

**Taken from public Lloyds Living announcements and company reporting**

- Over 8,850 homes owned today, with a target of 50,000 by 2030
- The Barratt Redrow deal, 980 homes across 14 developments
- The six counties: Cambridgeshire, Northamptonshire, Nottinghamshire, Merseyside, East Anglia and the West Midlands
- 255 of the homes are in East Anglia
- First lettings from autumn 2026 at Hampton Beach in Peterborough and Burleyfields in Stafford
- Every home EPC B or better, many with air source heat pumps, all managed in house
- Peer figures for Grainger, Legal and General and M&G, and the Savills and Knight Frank market numbers

**Modelled by me and labelled as such throughout**

- The twelve site locations other than Hampton Beach and Burleyfields. These are my own split of the announced counties so the pipeline can be planned site by site. Every row on the table tells you which is which.
- Unit mix, rents, cost per home, running costs, void and arrears assumptions
- The twelve month occupancy record, built on the 598 home tranche bought in 2025 as a comparator

No internal or confidential Lloyds Banking Group information is used anywhere. This is a personal project and not a Lloyds Banking Group publication.

---

## The headline numbers

| | |
|---|---|
| Homes | 980 across 14 sites |
| Delivery | Autumn 2026 to end 2029 |
| Three and four bed share | 64 percent |
| Rent a year when full | £13.1m |
| Total capital | £238.2m |
| Net stabilised yield | 4.59 percent at a 4.5 percent void rate |
| Sensitivity range | 4.42 to 4.96 percent |

Every one of these is calculated in the page rather than typed in, so they cannot drift apart from each other.

---

## Running it

There is nothing to install and nothing to build. It is one HTML file with the CSS and JavaScript inside it, no libraries, no fonts loaded from anywhere else, no data fetched at runtime.

**Locally.** Download `index.html` and open it in a browser.

**On GitHub Pages.**

1. Create a repository and upload `index.html` and `README.md` to the root.
2. Go to Settings, then Pages.
3. Under Build and deployment, set Source to "Deploy from a branch", branch `main` and folder `/ (root)`.
4. Save. The site appears at `https://YOUR-USERNAME.github.io/REPO-NAME/` within a minute or two.

The file has to be named `index.html` and sit at the root of the repository, otherwise Pages will not serve it as the landing page. Update the live link at the top of this README once it is up.

## What I would add next

- Cash flow by quarter rather than by year, so the mobilisation spend can be seen against the first rent received
- A debt layer, so the return can be shown geared as well as ungeared
- Actual letting data replacing the modelled lease up curve once Hampton Beach and Burleyfields are live
