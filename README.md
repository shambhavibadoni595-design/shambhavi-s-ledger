# The Shared Ledger: A Web3 Primer

This is my submission for the Web3 Landing Page challenge (Track A). It's a single page site that explains the basics of Web3 to someone who has never heard of it before, using an old ledger/manuscript theme instead of the usual neon crypto look everyone goes for.

## What it is

I wanted to avoid the typical "dark background, glowing purple gradients, floating coins" Web3 template that everyone builds, so I went with an old paper ledger aesthetic instead. The idea is that a blockchain is basically just a shared ledger that a group of people keep together instead of trusting one person to keep it, so I leaned into that metaphor for the whole design. Warm paper tones, serif fonts (Playfair Display for headings, EB Garamond for body text), and little details like a wax stamp and a signature line at the bottom.

It's fully responsive and also respects the user's light/dark mode preference and reduced motion settings.

## Web3 concepts covered

The page walks through these ideas, each in plain language rather than technical jargon:

- What a blockchain actually is (a shared, append only record instead of a single database owned by one company)
- Decentralization, meaning who actually keeps the copy of the ledger and why that matters
- Cryptocurrency explained as entries in the ledger rather than physical coins
- Smart contracts, described as rules that execute themselves once conditions are met
- NFTs, framed as unique entries that exist inside an otherwise fungible system
- DAOs, described as an organization's bylaws written directly into code

Each section tries to explain the concept from first principles instead of assuming the reader already knows what a "node" or "consensus" means.

## Tech used

Just HTML and CSS, no frameworks or build tools. Everything is in one file so there's nothing to install to preview it, you can literally just open it in a browser.

- Google Fonts (Playfair Display and EB Garamond)
- CSS variables for theming, including automatic light/dark mode via prefers-color-scheme
- CSS animations for the scroll based reveals
- prefers-reduced-motion is respected for accessibility

## Running it locally

There's nothing to build. Clone the repo and open the HTML file in your browser, or use a simple local server if you want, like:

```
python3 -m http.server 8000
```

then visit localhost:8000 in your browser.

## Live demo

[link to be added after deployment]

## Notes

Wallet connection (the optional bonus) is not implemented in this version, I focused on getting the content and design right first.
