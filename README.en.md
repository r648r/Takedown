# 🤼 E-commerce Clone Takedown — Procedure

[🇫🇷 Français](README.md) · 🇬🇧 **English**

A practical playbook for getting **fraudulent clones of an e-commerce site** taken
down — the scam sites that copy a brand to phish customers or run card fraud.
Covers the legal levers (DSA), the actors to contact, and a recon toolkit to find
and document the clones.

> ℹ️ The full step-by-step procedure, e-mail templates and scripts are written
> **in French** — see **[README.md](README.md)**. This page is an overview.

## Methodology

1. **Identify & document the clones** — find the copycat domains, capture proof
   (screenshots, WHOIS, hosting, registrar).
2. **Report** to the clone's **host / CDN / HTTPS proxy** and to the domain
   **registrar** (abuse channels, DSA notice).
3. **De-index** via Google Search Console and report the associated **ads**.
4. **Escalate** — apply pressure when the first reports are ignored.

## Recon toolkit

A Bash pipeline to triage candidate domains at scale:

- **WHOIS** extraction (registrar, dates, contacts)
- **DNS** resolution & checks
- **Dorking** to surface clones and exposed assets
- **HTTP** probing (status, fingerprints)
- structured **JSON** output + summary statistics for analysis

## Key terms

DSA (Digital Services Act) · Dark/black-hat SEO · hosting provider · registrar ·
scammer / "scamma" (resold scam templates) · user-agent · WHOIS.

> ⚠️ Defensive / brand-protection use only, against fraudulent clones — on targets
> you are authorized to investigate.
