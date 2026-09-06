# IMARA Finance

Landing page for **IMARA Finance** - a local Kigali lender offering salary, business, school fees, emergency and equipment loans in small installments.

## Overview

A premium, single-page marketing site built with plain HTML/CSS/JS (no framework). Navy blue primary with gold accent, matching the brand posters.

## Features

- Sticky top nav with white text over the hero, turning to a light bar on scroll
- Hero with a ticket-style CHIC Building photo card and floating stat chips
- Animated loan marquee
- Loans section (Salary, Business, School Fees, Emergency, Equipment)
- How-it-works (3 steps) + repayment sample card
- Visit section with an all-loans info panel and contact details
- FAQ accordion
- Final CTA band
- Contact/eligibility modal with a FormSubmit-driven form

## Contact form

The eligibility form posts via **FormSubmit** (no backend needed):

- **Test endpoint:** `https://formsubmit.co/ajax/info@imarafinance.com`
- **Live endpoint:** `https://formsubmit.co/ajax/info@imarafinance.com`

The endpoint is a single line in `index.html` - switch it for launch, then click the activation link that FormSubmit emails to the live inbox on first submit.

> FormSubmit only works when the page is served over HTTP (not opened as a `file://` HTML file). Use `python -m http.server` in this folder.

## Run locally

```
python -m http.server 8080
```

Then open http://localhost:8080/

## Assets

- `references/chic building.jpg` - real CHIC Building photo used in the hero ticket
- `favicon.svg` - brand mark (navy + gold)
