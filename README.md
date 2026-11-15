# Solana Funding Ladder

An open, source-checked map of how an early Solana team can get funded: bounties, grants, hackathons, accelerators,
venture rounds and on-chain raises. Seven rungs, 12 programmes, each with amount, terms, deadline and the official link.

- Live page: https://funding-ladder-v3.vercel.app (English) · https://funding-ladder-v3.vercel.app/uk.html (Ukrainian)
- Data: [`data.json`](data.json) · [`data.csv`](data.csv)
- Last checked against primary sources: **2026-11-15**

## Why

Funding guides go stale within weeks: deadlines move, programmes pause, amounts change. Every entry here is checked
against the programme's own page and carries a "checked on" date. Where a source was unclear, the entry says so
instead of guessing (for example, a grant listing that shows "Applications Paused").

## Use the data

`data.csv` columns: `rung, rung_title, kind, program, amount, terms, deadline, url, checked_on`.
`kind` is `non-dilutive`, `priced` (equity or token rights) or `governed` (market-governed treasury).
The pages are static HTML with no scripts and no external assets; open `index.html` locally or host it anywhere.

## Corrections

Found something out of date? Open an issue with the programme name and a link to the primary source.
Planned: a monthly re-check with a changelog.

## Licence

Code and pages: MIT. Data: CC BY 4.0. Amounts and dates are a snapshot, not financial advice; check programme
pages for current terms before you apply. Built with an AI research agent; every fact is linked to its source.
