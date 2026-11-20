# Portfolio Page Structure

Your Reen's Tech Vault portfolio now has a hierarchical page structure with dedicated sections for each topic!

## 📑 Main Navigation

**Main Index Page:** `index.html`
- Updated navigation with links to new pages:
  - `~/home` → Home section
  - `~/vault` → Lab Artifacts section  
  - `~/clean-slate` → Operation Clean Slate hub
  - `~/credentials` → PAM Systems hub
  - `~/certs` → Credentials section
  - `~/ping` → Contact section

---

## 🧹 Operation Clean Slate Section

**Hub Page:** `clean-slate.html`
- Overview of Operation Clean Slate initiative
- 6 topic cards linking to detailed pages

### Sub-Pages (Topic Details):

1. **`clean-slate-centralized-credentials.html`** 🔐
   - Delinea Secret Server overview
   - TACACS authentication status
   - Credential management best practices
   - **Status:** ✅ Complete with detailed content

2. **`clean-slate-local-accounts.html`** 👤
   - Local accounts audit overview
   - Placeholder for detailed findings
   - **Status:** 🚧 Content template ready

3. **`clean-slate-firewalls.html`** 🔥
   - Firewall credential management
   - **Status:** 🚧 Content template ready

4. **`clean-slate-juniper-nxos.html`** 🌐
   - Juniper and Cisco NX-OS device credentials
   - **Status:** 🚧 Content template ready

5. **`clean-slate-service-accounts.html`** ⚙️
   - Service account and FID management
   - **Status:** 🚧 Content template ready

6. **`clean-slate-servers-other.html`** 💾
   - Server and miscellaneous device credentials
   - **Status:** 🚧 Content template ready

---

## 🔑 PAM & Credential Systems Section

**Hub Page:** `pam-systems.html`
- Overview of three PAM systems
- 3 service cards with descriptions and links

### Sub-Pages (PAM Guides):

1. **`pam-delinea.html`** 🏛️
   - Delinea Secret Server onboarding
   - Vault access request process
   - BARS group and AD access
   - **Status:** ✅ Complete with comprehensive guide

2. **`pam-keeper.html`** 🗝️
   - Keeper Password Vault setup
   - Access and authentication steps
   - Import procedures
   - Support contacts
   - **Status:** ✅ Complete with detailed guide

3. **`pam-hashicorp.html`** ⚡
   - HashiCorp Vault documentation
   - FID password rotation
   - Vault environments (Prod/Dev)
   - Integration examples
   - **Status:** ✅ Complete with thorough documentation

---

## 📊 Page Features

### Navigation
- Each sub-page has:
  - Back button to parent hub
  - Navigation bar with links to all major sections
  - Breadcrumb trail showing context

### Styling
- Consistent kawaii color palette
- Responsive design across devices
- Floating decorative elements
- Color-coded sections:
  - 🧹 Clean Slate: Mint green theme
  - 🔐 Delinea: Pink/magenta accents
  - 🗝️ Keeper: Blue theme
  - ⚡ HashiCorp: Golden/yellow theme

### Content Types
- Detailed guides with step-by-step instructions
- Tables and status indicators
- Code examples and reference information
- Warning/info/note boxes for important details
- Table of contents for quick navigation

---

## 🔗 Navigation Hierarchy

```
index.html (Main Portfolio)
├── clean-slate.html (Operation Clean Slate Hub)
│   ├── clean-slate-centralized-credentials.html
│   ├── clean-slate-local-accounts.html
│   ├── clean-slate-firewalls.html
│   ├── clean-slate-juniper-nxos.html
│   ├── clean-slate-service-accounts.html
│   └── clean-slate-servers-other.html
│
├── pam-systems.html (PAM Systems Hub)
│   ├── pam-delinea.html
│   ├── pam-keeper.html
│   └── pam-hashicorp.html
│
├── Lab Artifacts (in-page section)
└── About/Credentials (in-page section)
```

---

## 🚀 Next Steps

1. **Deploy to GitHub Pages:**
   - Push all new HTML files to your repository
   - GitHub Pages will serve them automatically

2. **Add More Content (Optional):**
   - Replace placeholder content in Clean Slate pages with detailed findings
   - Add additional guides or documentation as needed

3. **Monitor Links:**
   - Verify all navigation links work correctly
   - Test on mobile and desktop browsers

4. **Customize Further:**
   - Add images or diagrams to the PAM guides
   - Include screenshots or examples
   - Expand placeholder sections with real content

---

## 📋 File Checklist

✅ **Main Page:** index.html (updated)
✅ **Operation Clean Slate Pages:**
  - clean-slate.html (hub)
  - clean-slate-centralized-credentials.html
  - clean-slate-local-accounts.html
  - clean-slate-firewalls.html
  - clean-slate-juniper-nxos.html
  - clean-slate-service-accounts.html
  - clean-slate-servers-other.html

✅ **PAM Systems Pages:**
  - pam-systems.html (hub)
  - pam-delinea.html
  - pam-keeper.html
  - pam-hashicorp.html

---

**Total Pages Created:** 13 new HTML files
**All pages:** Fully styled with responsive design and consistent theming
