# Marin-Demo

Private demo repo for the **Marin PM incident walkthrough** (signup drop after deploy).

**Demo recording:** April 4, 2026 — treat **“last night’s update”** as the **April 3, 2026** evening deploy of `v1.2.4`.

## Scenario

- `v1.2.3` — stable signup funnel  
- `v1.2.4` — deploy that regressed checkout (Stripe Elements mount / form null ref), shipped **2026-04-03**  
- Correlate with PostHog (`signup_completed`, `checkout_form_error`), Sentry (`checkout-web@1.2.4`), and Stripe refunds tagged `demo_wasted_money`.

## Tags

- `v1.2.3` — last good release  
- `v1.2.4` — simulated bad release  
