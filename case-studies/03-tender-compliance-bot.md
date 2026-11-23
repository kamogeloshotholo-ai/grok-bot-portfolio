# 03 · Tender compliance bot

## Problem
South African public tenders reject suppliers whose records fail compliance checks. A small company's supplier profile showed it as tax non-compliant, which would disqualify it from most tenders, and nobody knew why.

## What the bot does
- Signs in to the supplier database, the tax portal and the company registry, and reads the records.
- Finds the root cause of each compliance failure and lists the fix.
- Tracks the fixes until the status clears.
- Also built to find tenders and prepare bid packs.

## How it's built
- Browser automation with logins stored in an encrypted vault. The owner enters one-time PINs and captchas.
- Gmail search for official notices.
- Screenshots kept as evidence.
- Read-only by default. It files or pays nothing without the owner's approval.

## Result (11–16 Nov 2026)
- Found why the company showed as tax non-compliant: the company's tax number was not linked to the owner's tax profile, and no authorised representative was registered. There was no tax debt.
- Found why a registry payment had not shown after 10 days: the bank transfer went to an account number with a digit missing. The registry statement confirmed the money never arrived.
- Gave step-by-step fixes for both.
- Exported a shareable template of itself with all company data removed.
- No tender has been found or submitted yet.

## What's next
- Confirm the compliance status clears once the fixes are done.
- Start the tender search and first bid pack.
