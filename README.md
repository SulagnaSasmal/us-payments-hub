# US Payments Hub — Operations & Compliance Reference

**A documentation portfolio project by Sulagna Sasmal — Senior Technical Writer | Documentation Architect**

---

## About This Project

This is a fully authored, enterprise-grade documentation site covering the five major US payment rails used by financial institutions. It demonstrates documentation architecture for regulated financial systems — written for an internal operations and compliance audience.

**Documentation style:** Enterprise HTML documentation (MadCap Flare-inspired structure, rendered as a static HTML site)
**Audience:** Bank operations staff, compliance teams, settlement analysts
**Coverage:** ACH, Fedwire, SWIFT, RTP, FedNow, Card Networks

---

## What's Documented

| Section | Description |
|---|---|
| [Overview & Rail Comparison](index.html) | Side-by-side comparison of all 6 payment rails, regulatory framework |
| [ACH Processing](ach.html) | NACHA SEC codes, processing flow, settlement timeline, return codes (R01–R29), NOC, compliance, reconciliation |
| [Fedwire](fedwire.html) | RTGS processing, ISO 20022 migration (March 2025), pacs.008 format, OFAC, recall procedures |
| [SWIFT](swift.html) | Correspondent banking, nostro/vostro, MT 103/202 and ISO 20022 MX equivalents, SWIFT gpi, gSRP recall |
| [RTP](rtp.html) | Real-time credit push, TCH architecture, Request for Payment, APP fraud controls |
| [FedNow](fednow.html) | Federal Reserve instant payments (live July 2023), liquidity management, correspondent access |
| [Card Networks](card.html) | Four-party model, authorization/clearing/settlement lifecycle, chargebacks, interchange |
| [Scenario Walkthroughs](scenarios.html) | 12 end-to-end operational scenarios across all rails |

---

## Project Scope & Approach

This documentation is designed to show:

- **System-level documentation** — not surface-level summaries. Each section documents processing flows, compliance checkpoints, exception handling, and reconciliation procedures.
- **Regulatory accuracy** — reflects current rules: NACHA Operating Rules (2026), Fedwire ISO 20022 migration (March 2025), FedNow adoption status (early 2026).
- **Enterprise documentation style** — structured topic architecture with admonitions (Note, Warning, Important, Tip), step-by-step procedures, decision tables, and reference tables. This mirrors the HTML documentation style used in MadCap Flare enterprise documentation environments.
- **Operations-first perspective** — written from the point of view of bank operations staff who process, monitor, and reconcile payments — not a developer or end-user guide.

---

## Background

This project draws on real-world documentation experience:

- **Fundtech India (2008–2010):** Authored configuration and operations documentation for CashIn and Global CASHplus — enterprise payment hub systems that are direct predecessors of today's Finastra GlobalPAYplus.
- **NICE Actimize (2017–present):** Enterprise HTML documentation (MadCap Flare) for financial crime prevention platforms, including transaction monitoring, fraud detection, and AML systems — all deeply integrated with payment rails.

---

## Live Site

Hosted on GitHub Pages: [View Live →](https://sulagnasasmal.github.io/us-payments-hub/)

---

## Author

**Sulagna Sasmal**
Senior Specialist Technical Writer | Documentation Architect
19+ years in FinTech, enterprise SaaS, and financial systems documentation
[Portfolio](https://sulagnasasmal.github.io/sulagnasasmal-site/) · [GitHub](https://github.com/SulagnaSasmal) · [DocCraft AI](https://doccraft-ten.vercel.app/)

---

## Dark / Light Mode

All pages support dark and light themes via a toggle button (◐ / ☀) in the header. Theme preference persists in `localStorage`. System `prefers-color-scheme` is respected on first visit.

## Status

**Phase 1 (Domain Documentation) — Complete / Stable**

| Rail / Section | Status |
|----------------|--------|
| Overview & Rail Comparison Matrix | Complete |
| ACH Processing (NACHA codes, returns R01–R29) | Complete |
| Fedwire (ISO 20022 migration, March 2025) | Complete |
| SWIFT Correspondent Banking (MT/MX) | Complete |
| RTP Real-Time Payments | Complete |
| FedNow Instant Payments | Complete |
| Card Network Processing | Complete |
| 12 Scenario Walkthroughs | Complete |
| Dark / light theme support | Complete |

## Future Enhancements

- FedNow Phase 2 features (Request for Payment, expanded liquidity tools)
- ISO 20022 MX message field reference tables
- SWIFT gpi tracker integration documentation
- NACHA Same Day ACH 2026 rule updates
