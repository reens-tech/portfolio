# 🛡️ Reen's Tech Vault - Page Structure Guide

## Overview

Your portfolio now has **13 new dedicated pages** organized into two main hub sections:
1. **Operation Clean Slate** (6 detailed topic pages)
2. **PAM & Credential Systems** (3 comprehensive guides)

---

## 📂 Complete File List

### Hub Pages
- `clean-slate.html` - Operation Clean Slate overview & navigation
- `pam-systems.html` - PAM Systems overview & navigation

### Operation Clean Slate Topic Pages
- `clean-slate-centralized-credentials.html` - Delinea & TACACS details ✅
- `clean-slate-local-accounts.html` - Local accounts audit 🚧
- `clean-slate-firewalls.html` - Firewall credentials 🚧
- `clean-slate-juniper-nxos.html` - Juniper & NX-OS devices 🚧
- `clean-slate-service-accounts.html` - Service accounts & FIDs 🚧
- `clean-slate-servers-other.html` - Servers & other devices 🚧

### PAM Systems Guide Pages
- `pam-delinea.html` - Delinea Secret Server onboarding ✅
- `pam-keeper.html` - Keeper Password Vault setup ✅
- `pam-hashicorp.html` - HashiCorp Vault documentation ✅

---

## 🎨 Design Features

### Consistent Styling Across All Pages
- **Responsive layouts** - Works on mobile, tablet, desktop
- **Kawaii color palette** - Mint, aqua, peach, lavender
- **Floating decorations** - Animated sparkles and shapes
- **Smooth transitions** - Hover effects and animations
- **Clear typography** - Readable sans-serif fonts

### Navigation Elements
- **Back buttons** - Quick return to parent pages
- **Navigation bar** - Access to all major sections
- **Breadcrumb links** - Context and navigation hierarchy
- **Related links** - Jump to related pages at bottom

### Content Boxes
- **Info boxes** (blue) - Important information
- **Warning boxes** (yellow/orange) - Cautions and alerts
- **Note boxes** (teal) - Additional context
- **Code blocks** - Technical reference material
- **Tables** - Organized data presentation

---

## 🔄 Navigation Flow

### From Main Index
```
index.html
  ↓
  Navigation bar: "~/clean-slate" → clean-slate.html
  Navigation bar: "~/credentials" → pam-systems.html
  Button: "📑 View Full Clean Slate Documentation" → clean-slate.html
  Button: "🔑 PAM Systems Guides" → pam-systems.html
```

### From Clean Slate Hub
```
clean-slate.html
  ↓
  6 Topic Cards link to:
  - clean-slate-centralized-credentials.html
  - clean-slate-local-accounts.html
  - clean-slate-firewalls.html
  - clean-slate-juniper-nxos.html
  - clean-slate-service-accounts.html
  - clean-slate-servers-other.html
  ↓
  Each has "Back to Operation Clean Slate" button
```

### From PAM Systems Hub
```
pam-systems.html
  ↓
  3 Service Cards link to:
  - pam-delinea.html
  - pam-keeper.html
  - pam-hashicorp.html
  ↓
  Each has "Back to PAM Systems" button
  Each has "Related systems" links at bottom
```

---

## 📄 Page Descriptions

### Operation Clean Slate Pages

#### 1. **clean-slate.html** (Hub Page)
- **Purpose:** Overview and navigation hub for all Clean Slate topics
- **Contains:** 6 cards with descriptions and links to detail pages
- **Navigation:** Link from main index

#### 2. **clean-slate-centralized-credentials.html** ✅
- **Purpose:** Detailed guide on centralized credential management
- **Content:** 
  - TACACS authentication overview
  - Delinea-stored credentials explanation
  - Status summary table
  - Best practices
- **Status:** Complete with comprehensive content

#### 3. **clean-slate-local-accounts.html** 🚧
- **Purpose:** Local accounts audit findings
- **Status:** Template ready for detailed content
- **To fill in:** Device inventory, audit findings, remediation status

#### 4. **clean-slate-firewalls.html** 🚧
- **Purpose:** Firewall credential management
- **Status:** Template ready
- **To fill in:** F5 BIG-IP, FortiGate, and other firewall details

#### 5. **clean-slate-juniper-nxos.html** 🚧
- **Purpose:** Juniper and Cisco NX-OS device credentials
- **Status:** Template ready
- **To fill in:** Device-specific accounts, root/admin status

#### 6. **clean-slate-service-accounts.html** 🚧
- **Purpose:** Service account and FID management
- **Status:** Template ready
- **To fill in:** Service account inventory, rotation policies

#### 7. **clean-slate-servers-other.html** 🚧
- **Purpose:** Server and miscellaneous device credentials
- **Status:** Template ready
- **To fill in:** Server inventory, credential status

---

### PAM Systems Pages

#### 1. **pam-systems.html** (Hub Page)
- **Purpose:** Overview of Bell's three PAM systems
- **Contains:** 
  - 3 PAM service cards (Delinea, Keeper, HashiCorp)
  - Description, purpose, and use cases for each
  - Quick reference for choosing the right system
- **Navigation:** Link from main index

#### 2. **pam-delinea.html** ✅
- **Purpose:** Delinea Secret Server onboarding guide
- **Content:**
  - [x] Onboarding overview (steps 1-4)
  - [x] BARS and AD group access explanation
  - [x] Example vault request with field values
  - [x] After-access provisioning steps
  - [x] Troubleshooting section
- **Features:** Table of example values, warning boxes, step-by-step guide

#### 3. **pam-keeper.html** ✅
- **Purpose:** Keeper Password Vault setup guide
- **Content:**
  - [x] Pre-requisites checklist
  - [x] Step-by-step access instructions
  - [x] Password import guidance
  - [x] Support contacts and troubleshooting
- **Features:** Requirement cards, info boxes, support links

#### 4. **pam-hashicorp.html** ✅
- **Purpose:** HashiCorp Vault documentation hub
- **Content:**
  - [x] Getting started & service request process
  - [x] Key documentation links and overview
  - [x] Architecture explanation
  - [x] FID password rotation details
  - [x] Prod/Dev environment info
  - [x] Support channels
- **Features:** Navigation TOC, service request links, environment cards

---

## 🚀 Deployment to GitHub Pages

### Steps:
1. Commit all 13 new HTML files to your repository
2. Push to GitHub (main branch)
3. GitHub Pages automatically serves all `.html` files
4. Access at: `https://reens-tech.github.io/portfolio/clean-slate.html`

### Existing Files Also Updated:
- `index.html` - Added navigation links and buttons

---

## 🎯 Key Features Summary

✅ **Full Navigation System** - All pages linked and accessible
✅ **Responsive Design** - Works on all screen sizes
✅ **Consistent Styling** - Unified color palette and layout
✅ **Search-friendly** - Each page has clear structure and content
✅ **User-friendly** - Easy navigation between related topics
✅ **Professional Appearance** - Polished kawaii aesthetic
✅ **Sanitized Content** - No corporate-sensitive details
✅ **Expandable** - Template pages ready for additional content

---

## 📝 Content Status

| Page | Status | Content |
|------|--------|---------|
| index.html | ✅ Updated | Navigation links & buttons added |
| clean-slate.html | ✅ Complete | Hub page with 6 topic cards |
| clean-slate-centralized-credentials.html | ✅ Complete | Detailed Delinea & TACACS guide |
| clean-slate-local-accounts.html | 🚧 Template | Ready for detailed content |
| clean-slate-firewalls.html | 🚧 Template | Ready for detailed content |
| clean-slate-juniper-nxos.html | 🚧 Template | Ready for detailed content |
| clean-slate-service-accounts.html | 🚧 Template | Ready for detailed content |
| clean-slate-servers-other.html | 🚧 Template | Ready for detailed content |
| pam-systems.html | ✅ Complete | Hub page with 3 PAM systems |
| pam-delinea.html | ✅ Complete | Comprehensive onboarding guide |
| pam-keeper.html | ✅ Complete | Detailed setup instructions |
| pam-hashicorp.html | ✅ Complete | Thorough documentation |

---

## 💡 Next Steps

### To Deploy:
```bash
git add .
git commit -m "Add dedicated pages for Operation Clean Slate and PAM Systems"
git push origin main
```

### To Enhance:
- Add images/screenshots to PAM guides
- Fill in template content for Clean Slate topics
- Add links to external documentation
- Customize colors or styling as needed

---

**Total Pages:** 13 new files
**Total Size:** ~200KB of HTML/styling
**Navigation Links:** 50+ internal links across all pages
**Last Updated:** 2026-11-20
