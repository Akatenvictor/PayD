# PayD: Stellar-Based Cross-Border Payroll Platform!

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Stellar](https://img.shields.io/badge/Powered%20by-Stellar-7B68EE)](https://www.stellar.org/)

## 🧩 Project Summary

PayD is a revolutionary payroll system that enables organizations to pay employees, contractors, and partners across different countries using blockchain-based digital assets. By leveraging Stellar's fast, low-cost network, PayD replaces traditional banking rails with near-instant, transparent, and cost-effective payments.

**Key Benefits:**

- ⚡ Near-instant salary payments (seconds vs. days)
- 🔍 Transparent transaction tracking on-chain
- 💰 Lower cross-border fees (fraction of traditional banking)
- 📊 Stable-value payouts with predictable conversion rates

## 🚨 Problem This Solves

Traditional international payroll faces significant challenges:

| Problem                        | Impact                                  |
| ------------------------------ | --------------------------------------- |
| International bank delays      | Payments take 2–5 business days         |
| High transfer fees             | SWIFT + intermediary fees (often 5-15%) |
| Currency conversion issues     | Unpredictable FX rates and hidden fees  |
| Lack of proof                  | Difficult to verify payment delivery    |
| Contractor/freelancer payments | Many unbanked or prefer digital methods |

## 💡 Core Concept

Instead of routing through expensive banking infrastructure:

All transactions occur on-chain with full transparency and auditability.

## 🏗 System Architecture

┌─────────────────┐ ┌──────────────┐ ┌─────────────────┐ │ Organization │ │ Backend │ │ Stellar │ │ Dashboard │────│ (API) │────│ Network │ │ (Web App) │ │ │ │ │ └─────────────────┘ └──────────────┘ └─────────────────┘ │ │ │ ▼ ▼ ▼ ┌─────────────────┐ ┌──────────────┐ ┌─────────────────┐ │ Employee │ │ Payroll │ │ Employee │ │ Onboarding │ │ Engine │ │ Wallets │ └─────────────────┘ └──────────────┘ └─────────────────┘ │ ▼ ┌─────────────────┐ │ Local Anchors │ │ (Cash-out) │ └─────────────────┘

## 🔑 Main Actors

| Actor                   | Role                                                          |
| ----------------------- | ------------------------------------------------------------- |
| **Employer**            | Funds payroll, schedules payments, manages employees          |
| **Employee/Contractor** | Receives salary in digital assets, converts to local currency |
| **Backend System**      | Handles payroll logic, transaction processing                 |
| **Stellar Network**     | Processes fast, low-cost transactions                         |
| **Anchor Services**     | Converts digital assets to local bank/mobile money            |

## 💰 Asset Design on Stellar

PayD utilizes Stellar's asset issuance capabilities to create organization-specific stable assets:

### Example Asset: ORGUSD

- **Issuer Account**: Controlled by the organiza

---

## 📚 Contribution Reward (Bounty) Program

We value community contributions! High‑priority issues may carry a bounty to recognize and reward contributors.

### Eligible Contributions
- **Bug fixes** for critical bugs affecting core payroll flows.
- **Feature implementations** that align with the roadmap and have been approved as high priority.
- **Documentation improvements** that significantly enhance onboarding or user guidance for bounty‑eligible issues.

### Claim Process
1. **Work on an issue** labeled with the `bounty` tag.
2. **Submit a pull request** that resolves the issue and passes all CI checks.
3. **Add a comment** on the issue with the PR link, stating you are claiming the bounty.
4. **Project maintainers** will review the contribution. If approved, the reward will be transferred via the project's Stellar wallet.

### Reward Details
- Rewards are paid in **XLM** (Stellar Lumens) or a stable asset of the project's choosing.
- Amounts vary per issue and are defined in the issue description.
- Payments are processed within 7 business days after PR merge.

For more details, see the [CONTRIBUTION_REWARD.md](CONTRIBUTION_REWARD.md) file.
