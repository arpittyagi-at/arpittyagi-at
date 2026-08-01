# Profile Operations

This directory contains the automation layer for the `arpittyagi-at` GitHub profile repository.

## Workflows

| Workflow | Purpose | Output |
| --- | --- | --- |
| `snake.yml` | Generates light and dark contribution snake SVGs. | `output` branch |
| `metrics.yml` | Generates the profile metrics SVG used by the root README. | `github-metrics.svg` |

The root README uses `assets/contribution-snake.svg` as a reliable local fallback so the profile never renders a broken image before the `output` branch exists.

## Profile Direction

The profile is intentionally focused on Data Analytics, Python, SQL, Power BI, Pandas, Business Intelligence, AWS Cloud, Cloud Computing, and Data Engineering so recruiters see a consistent IT and analytics profile.

## Featured Repositories

Only these repositories are promoted in the public profile:

| Repository | Positioning |
| --- | --- |
| `bank-customer-churn-analysis` | Banking analytics, churn risk, retention insights |
| `ecommerce-marketplace-analytics` | Marketplace analytics, revenue, customer behavior |
| `arpit-tyagi-portfolio` | Personal portfolio and frontend presentation |
| `TaskManager-ArpitTyagi` | Productivity application and CRUD workflow |
| `Mini_E-Commerce_Website-ArpitTyagi` | Ecommerce frontend and user flow implementation |
