# Energy Resilience Command Center

AI-powered hybrid renewable energy resilience framework that simulates continuous power delivery to critical infrastructure during grid outages — without diesel generators.

## Live Demo

[View Dashboard](https://jeetarora6769.github.io/energy-resilience-dashboard/)

## Problem Statement

Hospitals, water treatment plants, and emergency services require uninterrupted electricity during large-scale grid failures. This solution designs a hybrid renewable backup system capable of powering critical infrastructure for a minimum of 7 days without conventional diesel generation.

## Energy Sources

| Source | Role | Type |
|--------|------|------|
| Solar | Primary daytime generation | Variable |
| Hydrogen (Fuel Cells) | Long-duration backup storage | Dispatchable |
| Biomass | On-demand baseload power | Dispatchable |
| Hydroelectric | Steady continuous generation | Baseload |

## Features

- **7-Day Outage Simulation** — Hour-by-hour energy generation and consumption modeling across 168 hours
- **AI Load Prioritization** — Automatically sheds non-critical loads while protecting life support systems
- **4-Source Energy Mix** — Solar, hydrogen, biomass, and hydroelectric working together
- **Interactive Controls** — Adjust capacity of each source and see real-time impact
- **Weather Scenarios** — Test system resilience under Standard, Severe Storm, and Optimal conditions
- **Hydrogen Storage Tracking** — Monitor tank depletion and recharge cycles
- **Economic Analysis** — Cost comparison of hybrid renewable vs diesel backup with payback period

## Critical Facilities Protected

| Facility | Demand | Priority |
|----------|--------|----------|
| ICU & Life Support | 500 kW | P1 (Never shed) |
| Emergency Comms | 100 kW | P1 (Never shed) |
| Water Treatment | 400 kW | P2 |
| Hospital General | 300 kW | P3 |
| Emergency Response | 200 kW | P4 |
| Hospital Admin | 200 kW | P5 |

## How It Works

1. Solar and hydro provide base generation
2. When demand exceeds base generation, biomass ramps up
3. If still insufficient, hydrogen fuel cells activate using stored hydrogen
4. Excess solar energy produces hydrogen via electrolysis for later use
5. If all sources are exhausted, AI sheds lowest-priority loads first while protecting life-critical systems

## Tech Stack

- HTML5 / CSS3 / JavaScript
- Chart.js for data visualization
- Custom simulation engine with seeded randomness

## Screenshots

### Dashboard Overview
The main dashboard shows real-time metrics, weather conditions, and a stacked area chart of energy generation vs demand across 7 days.

### Load Priority Panel
Displays which critical facilities are powered or shed at any given hour, with priority-based color coding.

### Economic Analysis
Compares annualized costs of the hybrid renewable system vs traditional diesel backup, showing payback period and 20-year savings.

## Team

- **Jeet Arora** — UI/UX & Frontend — [GitHub](https://github.com/JEETARORA6769)
- **Anushree Khandelwal** — Full Stack — [GitHub](https://github.com/anushreeekh)
- **Yash Kumar Bassi** — Backend — [GitHub](https://github.com/YashKumarBassi)

