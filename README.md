# WalletSign Feedback & Discussions

WalletSign is a website that lets users connect a browser wallet, sign arbitrary text messages, and verify signatures across multiple chains (BTC, EVM/Ethereum + common L2s, Solana, Tron, Sui). Use this repo to file issues and requests.

## What you can submit
- Bug reports: incorrect behavior in connect/sign/verify, crashes, bad results
- Feature requests: product or UX changes in the sign/verify flows, chain switcher, or wallet connectors
- New blockchain support: request another chain to connect/sign/verify
- Translation errors: wrong, missing, or unclear copy
- New language requests: add another UI language

## How WalletSign works
- Multi-chain signing and verification across BTC, EVM/Ethereum (plus common L2s), Solana, Tron, and Sui.
- Wallet connection via familiar browser wallets (e.g., MetaMask, OKX, TokenPocket, Phantom, TronLink, Suiet) with clear connect/disconnect status.
- Chain switcher with readable names/icons and compatibility notes for EVM-aligned networks.
- Signing: enter any text message, sign with the connected wallet, and copy/share the signature or jump straight to verify.
- Verification: input address, message, and signature to get immediate success/failure feedback, plus copy helpers for sharing data.
- Localization: supports multiple languages with locale-aware navigation and metadata.

## How to submit
1) Click “New issue” and choose the matching template.  
2) Fill in required fields; never include seed phrases, private keys, or secrets.  
3) Add chain/wallet details, screenshots, logs, or links so we can reproduce.  
4) Watch labels and comments for follow-ups; we may ask for more info or share status.

## Template snapshot
- 🐞 Bug report: steps, chain/wallet, expected vs actual, environment
- 💡 Feature request: what you want and why (one field)
- 🌐 New blockchain request: chain name, explorer (optional), why it’s needed; optional sample signature (address + message + digest)
- 🈶 Translation error: locale, current text, suggested text, issue, screenshot (optional)
- 🗣️ New language request: target language, language code, optional reference link

Want to help translate directly? Contribute at https://github.com/walletsign/translate.

## Pre-submit checklist
- Searched existing issues to avoid duplicates
- Clear reproduction steps (for bugs)
- Chain, wallet/provider, and environment details included
- No keys, seed phrases, private links, or personal data

## What to expect
We triage by impact and feasibility and will update the issue with questions or status. Thanks for helping improve WalletSign!
