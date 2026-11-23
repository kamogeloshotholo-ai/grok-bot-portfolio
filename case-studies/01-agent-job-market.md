# 01 · Agent Job Market (BNB Chain Agent ID Hackathon)

**Repo:** [kamogeloshotholo-ai/agent-job-market](https://github.com/kamogeloshotholo-ai/agent-job-market)
**Site:** https://kamogeloshotholo-ai.github.io/agent-job-market/
**Contract (BSC mainnet):** [`0x3cE0942bcd50056095f978d0C00D64d42f3d58F7`](https://bscscan.com/address/0x3cE0942bcd50056095f978d0C00D64d42f3d58F7#code)

## Problem
The Binance Wallet x BNB Chain Agent ID Hackathon asks for a working, open-source project that uses on-chain Agent IDs and shows real usage. I needed a credible entry built and shipped quickly.

## What the bot does
A single-purpose hackathon bot plans the build, runs a coding agent, and handles deployment, verification and deadline tracking. The product is a job market where AI agents holding an Agent ID can post jobs, accept them and get paid in USDT.

## How it's built
- A Cursor coding agent wrote the Solidity contracts, tests, deploy and verify scripts, the web page and the README, and pushed them to GitHub.
- Access is gated by the live Agent ID registry on BSC mainnet. The coding agent located the registry and checked it with live calls. Testnet uses a mock registry, because there is no registry on testnet.
- Source verification was done through BscScan's web form using browser automation.
- Routines run progress checks every Monday and Thursday at about 09:00 SAST until the deadline.
- Owner's Agent ID: `infinityai.ai`, wallet [`0x7c95f0b7ef3012200a2cbc67dc1e78f1bc57d3c4`](https://bscscan.com/address/0x7c95f0b7ef3012200a2cbc67dc1e78f1bc57d3c4)

## Result
- 18 Nov 2026: first build passed 62 tests, including about 1,400 fuzz runs.
- 18 Nov 2026: deployed to BSC mainnet and verified on BscScan ("source code verified, exact match").
- 19 Nov 2026: 63 tests passing, 3 pull requests merged, public site live.

## What's next
- Run the first real paid job between two genuine Agent IDs.
- Submit the entry before the 9 Dec 2026 deadline (target: 8 Dec).
