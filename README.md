# Marin-Demo

Private demo repo for the **Marin PM incident walkthrough** (signup drop after deploy).

## Scenario

- `v1.2.3` — stable signup funnel  
- `v1.2.4` — deploy that regressed checkout (Stripe Elements mount / form null ref)  
- Correlate with PostHog (`signup_completed`, `checkout_form_error`), Sentry (`checkout-web@1.2.4`), and Stripe refunds tagged `demo_wasted_money`.

## Tags

- `v1.2.3` — last good release  
- `v1.2.4` — simulated bad release  

