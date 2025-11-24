# trade-token-table
## Overview

trade-token-table is a modern, interactive token discovery dashboard for the  Trade ecosystem. It displays a live updating table of crypto tokens/pairs with advanced filtering, sorting, pagination, and analytics capabilities. The UI leverages Tailwind CSS and mock live data generation in pure HTML + JS.

## Features

- **Live Token Table:** View real-time token data with simulated price, market cap, volume, and status.
- **Interactive Filters:** Tabs for All Tokens, New Pairs, Final Stretch, and Migrated tokens.
- **Search & Sort:** Search tokens by name or symbol. Sort by rank, name, price, 24h%, volume, or market cap.
- **Analytics Cards:** Top-level stats (total volume 24h, active pairs, new listings, avg market cap).
- **Responsive Design:** Works across devices with custom scrollbar and mobile-friendly table view.
- **Visuals:** 7-day sparkline charts, animated price changes, pulse indicator for live data.
- **Token Details Modal:** Click any row for detailed modal—price, charts, holders, contract address, creation date.
- **Pagination:** Easily browse large lists of up to 150 tokens with next/previous controls.
- **Skeleton & Loading Animations:** Smooth UX during data refresh.

## Technologies Used

- HTML5
- Tailwind CSS (via CDN)
- Google Fonts (Inter)
- Vanilla JavaScript (mock data + interactivity)

## Getting Started

No installation or build process required for demo. To run:

1. Clone/download this repository.
2. Open `index (2).html` in your web browser.

All features and sample data are immediately available.

## File Structure

- `index (2).html` : Main dashboard UI, styling, and logic.
- `README.md` : This documentation file.

## Customization

You can adjust token generation logic to pull from a real backend or crypto API by swapping out the mock data generator in JS.
