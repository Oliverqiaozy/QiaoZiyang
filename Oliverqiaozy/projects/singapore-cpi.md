# Singapore Fertility Explorer

[← Profile](../README.md)

## Research question

How do fertility trends in Singapore relate to family costs, income, women's labour-market participation and marriage patterns?

## Team project

The project brings multiple annual data series into a common exploratory interface. It combines total fertility rate, resident births and age-specific fertility measures with CPI components, household income, female labour-force participation, female employment and marriage indicators.

The default dashboard period is **2015–2025**. Longer time ranges are available where individual source series support them. Data preparation aligns calendar years, preserves missing observations and records indicator definitions and provenance.

## Interactive analysis

Six views support different analytical questions:

- **Overview:** fertility indicators and indexed trends across selected factors.
- **Factor explorer:** levels versus annual changes, calendar-year lags and Pearson or Spearman correlations.
- **CPI and costs:** relative price indices, raw CPI and inflation patterns.
- **Age profiles:** age-specific fertility alongside relevant employment counts.
- **Compare factors:** multiple factors evaluated on one common sample.
- **Data and methods:** definitions, source notes and downloadable data.

Users can change years, inspect matched observations, explore lags of up to three years and test the sensitivity of comparisons to pandemic-period exclusions. Charts and CSV exports update with the selected sample.

## Analytical value

The project makes it practical to examine competing explanations for fertility trends while checking how transformations and sample choices affect apparent relationships. A separate CPI notebook provides reproducible preparation and presentation charts for selected family-cost channels.

These annual comparisons describe associations. Shared trends, small samples and incomplete source metadata limit interpretation; the dashboard does not estimate causal effects or produce fertility forecasts.

## Deliverables and sources

Existing materials include a Streamlit app, data-preparation scripts and notebook, prepared CSVs, a source catalogue, a CPI notebook and presentation charts.

The CPI and fertility inputs include [SingStat M213801](https://tablebuilder.singstat.gov.sg/table/TS/M213801) and [SingStat M810091](https://tablebuilder.singstat.gov.sg/table/TS/M810091), as recorded in the project. Other integrated series have source-scope limitations documented in the dashboard materials.

**My contribution:** CPI and family-cost analysis, including relative-price preparation and fertility visualizations.

*Group coursework; the saved CPI notebook and dashboard integration record AI-assisted code preparation.*
