# 🛡️ Webamon Daily Threat Brief — Thursday, 29 October 2026

**TLP:CLEAR** · Estate: 133 campaigns tracked · 1,021,597 unique domains · 79.5% online

Automated campaign intelligence from Webamon. Here's what our sensors saw across tracked phishing, scam and malware-delivery estates in the last 24 hours.

## ⭐ New campaign spotlight — xokwna / booster fake-shop kit on Tencent 119.28.63.231

We've added one new tracked campaign this window: [Fake-Shop Storefront Kit - xokwna / booster Multi-Brand Network (Tencent 119.28.63.231)](https://intel.webamon.com/campaigns/6c2228544f6e4aaabe10e3a54eebeab9f4108cae) — 2,389 domains, 100% online (2,380), first seen 25 March 2026, active today.

A single fake-shop kit (one shared JS bundle, `scripts:2a23fcbac937`) has been cloned across ~2,388 .com domains by one operator on Tencent origin 119.28.63.231 (2,385/2,388), fronted via Shopify 23.227.39.200 / Fastly 151.101.x. Multiple storefront brands reuse the kit — xokwna.online (~1,917 domains), booster.blenfe.com (465, loading product images from abimg.xokwna.online = same backend), plus named single shops such as hoobbyshop.com and photogearshops.com. Coined 6–8 letter .com SLDs carry no brand token, making the fleet invisible to typosquat-style DRP; fabricated electronics and jewelry storefronts with fake reviews and a POST checkout form indicate card-harvesting and goods that never ship. NameSilo NRDs with continuous minting (peak 167 new domains in a day).

## 📊 By the numbers (last 24h)

- **57** campaigns with activity
- **8,877** new malicious domains observed
- **13,175** domains went offline
- **15,736** infrastructure changes (IP / ASN / cert)
- **5,890** new page-title lures
- **200** emerging clusters live on the radar

## 🔍 What moved today

🔺 **Fastest-growing** — [Rolling sqllq.com subdomain phishing](https://intel.webamon.com/campaigns/2f41c3bbec077af4f1c44fff61a425759f949713) added 5,943 new domains — active registration/rotation in progress.

🔻 **Takedowns** — 12,301 domains in the [Gambling Affiliate Registration Redirect Network (Meteverse /app/register.php)](https://intel.webamon.com/campaigns/ec61331d3817418cbcf3dd1bf2ac7ac20cf48678) now resolve NXDOMAIN — takedowns/expiry confirmed by double-checked DNS.

🔁 **Infra rotation** — [Brazilian Casino Network (0007bet / 001bet / 001win / aavip)](https://intel.webamon.com/campaigns/0899610610c7f95d7b22ee8339b585b573f7a1b2) moved onto 4,214 new IPs and [china k8 phishing portal](https://intel.webamon.com/campaigns/f8baac9d9fa365f2adf7414919aa45f6f37a0450) onto 4,499 — evasion or re-hosting; refresh blocklists.

🎭 **Lure refresh** — the same Brazilian casino estate deployed 1,185 new page titles; content templates are being rotated.

## 🎯 Campaigns worth a look

**[Fake CAPTCHA Gate Network (Verifying you are human)](https://intel.webamon.com/campaigns/aa0b592f46ffd72770beb082f8234379602ced70)** — 644 new domains this window across a 33,203-domain estate at 99% online, including corporate-sounding lures such as lonergan-acquisitions.com.

**[Femo IT (AS214351) Bulletproof Phishing Estate + verificator.cc ClickFix](https://intel.webamon.com/campaigns/da5add1b8957951473127d5061d2eed4e89f68bd)** — 7 new domains, 8 offline, 3 infra changes and 2 new lures: small but continuously churning.

## 📡 On the radar — emerging clusters

 200 clusters are live. Sharpest 24h growth:

    scripts cluster — 9,748 domains, +90 (10-elfenland.de)
    header_order cluster — 9,872 domains, +75 (Access Restricted)
    dom_structure cluster — 9,826 domains, +64 (Site en construction)
    dom cluster — 9,876 domains, +53 (Not found)
    cert_san cluster — 9,788 domains, +45 (Non-compliance ICP Filing)

See the full brief and every tracked campaign live in the Webamon console → intel.webamon.com/campaigns

Full PDF brief is available daily from 12:00 UTC on our DTB GitHub repo → https://github.com/webamon-org/Daily-Threat-Brief

---

*Generated from Webamon campaign intelligence · TLP:CLEAR · Full daily brief and live feeds at [intel.webamon.com](https://intel.webamon.com)*
