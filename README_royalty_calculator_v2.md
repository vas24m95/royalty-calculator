# Royalty Calculator v2

## Project Overview

A Python-based royalty calculator that uses artist streaming data to estimate gross revenue and artist royalty payouts.

The project demonstrates how Python and Pandas can be used to clean, analyse and transform music industry data into a structured royalty reporting output.

## Objectives

- Load and analyse artist streaming data using Pandas.
- Identify the top 10 artists by total streams.
- Convert streaming figures from millions into individual streams.
- Estimate gross revenue using an assumed revenue-per-stream rate.
- Calculate artist payouts using different royalty percentages.
- Export the results into a CSV report.

## Technologies Used

- Python
- Pandas
- Google Colab
- GitHub

## Calculation Methodology

The project uses the following illustrative assumptions:

- Revenue per stream: £0.003
- Example artist royalty rate: 20%
- Alternative royalty scenarios: 10%, 20% and 30%

**Calculations:**

Gross Revenue = Total Streams × Assumed Revenue per Stream

Artist Payout = Gross Revenue × Artist Royalty Rate

These are educational estimates, not official Spotify royalty rates or actual contractual payments. Actual royalty distributions depend on rights ownership, agreements, territories and other factors.

## Key Features

1. Data loading and inspection.
2. Data cleaning and column preparation.
3. Sorting and ranking artists by streaming volume.
4. Revenue and royalty calculations.
5. Royalty percentage scenario analysis.
6. CSV report generation.

## Output

The project produces a structured report containing:

- Artist name
- Streaming volume
- Estimated gross revenue
- Estimated artist payout
- Payout scenarios at 10%, 20% and 30%

## Future Development

Planned improvements include:

- Uploading and processing royalty statements.
- Validating missing or inconsistent royalty data.
- Identifying duplicate records.
- Comparing royalty rates against reference contract data.
- Generating automated exception reports.
- Exploring AI-assisted analysis of royalty discrepancies.

## Disclaimer

This project is for educational and portfolio purposes. Revenue and payout figures are estimates based on assumed rates and should not be interpreted as actual Spotify payments.
