# 🛡️ Webamon Daily Threat Brief — Tuesday, 17 November 2026

**TLP:CLEAR** · Estate: 152 campaigns tracked · 1,077,023 unique domains · 77.7% online

Automated campaign intelligence from Webamon. Here's what our sensors saw across tracked phishing, fraud and malware-delivery estates in the last 24 hours.

## ⭐ New campaign spotlight — brandless "AI trading platforms", eight languages

One new tracked campaign this window: [Brandless AI Trading Platform Lead-Gen Kit (invented names, 8 languages)](https://intel.webamon.com/campaigns/e8d0fef667feab19f07a5c0453066bdfa3fccabd) — 40 domains, 95% online (38), first seen 19 August 2026, active today.

An investment-fraud lead-gen kit where every site carries a freshly invented platform name (Alinixio, ApoyVex, Akaudalorio, 1CFT, Arbiquant…) under the title template "`<Name> | AI Trading Platform | Official Website`", localised to EN/ES/IT/DE/FR/JA/KO/EL with a name + email + phone registration form. Exact DOM hashes are unique per site, so the fuzzy LSH `dom_band` 0 (current wave) and band 3 (Aug–Oct wave) are the census. Domains are aged before use — median 126 days from registration to first scan, batch-registered via NICENIC/Dynadot/Spaceship/NETIM and fronted by Cloudflare. Zero overlap with the tolfex, flags.webp and ADNOC Profit kits at promote.

## 📊 By the numbers (last 24h)

- **73** campaigns with activity
- **3,639** new malicious domains observed
- **665** domains went offline
- **16,177** infrastructure changes (IP/ASN/cert)
- **6,482** new page-title lures
- **200** emerging clusters live on the radar

## 🔍 What moved today

🔺 **Fastest-growing** — [Rolling sqllq.com subdomain phishing](https://intel.webamon.com/campaigns/2f41c3bbec077af4f1c44fff61a425759f949713) added 2,357 new domains — active registration/rotation in progress.

🔻 **Takedowns** — 109 domains in [Brazilian Casino Network (0007bet / 001bet / 001win / aavip)](https://intel.webamon.com/campaigns/0899610610c7f95d7b22ee8339b585b573f7a1b2) now NXDOMAIN, confirmed by double-checked DNS.

🔁 **Infra rotation** — the same Brazilian casino estate moved onto 3,917 new IPs, and [china k8 phishing portal](https://intel.webamon.com/campaigns/f8baac9d9fa365f2adf7414919aa45f6f37a0450) onto 4,460 new IPs. Refresh blocklists.

🎭 **Lure refresh** — 1,179 new page titles deployed across the Brazilian casino network; content templates are being rotated.

## 🎯 Campaigns worth a look

**[Fake CAPTCHA Gate Network (Verifying you are human)](https://intel.webamon.com/campaigns/aa0b592f46ffd72770beb082f8234379602ced70)** — 370 new domains in 24h across a 42,582-domain estate at 99% online.

**[Femo IT (AS214351) Bulletproof Phishing Estate + verificator.cc ClickFix](https://intel.webamon.com/campaigns/da5add1b8957951473127d5061d2eed4e89f68bd)** — 56 new domains, 12 offline; the bulletproof estate keeps cycling.

## 📡 On the radar — emerging clusters

200 clusters are live. Sharpest 24h growth:

    cert_san cluster — 9,989 domains, +352 (00poker[.]com)
    header_order cluster — 9,768 domains, +299
    ns_set cluster — 9,870 domains, +125 (0pterminal[.]com)
    asn cluster — 9,886 domains, +47 (007jshiqutanbifenwang[.]com[.]cn)

See the full brief and every tracked campaign live in the Webamon console → intel.webamon.com/campaigns

Full PDF brief is available daily from 12:00 UTC on our DTB GitHub repo → https://github.com/webamon-org/Daily-Threat-Brief

---

*Generated from Webamon campaign intelligence · TLP:CLEAR · Full daily brief and live feeds at [intel.webamon.com](https://intel.webamon.com)*
