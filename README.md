# Rental Deal Analyzer

A standalone browser-based analyzer for long-term rental properties. The interface and calculations are contained in `index.html`; it has no build step or external dependencies.

## Open the app

Open `index.html` directly in a browser. The calculator runs locally in the browser and does not send property inputs to a server.

## Current features

- Property purchase, financing, closing-cost, and improvement inputs
- Unit-by-unit monthly rent and other income
- Vacancy, management, maintenance, capital reserve, property tax, insurance, HOA, and utility assumptions
- Estimated cap rate, cash-on-cash return, DSCR, gross rent multiplier, break-even rent, upfront cash invested, and cash flow
- An illustrative example that can be restored with **Load example**

## Calculation notes

- Property tax is entered annually. Insurance, HOA, and owner-paid utilities are entered monthly.
- Vacancy, management, maintenance, and capital reserve percentages are applied to scheduled rent by unit; other unit income is not reduced by vacancy.
- Net operating income excludes capital reserve and debt service. The cash-flow estimate subtracts both capital reserve and principal-and-interest payments.
- Cash invested includes the down payment, closing costs, and entered initial improvements.
- Inputs are not saved between browser sessions yet. Use **Load example** to restore the sample values.

The estimates are for planning and do not include every possible cost, tax treatment, financing fee, or investment risk.
