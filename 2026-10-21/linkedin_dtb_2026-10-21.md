# 🛡️ Webamon Daily Threat Brief — Wednesday, 21 October 2026

**TLP:CLEAR** · Estate: 132 campaigns tracked · 999,637 unique domains · 81.1% online

Automated campaign intelligence from Webamon. Here's what our sensors saw across tracked phishing and malware-delivery estates in the last 24 hours.

## ⭐ New campaign spotlight — Coinbase "Verify Identity" operator-in-the-loop ATO

We've added [Coinbase "Verify Identity" Operator-in-the-Loop Takeover Kit (numbered lookalikes)](https://intel.webamon.com/campaigns/2aa8731088beebbb11f2c07acdc2067dc258544f) — 6 domains, 100% online (5), first seen 31 May 2026, active today.

A real-time Coinbase account-takeover kit hosted on `NNNNNNcoinbase.com` lookalikes: a "Verify Identity" holding page paired with a fake Coinbase Support chat. The page polls `/api/sessions/<id>/injection` so a human operator can push screens to the victim live, with backend endpoints covering seedphrase, generated-seed, vault-balances, password, snap and mutations. Six domains since 31 May, five live at card.

Also new this window: [Turnstile-Gated "Secure Gateway Portal" Cloaking Fleet (SSO-endpoint naming)](https://intel.webamon.com/campaigns/fa887378a95135dc676dfe0e3d7c3f139b9ddbee) and [Coined "Swiss Investment Platform" Fake Wealth-Manager Kit](https://intel.webamon.com/campaigns/1c0e9605c7c97e1890f217f79dfada98f8a57a0f).

## 📊 By the numbers (last 24h)

- **56** campaigns with activity
- **5,767** new malicious domains observed
- **644** domains went offline
- **5,489** infrastructure changes (IP / ASN / cert)
- **3,937** new page-title lures
- **200** emerging clusters live on the radar

## 🔍 What moved today

🔺 **Fastest-growing** — [Rolling sqllq.com subdomain phishing](https://intel.webamon.com/campaigns/2f41c3bbec077af4f1c44fff61a425759f949713) added 3,289 new domains — active registration/rotation in progress.

🔻 **Takedowns** — 75 domains in [Gambling Infra ASN+SSL Pair (.vip/.cc)](https://intel.webamon.com/campaigns/c89bdabcb2cb4ae583fa4c4baf6e635675e59834) now NXDOMAIN, confirmed by double-checked DNS.

🔁 **Infra rotation** — [Brazilian Casino Network (0007bet / 001bet / 001win / aavip)](https://intel.webamon.com/campaigns/0899610610c7f95d7b22ee8339b585b573f7a1b2) moved onto 2,205 new IPs; [Brazilian Online Casino Doorway Network (Cassino Online Brasil, 944bet / 001WIN / 0007bet)](https://intel.webamon.com/campaigns/b78ce38e9f9e53ef933db4c098dc27ef239353a6) onto 931 — refresh blocklists.

🎭 **Lure refresh** — the same Brazilian Casino Network deployed 1,160 new page titles.

## 🎯 Campaigns worth a look

**[Fake CAPTCHA Gate Network (Verifying you are human)](https://intel.webamon.com/campaigns/aa0b592f46ffd72770beb082f8234379602ced70)** — 753 new domains this window across a 29,549-domain estate at 99% online.

## 📡 On the radar — emerging clusters

 200 emerging clusters are live. Sharpest 24h growth:

    cookie_names cluster — 9,995 domains, +342 in a day
    header_order cluster — 10,000 domains, +309 (Parking Page)
    header_order cluster — 9,687 domains, +235 (100baisui[.]com)
    ssl cluster — 9,804 domains, +147 (010211[.]xyz)

See the full brief and every tracked campaign live in the Webamon console → intel.webamon.com/campaigns

Full Pdf Brief is available daily from 12:00UTC on our DTB Github Repo → https://github.com/webamon-org/Daily-Threat-Brief

---

*Generated from Webamon campaign intelligence · TLP:CLEAR · Full daily brief and live feeds at [intel.webamon.com](https://intel.webamon.com)*
