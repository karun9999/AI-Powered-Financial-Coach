# iOS UI concepts

`ios-ui-concepts.html` is a self-contained design document for the financial coach
app — open it in a browser, no build step or network access required. It covers
eight screen mockups, the information architecture, the shared chart component,
platform surfaces outside the app, and the colour/type/motion system. Light and
dark themes are both designed; the toggle sits bottom-right.

## What it argues

The six product areas — coach, subscription intelligence, family finance,
cash-flow prediction, health score, tax — are treated as one product rather than
six. They all describe the same object: a month with a shape. That gives the app
four tabs (Today, Flow, Commitments, Household) plus a pinned Ask affordance, and
one signature chart, the Runway, reused at four sizes throughout.

## Screens

| Screen | Covers |
| --- | --- |
| Today | Cash-flow prediction, low-balance warning, the daily nudge |
| Afford check | "Can I afford this?" as a before/after forecast |
| Bill explainer | "Why did my electricity bill increase?" as a waterfall |
| Savings plan | "How can I save ₹5,000?" as a ranked, executable checklist |
| Commitments | Subscriptions, EMIs, SIPs and mandates in one ranked list |
| Household | Shared budgets and goals, with per-category privacy controls |
| Health | Score composition and trend, not a dial |
| Tax | Old/new regime comparison, 80C headroom, document checklist |

## Context

Written for Indian households: rupee amounts use lakh digit grouping, recurring
payments ride UPI autopay mandates and card standing instructions, bank data
arrives through the RBI account aggregator framework, and the tax screen deals in
regimes, 80C and HRA.

The mockups are design artwork rendered in HTML and CSS. They are not a running
app and contain no application code. Sample figures are illustrative.

## Typography

Body text is Bitstream Charter, subset and embedded as woff2 so the page needs no
network access. Screen mockups use the iOS system font stack, since that is what
the app itself would render in.
