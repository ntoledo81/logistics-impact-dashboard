# Logistics Impact Dashboard

Interactive timeline-style dashboard analyzing the impact of logistics (delivery timing) on school engagement — Q1 2026.

> ✅ **Status: Ready.** All sections, charts, and interactivity are complete.

## Usage

Open **`index.html`** directly in any modern browser — no server, build step, or internet connection required. Chart.js is bundled inline; all data is embedded as JavaScript literals.

> **GitHub Pages:** Enable GitHub Pages on the `main` branch (root folder) in repository Settings → Pages to get a public URL like `https://ntoledo81.github.io/logistics-impact-dashboard/`.

## Sections

| # | Section | Description |
|---|---------|-------------|
| 1 | **Overview & Key Metrics** | Animated KPI cards: 809 schools, 449 delivered, 87.3% active rate |
| 2 | **Monthly Cohort Timeline** | Bar + line combo chart per delivery month (Nov 2025 – Mar 2026) with Students / Classes toggle |
| 3 | **Delivery Timing vs Engagement** | Grouped bars for % Active and Avg Completion across 8 timing buckets |
| 4 | **Weekly Onboarding Granularity** | Week-by-week delivery cohorts (W47/2025 – W11/2026) with Avg Students / Avg Classes toggle |
| 5 | **Delivered vs Not-Delivered** | Side-by-side comparison of delivered, pending, and no-order school groups |
| 6 | **Correlation Insights** | Six Pearson correlation cards linking delivery delay and completion rate to engagement metrics |

## Interactive Features

- **Turmas / Alunos toggle** on Monthly, Weekly, and Comparison charts
- **Animated KPI counters** triggered on scroll via `IntersectionObserver`
- **Index-mode tooltips** on all charts with extended data rows
- **Sticky top nav** with active-section highlighting on scroll
- **Fade-in animations** as each section enters the viewport

## Data Source
- **Entregas**: 519 schools, 470 with at least 1 delivery
- **Visão Analítica**: 809 schools
- Data range: November 2025 – March 2026

## Brand
Built with Edify brand specifications (Ubuntu font, Edify color palette: `#4219B5`, `#FF2726`, `#FFC20E`, `#00AA9E`, `#4CD1F6`).

## Screenshot

![Dashboard preview](https://github.com/user-attachments/assets/849717ab-7fda-47e8-912f-8e296e0645dd)