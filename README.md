# Yahoo Fantasy Football Sit/Start Tool

Fantasy football sit/start analyzer with Yahoo league integration.

## Contents

- **ff-sitstart/**: Core sit/start analysis logic
- **netlify/functions/**: Serverless functions for Yahoo integration
  - `ff-weekly-roast.mjs`: AI-powered weekly league roast generator (25+ character voices)
  - `ff-run.mjs`: Main sit/start analysis runner
  - `ff-yahoo.mjs`: Yahoo Fantasy API integration
  - `ff-auth-*.mjs`: OAuth authentication flow
  - `ff-get-leagues.mjs`: Fetch user leagues
  - `_lib/`: Shared utilities (scoring, odds, cookies, blobs)

## Features

- Yahoo Fantasy league OAuth integration
- Sit/start recommendations based on:
  - Player projections
  - Matchup analysis
  - Odds integration
  - Scoring settings
- Weekly league roasts with 25+ AI character voices (Gordon Ramsay, Eric Cartman, Shakespeare, etc.)

## Extracted From

This code was extracted from the main RRMODEL repository on December 1, 2025.

Original repo: https://github.com/bgoldman22-code/RRMODEL
