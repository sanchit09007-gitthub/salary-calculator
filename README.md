# Salary Calculator

A simple, single-page payroll calculator that turns a Basic Salary into Gross and Net salary. Built with plain HTML, CSS and JavaScript — no frameworks, no build step.

## Features

- Enter Basic Salary and instantly see the full breakdown
- Auto-filled, editable rates for HRA (40%), DA (10%), Employee PF (12%)
- Editable fixed amounts for Other Allowances (₹1,600) and Professional Tax (₹200)
- One-click **Reset** to default rates
- Indian number formatting (₹1,23,456)
- Responsive, mobile-friendly layout
- You can change HRA, DA, PF also
## How it's calculated

```
Gross = Basic + HRA + DA + Other Allowances
Net   = Gross − (Employee PF + Professional Tax)
```

HRA, DA and PF are percentages of Basic Salary.

## Run locally

Just open `index.html` in any browser.

## Live demo

Enable GitHub Pages (Settings → Pages → Deploy from branch → `main` / root) and your site will be at:

https://sanchit09007-gitthub.github.io/salary-calculator/

## Disclaimer

The default rates are illustrative. Actual salary structures, PF limits and Professional Tax slabs vary by employer and state.

## Author

Developed by Sanchit Raj

## License

MIT
