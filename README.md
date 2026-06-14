# Sikadesk

**Stablecoins at scale — OTC trading with platform-managed settlement.**

Sikadesk is building infrastructure for compliant stablecoin trading. Our platform digitizes onboarding, order management, matching, settlement, and operational oversight for OTC stablecoin flows.

> **Note:** Sikadesk’s application source code is maintained in **private repositories** for security, compliance, and commercial reasons. This repository is our public overview for grant reviewers, partners, auditors, and other stakeholders who need visibility into what we build and how to request deeper access.

---

## What we build

Sikadesk is an OTC stablecoin trading platform designed for institutions, with a separate retail surface for smaller self-serve activity where enabled.

| Area | Description |
|------|-------------|
| **Institutional trading** | Buy and sell stablecoins (e.g. USDT, USDC) via OTC orders, automatic matching, and platform-mediated settlement |
| **Onboarding & compliance** | Whitelisting, KYC/KYB verification, payment-account and wallet review, sanctions and fraud controls |
| **Settlement** | Fiat and crypto settlement through platform-controlled accounts and wallets — not direct counterparty settlement |
| **Operations** | Admin console for trade oversight, settlement management, onboarding review, chat, and configuration |
| **Retail (where enabled)** | Individual onboarding, identity verification, and buy/sell ramp flows |

### How it works (high level)

1. **Sign up & verify** — Institutions complete whitelist approval, identity verification, and payment-method setup.
2. **Place orders** — Users create buy or sell orders with token, network, fiat currency, amount, and rate.
3. **Match & settle** — Orders are matched automatically; settlement runs through Sikadesk’s platform-managed flow with full operational visibility.

### Platform principles

- **Compliance-first** — Built-in audit trails, review workflows, and exportable reporting.
- **Platform-mediated settlement** — Institutions do not settle directly with each other.
- **Operational transparency** — Matching, lock confirmation, and settlement are visible to authorized platform operators.
- **Security by design** — Multi-layered controls around wallets, settlement accounts, and access management.

---

## Technology overview

Sikadesk is developed as a modern TypeScript monorepo. At a high level:

| Layer | Technologies |
|-------|----------------|
| **Applications** | Next.js (web, admin, retail, marketing), static export deployment |
| **API** | NestJS, oRPC, OpenAPI |
| **Data** | PostgreSQL (Prisma), Redis (queues/caching) |
| **Integrations** | Identity verification (Sumsub), email, notifications, blockchain settlement providers |
| **Quality** | TypeScript, ESLint, Vitest, Playwright (E2E) |

We do not publish implementation details, infrastructure diagrams, or credentials in this repository.

---

## Public resources

| Resource | URL |
|----------|-----|
| Website | [https://sikadesk.com](https://sikadesk.com) |
| Platform (institutional) | [https://app.sikadesk.com](https://app.sikadesk.com) |
| Support portal | [https://support.sikadesk.com](https://support.sikadesk.com) |
| X (Twitter) | [https://x.com/sikadesk](https://x.com/sikadesk) |

---

## Source code access

Our production codebase is **private**. We routinely share materials with:

- Grant and funding reviewers  
- Prospective institutional partners  
- Compliance and security auditors  
- Academic or research collaborators (under NDA where required)

### Request access

Email **[support@sikadesk.com](mailto:support@sikadesk.com)** with:

| Field | Details |
|-------|---------|
| **Subject** | `GitHub / Code Review Access Request` |
| **Your name & affiliation** | Organization, program, or role |
| **Purpose** | e.g. grant review, partnership diligence, security audit |
| **Scope needed** | Architecture overview, demo environment, read-only repo access, technical walkthrough |
| **Timeline** | Review deadline or preferred dates |

 For time-sensitive grant deadlines, kindly include the date in your subject line.

Access may be provided as:

- A guided product demo or staging environment  
- Architecture and product documentation  
- Time-limited, read-only access to private repositories  
- A live technical Q&A session  

All access is subject to confidentiality terms where applicable.

---

## Security

If you discover a security vulnerability, please **do not** open a public GitHub issue.

Report it responsibly to **[support@sikadesk.com](mailto:support@sikadesk.com)** with the subject `Security Disclosure`.

---

## Open source

Sikadesk is a commercial fintech product. We use open-source dependencies extensively and may publish selected libraries or tools in the future. This repository does not imply that the full platform is open source.

---

## Legal

Information in this repository is provided for general orientation only. It does not constitute an offer, solicitation, or financial advice. Product capabilities, availability, and regulatory treatment may vary by jurisdiction and user type.

For terms and privacy information, see [sikadesk.com](https://sikadesk.com).

---

## Contact

| Channel | Address |
|---------|---------|
| **General & access requests** | [support@sikadesk.com](mailto:support@sikadesk.com) |
| **Website** | [https://sikadesk.com](https://sikadesk.com) |

---

<p align="center">
  <sub>© Sikadesk. All rights reserved.</sub>
</p>
