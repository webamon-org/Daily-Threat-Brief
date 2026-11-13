# 🛡️ Webamon Daily Threat Brief — Friday, 13 November 2026

**TLP:CLEAR** · Estate: 150 campaigns tracked · 1,068,638 unique domains · 77.9% online

Automated campaign intelligence from Webamon. Here's what our sensors saw across tracked phishing and malware-delivery estates in the last 24 hours.

## ⭐ New campaign spotlight — localised AI-trading lead-gen at factory scale

We've added one new tracked campaign this window: [Localised AI-Trading "Official Site" Lead-Gen Kit (tolfex.com backend / BosaTheme)](https://intel.webamon.com/campaigns/b5a0583b27b5b9c6a4c9de2f815a86fa3d9ada57) — 243 domains, 100% online (243), first seen 23 July 2026, active today.

It's a factory-scale AI-trading investment-fraud kit: one throwaway invented brand per domain, localised per country (ES/AR/MX/BR/PT/DE/AT/CH/NO/SE/DK/NL/BE/FR/GR/IT/HR/CZ/SI/HU/RO/PL/UK/IE/AU/CA/JP/UAE), identical page structure, all loading operator backend host tolfex.com on a BosaTheme WordPress base. The NRD wave sits behind Cloudflare and adds roughly 6 new brands a day, abusing real firms in its lures (Pepperstone, Petrobras, 3G Capital, AltabourseETH, Quantum AI). Seeding is on the durable backend host, with dom_structure hash `21ec46f1` OR'd in as a fallback if the backend rotates. It is distinct from the [Multilingual AI-Trading Official Website Lead-Gen Fraud Kit](https://intel.webamon.com/campaigns/ccdfb17011a7a0f8d56d82f55bf4aa7353a5edda) (0 overlap) and the [ADNOC Profit /landers kit](https://intel.webamon.com/campaigns/c71af8377ebdf7d36f68f082ae844763932c37a9).

## 📊 By the numbers (last 24h)

- **74** campaigns with activity
- **4,598** new malicious domains observed
- **1,224** domains went offline
- **17,925** infrastructure changes (IP / ASN / cert)
- **7,911** new page-title lures
- **200** emerging clusters live

## 🔍 What moved today

🔺 **Fastest-growing** — [Rolling sqllq.com subdomain phishing](https://intel.webamon.com/campaigns/2f41c3bbec077af4f1c44fff61a425759f949713) added 2,619 new domains — active registration/rotation in progress.

🔻 **Takedowns** — 269 domains in the [2026 World Cup Chinese Gambling Doorway Network](https://intel.webamon.com/campaigns/0e9c79003e214820e4dda7ca94251baf9494fda0) are now NXDOMAIN, confirmed by double-checked DNS.

🔁 **Infra rotation** — [Brazilian Casino Network (0007bet / 001bet / 001win / aavip)](https://intel.webamon.com/campaigns/0899610610c7f95d7b22ee8339b585b573f7a1b2) moved onto 4,152 new IPs, and [china k8 phishing portal](https://intel.webamon.com/campaigns/f8baac9d9fa365f2adf7414919aa45f6f37a0450) onto 4,599 — refresh blocklists.

🎭 **Lure refresh** — [Brazilian Online Casino Doorway Network (Cassino Online Brasil, 944bet / 001WIN / 0007bet)](https://intel.webamon.com/campaigns/b78ce38e9f9e53ef933db4c098dc27ef239353a6) deployed 1,184 new page titles — templates are being rotated.

## 🎯 Campaigns worth a look

**[Crypto Wallet-Phishing / Fake-Airdrop Network (Ledger / Neoval Airdrops)](https://intel.webamon.com/campaigns/1f04e0b59f75fbdba150383a871ee2809ded3098)** — 9,033 domains, 100% online, with 54 new domains and 549 new page-title lures this window.

**[Fake CAPTCHA Gate Network (Verifying you are human)](https://intel.webamon.com/campaigns/aa0b592f46ffd72770beb082f8234379602ced70)** — 41,253 domains at 99% online; 87 new domains added today.

## 📡 On the radar — emerging clusters

 200 emerging clusters are live. Sharpest 24h growth:

    asn cluster — 9,824 domains, +556 in a day (loading)
    cert_san cluster — 9,899 domains, +235 (00poker[.]com)
    cert_config cluster — 10,000 domains, +142 (10x-partners[.]com)
    asn cluster — 9,879 domains, +53 (007jshiqutanbifenwang[.]com[.]cn)
    cert_config cluster — 9,914 domains, +46 (100000[.]best)


See the full brief and every tracked campaign live in the Webamon console → intel.webamon.com/campaigns

Full Pdf Brief is available daily from 12:00UTC on our DTB Github Repo → https://github.com/webamon-org/Daily-Threat-Brief

---

*Generated from Webamon campaign intelligence · TLP:CLEAR · Full daily brief and live feeds at [intel.webamon.com](https://intel.webamon.com)*
