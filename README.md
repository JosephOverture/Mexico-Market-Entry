Starbucks Northern Mexico Market-Entry Strategy

Question

How should a premium coffee chain stage a 30-store northern-Mexico expansion while controlling cannibalization and execution risk?

Answer in one paragraph

Monterrey and Tijuana rank first and second under the stated city-attractiveness framework. The proposed rollout opens 30 stores over three years across five metropolitan markets. Under the base assumptions, mature revenue is about MXN 19.6 million per store and mature annual cash contribution is about MXN 2.6 million. The five-year NPV before terminal value is negative, while the terminal-value-inclusive result is positive; therefore, the recommendation is a staged pilot with explicit performance gates rather than an unconditional expansion.

Files

Starbucks_Northern_Mexico_Market_Entry.xlsx — market inputs, city scorecard, rollout, unit economics, five-year P&L, sensitivity, dashboard, and sources.

Starbucks_Northern_Mexico_Analysis.ipynb — reproducible prioritization and economics.

Starbucks_Northern_Mexico_Deck.pptx / .pdf — consulting-style executive presentation.

Starbucks_Northern_Mexico_Report.docx / .pdf — written recommendation, risks, and sources.

data/northern_mexico_city_inputs.csv — notebook input.

charts/ — exported visualizations.

Method

The city score weights population (35%), state GDP share (20%), premium-income index (20%), saturation headroom (15%), and strategic fit (10%). Population and GDP inputs are evidence-based; the latter three indices are transparent analytical assumptions intended to demonstrate a decision framework. Unit economics use explicit assumptions for ticket, daily transactions, operating days, EBITDA margin, opening capex, maintenance capex, tax, cannibalization, ramp, discount rate, and terminal growth.

Main limitations

The model does not use site-level rent, footfall, store-count, delivery, or competitor-density data.

Premium-income, headroom, and strategic-fit indices are assumptions and require primary research.

The model treats the rollout as a simplified economic project and does not replicate Alsea’s contractual or franchise accounting.

Terminal value is a large share of modeled value, so the result is highly sensitive to long-run margin, growth, and discount-rate assumptions.

A real recommendation would begin with a small store cohort and update the model using observed performance.

Proposed stage gates

After the initial pilot, proceed only if stores meet pre-agreed thresholds for sales per store, store EBITDA margin, cannibalization, customer repeat behavior, and payback trajectory.

Reproduce the analysis

Open a terminal in this folder and run:

jupyter notebook Starbucks_Northern_Mexico_Analysis.ipynb

Run all cells from top to bottom. The notebook reads data/northern_mexico_city_inputs.csv and exports charts to charts/.
