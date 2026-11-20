# Reen's Tech Vault

A personal portfolio for network engineering, cybersecurity, and hands-on lab work. The single-page site uses a pastel, retro-terminal design and is hosted with GitHub Pages.

## Portfolio sections

- **The Vault:** Network and security lab artifacts.
- **Operation Clean Slate:** A sanitized, high-level account-hygiene and security-documentation project summary.
- **About:** Certifications and technical focus areas.
- **Contact:** Collaboration and professional contact options.

## Operation Clean Slate

The public project summary describes a structured approach to privileged-account hygiene:

1. Inventory and classify account types and authentication patterns.
2. Review ownership, access, and credential-lifecycle risks.
3. Prioritize remediation themes and produce practical documentation.
4. Distinguish human-managed passwords from application secrets and automated rotation.

The public portfolio intentionally excludes organization names, device and account identifiers, network details, access-group names, proprietary architecture, and credentials.

## Certifications

- **Cisco Certified Network Associate (CCNA 200-301)**
- **CompTIA Security+ (SY0-701)**

## Technical focus

- **Routing and switching:** OSPF, EIGRP, BGP, RSTP, EtherChannel
- **Network security and SOC:** Wireshark, IDS/IPS, SIEM triage
- **Zero trust and tunneling:** IPsec, WireGuard, RADIUS, TACACS+

## Files

- `index.html` — page content and navigation.
- `vault-portfolio.css` — layout, theme, and responsive styles.
- `vault-portfolio.js` — mobile navigation, active-section state, and page interactions.
- `images/` — original tech-themed SVG illustrations used by the rotating hero, featured lab, credentials section, and artifact cards.

## Design credit

The site adapts Tooplate's “Sweet Bakery” HTML/CSS template. The existing footer attribution is retained.

## Preview locally

Open `index.html` in a browser, or run a local static server from the repository root:

```sh
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Hosting

GitHub Pages publishes the site from this repository. Commit and push approved changes to the configured publishing branch to update the live portfolio.
.
