# my-diet-plan

A 30-day diet and lifestyle plan, built as a single static page.

**Live:** https://codewithrobinsh.github.io/my-diet-plan/

**Day 1 = Monday 10 August 2026 · Day 30 = Tuesday 8 September 2026**

## What it covers

- **Goals** — triglycerides 448 → under 150, HDL 24 → above 40, homocysteine 29.82 → under 16.2, B12 191 → above 211, weight 56 → 58 kg
- **Prescribed medication** — Homin (folic acid 5 mg + methylcobalamin 1500 mcg + pyridoxine 20 mg), one month
- **Daily plan** — six meals a day, tap any of the 30 days
- **Shopping** — one monthly list for non-perishables, five weekly lists for fresh items
- **Water** — 3.2 litres, timed, all between meals
- **Walking** — 1 km after lunch on office days, 500 m on work-from-home days, 2 km at weekends
- **Prep, supplements and tracking**

## Structure

```
index.html    markup and the plan data
index.css     all styles
```

No build step, no dependencies. Open `index.html` in a browser.

Fonts load from Google Fonts; everything else works offline.

## Publishing with GitHub Pages

Settings → Pages → Source: `main`, folder `/root`.

Note that GitHub Pages requires a public repository on free accounts, and this page
contains personal health data — name, age, weight and blood results. Keep the repo
private and open `index.html` locally if you would rather that stayed off the open web.

---

Not medical advice. Reviewed against a general physician's prescription dated 2 August 2026;
any change to medication, dosing or supplements is a decision for a doctor.
