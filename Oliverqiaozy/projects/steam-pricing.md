# Gaming Market & Player Analytics

[← Profile](../README.md)

## Business question

How do market structure, pricing and player engagement help explain performance in the gaming industry?

## Team project scope

The group project connects four perspectives:

1. **Global gaming landscape:** place gaming revenue and leading national markets in context.
2. **Steam market landscape:** examine the evolution of game releases and the genre mix.
3. **Pricing and performance:** compare prices with estimated ownership and positive review rates, including free versus paid titles.
4. **Player engagement:** explore genre-level playtime, the relationship between playtime and reviews, and potential hidden gems.

Together, these perspectives distinguish market size, audience reach, player satisfaction and engagement rather than treating them as a single success metric.

## Selected evidence: pricing and performance

The supplied historical Steam snapshot contains **27,075 game records**, approximately May 2019, with prices in GBP. The pricing analysis uses ownership-range midpoints as an estimated reach measure, compares free and paid titles per game, and checks both means and medians. Review-rate analysis applies a minimum review-count threshold.

| Snapshot price group | Games | Mean estimated owners | Median estimated owners |
| :--- | ---: | ---: | ---: |
| Free | 2,560 | 442,340 | 35,000 |
| Paid | 24,515 | 101,901 | 10,000 |

Free titles have approximately **4.34× the mean** and **3.5× the median** estimated ownership of paid titles in this snapshot. These are descriptive group differences, not the causal effect of making a particular game free.

The recorded full-sample price–ownership Spearman correlation is 0.048, indicating that price alone is a weak popularity signal in this dataset.

## Deliverables and interpretation

Available materials include a Tableau-ready dataset, summary tables, pricing slides, a presentation script and step-by-step Tableau instructions. The wider scope above follows the group project structure; the numerical findings shown here come from the available pricing analysis.

Estimated owners are not active-player counts or unit sales. The historical snapshot does not describe today's Steam market.

[Free versus paid summary CSV](../evidence/steam-free-paid-summary.csv)

**My contribution:** Part 3 — Pricing & Game Performance, including the pricing analysis, presentation materials and Tableau preparation.

*Group coursework.*
