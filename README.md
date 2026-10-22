<div align="center">

# 🇲🇺 MorisMoney Compass

**Know your money. Explore your options. Make clearer decisions.**

A Mauritius-first financial resilience companion for individuals, self-employed people, and small businesses.

[![Launch MorisMoney Compass](https://img.shields.io/badge/LAUNCH_LIVE_DEMO-OPEN_MORISMONEY-12A889?style=for-the-badge)](https://aurex-sicos.github.io/MoneyCompassApp/)

### [🚀 Launch the interactive demo](https://aurex-sicos.github.io/MoneyCompassApp/)

**English · Français · Kreol Morisien**

</div>

---

## 🌱 About MorisMoney

MorisMoney Compass is an educational prototype designed in Mauritius to make everyday financial decisions easier to understand. It helps people see their available money, upcoming commitments, protected reserve, and what different financing choices could mean for their plans.

The guiding principle is **understanding before deciding** — not telling people what to buy, borrow, or invest in.

## ✨ Explore the app

| Journey | What it helps you do |
| --- | --- |
| 🏠 **HOME** | See available cash and a separate **Planning Buffer** after relevant commitments and protected reserve. |
| 📊 **RUN** | Record income, expenses and commitments; review money in and out, and confirm older future-dated transactions before counting them as completed. |
| 🧮 **DECIDE** | Compare financing options, monthly repayments and total costs; explore *what-if* changes to income or expenses. |
| 🌿 **GROW** | Set savings goals, explore reserve planning and build financial resilience. |
| 🛡️ **PROTECT** | Review explainable text-based warning indicators in English, French, Kreol Morisien and some mixed-language messages. |
| 🔎 **Scam Watch** | Consult links to official sources and explore **fictional** community-report examples, clearly separated from official warnings. |

## ▶️ Try the fictional demo

1. Open **[the live interactive demo](https://aurex-sicos.github.io/MoneyCompassApp/)**.
2. On the welcome screen, choose **Try Demo**.
3. Follow **HOME → RUN → DECIDE → GROW → PROTECT → Scam Watch** through Maya's fictional small-business journey.
4. Use the **Demo** control to restart the example or exit back to your own browser state.

Maya's original fictional scenario includes:

| Example figure | Amount |
| --- | ---: |
| Current cash | **Rs 50,000** |
| Protected reserve | Rs 7,000 |
| Commitments due before expected income | Rs 21,500 |
| **Planning Buffer** | **Rs 21,500** |

The Planning Buffer is an illustration for planning; it is **not** a guarantee that the amount can safely be spent.

### 🛡️ Try a warning-indicator example

Under **PROTECT**, select **Try fictional example**, then **Check warning indicators**. The example button cycles through reviewed fictional messages, starting with mixed French–English and English–French–Kreol examples, alongside investment, payment-redirection, credential-request and ordinary-business examples.

The rule-based checker highlights configured wording patterns and quotes the text that triggered them. **It does not visit links, check website reputation, establish fraud or guarantee safety.** Some suspicious messages — including other mixed-language wording — may not be recognised. The sample messages are demonstrations, not an independently validated detection-accuracy benchmark.

## 🔐 Privacy & responsible use

- This is a **demonstration and educational tool**, not personalised financial, lending, investment or legal advice.
- **Please do not paste real PINs, OTPs, passwords, complete banking credentials, account details or sensitive personal information.**
- App data is kept in the visitor's **own browser storage**, not a shared MorisMoney reporting database. On a shared device, use a temporary/private browser profile and clear that profile's site data afterwards.
- Older future-dated income and expense records require **manual confirmation** before being included in completed-transaction totals. Reaching a scheduled date does not confirm payment or receipt; confirmation does not automatically change the separately recorded cash balance.
- Official source links, MorisMoney's warning indicators and **fictional community reports** have different evidentiary status. Fictional report forms do not publish or transmit real allegations.
- The static public website does **not** expose the experimental local AI server endpoint or enable live identification/reputation checking.
- Rule-based multilingual detection is **not** independently certified. No-hit results do not mean that a message is safe.

## 🛠️ Built with

**Next.js · React · TypeScript · Tailwind CSS · Zod · Vitest · Capacitor**

The underlying project supports web and Android-oriented builds. **This GitHub Pages edition is a compiled static website** and does not include an APK or backend API.

## 📦 About this public repository

**[AUREX-SICOS/MoneyCompassApp](https://github.com/AUREX-SICOS/MoneyCompassApp)** hosts only the **compiled public demo assets** and its GitHub Pages deployment workflow:

- `site/` — static exported pages, browser scripts, styles and assets.
- `.github/workflows/deploy-pages.yml` — the manually triggered deployment of the reviewed compiled site.
- `README.md` — this public-facing guide.

**This is not the development-source repository.** The private development code, tests, research materials and build scripts are **not distributed here**. Commands such as `npm ci` or `npm run dev` cannot build the app from this public repository.

All source changes are built and tested separately, checked for unintended private or sensitive assets, and then transferred to `site/` as compiled output. The published public repository retains its Git history so a prior compiled release can be restored if necessary.

---

<div align="center">

**Made for Mauritius 🇲🇺 · Money Minds App Challenge 2026**

[🚀 Live Demo](https://aurex-sicos.github.io/MoneyCompassApp/) · [📦 Public Demo Repository](https://github.com/AUREX-SICOS/MoneyCompassApp)

</div>
