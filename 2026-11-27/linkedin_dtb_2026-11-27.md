# 🛡️ Webamon Daily Threat Brief — Friday, 27 November 2026

**TLP:CLEAR** · Estate: 153 campaigns tracked · 1,094,617 unique domains · 75.9% online

Automated campaign intelligence from Webamon. Here's what our sensors saw across tracked phishing and malware-delivery estates in the last 24 hours.

## ⭐ New campaign spotlight — Martin Lewis "Quantum AI" fake BBC investment lure

We've added a new tracked campaign this window: [Martin Lewis "Quantum AI" Fake BBC / MoneySavingExpert Investment Lure](https://intel.webamon.com/campaigns/5afa52a6ffe435647305c8ea84eae3b077e0da36) — 14 domains, 57% online (8), first seen 3 November 2026, active today.

A UK fake-news investment lure: a BBC Business article clone (11 domains) or a MoneySavingExpert clone (3) claims the government and Martin Lewis back "Quantum AI", promising up to £45,000/month from a £200 stake. A `send.php` lead form harvests name, email and phone with TikTok `ttclid` tracking, while JavaScript writes the next day as the "apply by" deadline to manufacture urgency. The root serves a decoy business site or 404 to non-ad visitors. Namecheap two-word .click/.cloud domains are registered in waves, typically the day before first scan. Found by Daily Hunt on 26 November 2026.

## 📊 By the numbers (last 24h)

- **79** campaigns with activity
- **4,539** new malicious domains observed
- **3,288** domains went offline
- **12,343** infrastructure changes (IP / ASN / cert)
- **6,412** new page-title lures
- **200** emerging clusters live on the radar

## 🔍 What moved today

🔺 **Fastest-growing** — [Rolling sqllq.com subdomain phishing](https://intel.webamon.com/campaigns/2f41c3bbec077af4f1c44fff61a425759f949713) added 3,317 new domains — active registration/rotation in progress.

🔻 **Takedowns** — 1,044 domains in the [Indonesian Slot-Gacor Network (aceh999 / bajing33 / candy89)](https://intel.webamon.com/campaigns/050f61e924316e2a9d73ca12ee0d9b09dada5dde) now NXDOMAIN — takedowns/expiry confirmed by double-checked DNS.

🔁 **Infra rotation** — [china k8 phishing portal](https://intel.webamon.com/campaigns/f8baac9d9fa365f2adf7414919aa45f6f37a0450) moved onto 3,915 new IPs, and [Brazilian Casino Network (0007bet / 001bet / 001win / aavip)](https://intel.webamon.com/campaigns/0899610610c7f95d7b22ee8339b585b573f7a1b2) onto 3,822 — refresh blocklists.

🎭 **Lure refresh** — [Brazilian Online Casino Doorway Network (Cassino Online Brasil, 944bet / 001WIN / 0007bet)](https://intel.webamon.com/campaigns/b78ce38e9f9e53ef933db4c098dc27ef239353a6) deployed 1,189 new page titles — templates are being rotated.

## 🎯 Campaigns worth a look

**[Fake CAPTCHA Gate Network (Verifying you are human)](https://intel.webamon.com/campaigns/aa0b592f46ffd72770beb082f8234379602ced70)** — 446 new domains this window across a 47,903-domain estate at 99% online.

**[Crypto Wallet-Phishing / Fake-Airdrop Network (Ledger / Neoval Airdrops)](https://intel.webamon.com/campaigns/1f04e0b59f75fbdba150383a871ee2809ded3098)** — 19 new domains and 118 new page-title lures across 9,322 domains, all online.

## 📡 On the radar — emerging clusters

 200 clusters are live. Sharpest 24h growth:

    ssl cluster — 9,770 domains, +228 in a day (0un1[.]com)
    ns_set cluster — 9,732 domains, +41 (GNAME | Domain Broker Service)
    cert_san cluster — 9,929 domains, +28 ("This domain is not linked to any directory")
    scripts cluster — 9,692 domains, +21 (017brl-ios[.]com)
    dom cluster — 9,618 domains, +18 (STRATO - Domain reserved)

See the full brief and every tracked campaign live in the Webamon console → intel.webamon.com/campaigns

Full Pdf Brief is available daily from 12:00UTC on our DTB Github Repo → https://github.com/webamon-org/Daily-Threat-Brief

---

*Generated from Webamon campaign intelligence · TLP:CLEAR · Full daily brief and live feeds at [intel.webamon.com](https://intel.webamon.com)*
