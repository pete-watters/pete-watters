# Pete Watters

**Senior Frontend Engineer** — Bitcoin, Web3, and high-stakes fintech.

Currently at [Trust Machines](https://trustmachines.co), building [Leather](https://leather.io) — the leading wallet for Bitcoin and Stacks apps. Open-source contributor to the [Leather mono-repo](https://github.com/leather-io/mono).

## What I'm working on

**Leather Wallet** — Bitcoin & Stacks wallet serving 8,400+ monthly active extension users

- Core team on the Hiro Wallet to Leather rebrand — architected the mono-repo, built the shared Panda UI component library, implemented BIP key validation
- Shipped the first **Leather mobile app** (React Native + Expo), growing to 1,850+ MAU in three months
- Built the DeFi Portfolio UI for on-chain position tracking across Granite and Zest

## Notable open-source contributions

- **Monorepo architecture** — [leather-wallet/mono#8](https://github.com/leather-wallet/mono/pull/8)
  - Consolidated extension, mobile app, and shared packages into a single repo with automated npm publishing
- **Mnemonic validation on wallet sign-in** — [leather-wallet/extension#4243](https://github.com/leather-wallet/extension/pull/4243)
  - Replaced a single textarea with word-by-word input and real-time BIP-39 validation using `@scure/bip39`
- **Full-page container system rebuild** — [leather-wallet/extension#4655](https://github.com/leather-wallet/extension/pull/4655)
  - Replaced the entire drawer and container system with Radix Dialog, unified headers, and standardised viewport widths
- **Modal routing refactor** — [leather-wallet/extension#4325](https://github.com/leather-wallet/extension/pull/4325)
  - Fixed overlay modal routing to handle background content, direct navigation, and nested route state
- **Spam token filtering** — [leather-wallet/extension#4113](https://github.com/leather-wallet/extension/pull/4113)
  - Detection and filtering of scam token names containing URLs and phishing text in the wallet's asset list
- **Collectibles refactor** — [leather-io/mono#1903](https://github.com/leather-io/mono/pull/1903)
  - Introduced shared `CollectibleView` type, moved UI components into apps, added token detail screens and Send Inscription flow

## Tech

**Frontend:** React, TypeScript, Next.js, React Native, Expo, Redux, Ember.js
**Tooling:** Panda CSS, Radix UI, Playwright, Cypress, Vitest, CI/CD
**Server-side:** Node.js, Express, Python, Ruby

## Previously

- **[Qredo](https://qredo.com)** — Web3 wallet integration and institutional trading UI
- **[Kraken / Cryptowatch](https://kraken.com)** — Multi-exchange trading terminal, sole FE on Coderunner trading automation
- **[Xapo](https://xapo.com)** — Full-stack architecture blueprint adopted company-wide, CI/CD from scratch
- **[Bank of America Merrill Lynch](https://bankofamerica.com)** — Introduced automated acceptance testing to frontend workflow
- **[Fidelity Investments](https://fidelity.com)** — Technical lead for offshore development

## Links

- [petewatters.ie](https://petewatters.ie) — Portfolio & blog
- [petewatters.ie/cv](https://petewatters.ie/cv) — CV
- [LinkedIn](https://www.linkedin.com/in/pete-watters/)
- [StackOverflow](https://stackoverflow.com/users/1365580/peadar)
