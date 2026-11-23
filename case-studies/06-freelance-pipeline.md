# 06 · Freelance pipeline (Job Scout → Contest Entry)

## Problem
Finding paid online work that is free to apply for, and that a bot can do most of, takes time. So does preparing a strong entry.

## What the bots do
- **Job Scout** scans freelance sites every week, ranks the best five opportunities and writes a one-page bot spec for the one the owner picks.
- **Contest Entry** prepares the entry pack. The owner reviews and submits every entry.

## How it's built
- Web search, with each listing checked live before it is ranked.
- A weekly routine every Monday at about 07:00 SAST.
- Live domain checks and trademark searches for naming work. These are research only, not legal advice.
- Google Flights for fare contests.
- Image generation for entry boards.
- The spec is handed to the bot factory (case study 05) to build the worker bot.

## Result (13 Nov 2026)
- Brand-naming contest: a pack of 12 names, each checked live for a free .com and .in, plus a ready-to-upload entry image and entry note.
- Flight-fare contest: beat 5 of the 6 target fares, for example $894 against a $1,100 target.
- No submission result or win is confirmed yet.

## What's next
- Log submission outcomes, so the pipeline can be judged on paid wins.
