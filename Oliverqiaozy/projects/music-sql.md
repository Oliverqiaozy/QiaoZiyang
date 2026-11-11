# Music Listening Analytics with SQL

[← Profile](../README.md)

## Business question

How do listening behavior and engagement differ by genre, subscription segment and discovery channel, and which source records need data-quality review?

## Analysis

The MySQL script contains eight assignment queries. The inspected sections cover genre activity, subscription and repeat-listening segments, listening minutes by discovery source, music-and-wellbeing summaries and platform-directory quality checks.

Techniques include common table expressions, joins, grouped aggregations, window functions and validation of text fields before numerical conversion. One query explicitly cleans listening-minute strings; another returns invalid platform records without modifying the source data.

## What this demonstrates

A path from an analytical question to auditable SQL: define the observation, use the correct denominator, handle inconsistent types and make data-quality exceptions visible.

## Evidence and scope

The existing executable SQL file is the main evidence. This profile package describes its inspected logic; it does not include a database export or claim that the queries were rerun here. Numerical business findings should be added only after reproducing the results against the intended database.

**My contribution:** individual SQL assignment.

*Individual coursework.*
