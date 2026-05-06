# NC SBI — Center for Safer Schools | Portal Demo

A fully interactive front-end demonstration of a proposed web hosting and content management solution for the **North Carolina State Bureau of Investigation (NC SBI) Center for Safer Schools (CFSS)**.

> **This is a proposal demonstration prototype. It is not an official NC SBI or State of North Carolina website.**

---

## Live Demo

[View the Live Demo](https://YOUR-USERNAME.github.io/nc-sbi-demo/)

---

## What This Demo Shows

This prototype demonstrates a fully managed, NIST 800-53 compliant digital platform delivering training, resources, and stakeholder engagement across four distinct secure portals.

### Four Secure Training Portals

| Portal | Audience | Authentication |
|---|---|---|
| 🚔 Law Enforcement | NC law enforcement officers & SBI personnel | Microsoft Entra ID + PIV + MFA |
| 🏫 School Admins & Teachers | NC educators and district administrators | Entra ID / District SSO + MFA |
| 🎒 Students | NC students, Grades 6–12 | School SSO (Google / Microsoft 365) |
| 🌐 General Public | NC families and community members | Free registration + email verification |

---

## Key Capabilities Demonstrated

- **CMS Platform** — WordPress or Drupal open-source foundation, fully managed
- **Identity Management** — Microsoft Entra ID for internal NC SBI users; MFA for all external users
- **Four Distinct Portals** — Audience-specific branding, authentication, and training content
- **NIST 800-53 Moderate** — Security controls, audit logging, access management
- **WCAG 2.1 / Section 508** — AA-level accessibility, screen-reader compatible
- **CDN + DDoS Protection** — Global edge delivery, automated attack mitigation
- **Disaster Recovery** — RPO 4hr / RTO 8hr, geo-redundant backup
- **99.9% Uptime SLA** — Managed infrastructure with proactive monitoring

---

## How to Run Locally

No build tools or dependencies required. This is a single self-contained HTML file.

```bash
# Clone the repo
git clone https://github.com/YOUR-USERNAME/nc-sbi-demo.git

# Open in your browser
open nc-sbi-demo/index.html
```

Or simply double-click `index.html` to open it in any modern browser.

---

## How to Deploy on GitHub Pages

1. Push `index.html` to the `main` branch of your repository
2. Go to **Settings → Pages**
3. Under **Source**, select `main` branch, folder `/root`
4. Click **Save**
5. Your demo will be live at `https://YOUR-USERNAME.github.io/nc-sbi-demo/`

---

## Project Structure

```
nc-sbi-demo/
│
├── index.html       # Complete demo — single self-contained file
└── README.md        # This file
```

---

## Platform Scope

This demo covers the following service areas:

- Design and development of a new public-facing CFSS website
- Implementation of four secure training portals
- Microsoft Entra ID integration for internal NC SBI staff
- Multi-factor authentication for external contributors
- NIST 800-53 Moderate security compliance
- CDN, DDoS protection, and disaster recovery
- WCAG 2.1 / Section 508 accessibility
- Staff training and ongoing content management support



---

## Disclaimer

This repository contains a **demonstration prototype only**. It does not represent an official NC SBI or State of North Carolina website. All portal screens, login forms, and training content shown are illustrative mockups. No real user data is collected or transmitted.

---

*Built to demonstrate secure government web portal architecture for a state-level school safety platform.*
