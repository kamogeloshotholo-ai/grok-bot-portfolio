# 04 · Competition Entrant

## Problem
South African brands run many free competitions, but finding real ones and filling in forms takes hours. Many listings are scams, closed, or need a purchase.

## What the bot does
- Searches brand websites and verified brand social pages for free competitions open to South Africans.
- Skips anything closed, without proper terms, needing a purchase, or asking for sensitive personal data up front.
- Enters the ones that qualify and logs each entry.

## How it's built
- Browser automation to fill in entry forms, with each entry confirmed on screen.
- A Google Sheets tracker with Entries and Sources tabs.
- Routines: runs at about 08:00 and 19:00 SAST, plus a Sunday summary.
- Contact details come from an encrypted vault.

## Result
- 21 Nov 2026: found 23 real, free competitions and skipped 15.
- 23 Nov 2026: 7 entries confirmed on screen and logged.
- No wins yet.

## What's next
- Track the win rate per source and drop sources that never pay out.
