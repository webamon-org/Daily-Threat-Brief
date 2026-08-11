# 🛡️ Webamon Daily Threat Brief — Tuesday, 11 August 2026

**TLP:CLEAR** · Estate: 85 campaigns tracked · 454,693 unique domains · 84.4% online

Automated campaign intelligence from Webamon. Here's what our sensors saw across tracked phishing and malware-delivery estates in the last 24 hours.

## ⭐ New campaign spotlight — verificator.cc ClickFix → Femo IT bulletproof estate

We've added a new tracked campaign this window: **[Femo IT (AS214351) Bulletproof Phishing Estate + verificator.cc ClickFix](https://intel.webamon.com/campaigns/da5add1b8957951473127d5061d2eed4e89f68bd)** — **624 domains, 62% still online (386), first seen 3 January 2026, active today.**

It started from a single `Win + R` screenshot search that surfaced a fake-Cloudflare **ClickFix** loader on `verificator.cc` — a cloned "Just a moment…" gate that poisons the clipboard with a fileless `irm …/verify.ps1 | iex` PowerShell command. Pivoting the loader's **cert-SAN fingerprint** onto its **ASN fingerprint** exposed the host beneath: **Femo IT Solutions Limited, AS214351 (Germany)** — a single bulletproof network where every tracked domain contacts only this ASN. It runs at least six parallel operations at once: hotel/PMS credential phishing (Rezlynx, Newbook, D-EDGE, DIRS21, Guestline), banking (SoFi, Navy Federal, E*TRADE), crypto-exchange spoofs (ChangeNOW, ff-exchange), gaming skin scams, fake-YouTube copyright lures, and the ClickFix info-stealer delivery itself.

OSINT associates AS214351 with the **defhost** brand (`defhost.co`) and a broad malicious-tooling set (Lumma, StealC, Rhadamanthys, RedLine, Evilginx/EvilGoPhish, Meduza and more) — consistent with a bulletproof host renting to many actors. New-domain volume is **surging in August** (16–22/day). The estate is now re-checked every 4 hours as a single tracked record.

## 📊 By the numbers (last 24h)

- **49** campaigns with activity
- **4,664** new malicious domains observed
- **910** domains went offline (NXDOMAIN, double-checked)
- **2,431** infrastructure changes (new IPs / ASNs / cert issuers)
- **1,569** new page-title lures
- **193** emerging clusters live on the radar

## 🔍 What moved today

🔺 **Fastest-growing** — [Chinese Gambling Portal Cluster (Dafa 6622 / Sun City / Vegas)](https://intel.webamon.com/campaigns/0186ddfd8038cf5a3cdb0d0619417f71b1874352) added 1,040 new domains — active registration and rotation in progress.

🔻 **Takedowns** — 433 domains in [Rolling sqllq.com subdomain phishing](https://intel.webamon.com/campaigns/2f41c3bbec077af4f1c44fff61a425759f949713) now resolve NXDOMAIN — takedowns/expiry confirmed by double-checked DNS.

🔁 **Infra rotation** — [china k8 phishing portal](https://intel.webamon.com/campaigns/f8baac9d9fa365f2adf7414919aa45f6f37a0450) moved onto 938 new IPs, and [Brazilian 'Plataforma Oficial' Betting Kit Family](https://intel.webamon.com/campaigns/f04cc4c7e2513dcd0015e26eea0755ea908f3aab) onto 802 — evasion or re-hosting behaviour; refresh blocklists.

🎭 **Lure refresh** — [Brazilian 'Plataforma Oficial' Betting Kit Family](https://intel.webamon.com/campaigns/f04cc4c7e2513dcd0015e26eea0755ea908f3aab) deployed 1,060 new page titles; [Brazilian Casino Affiliate Network (Fortune Tiger kit)](https://intel.webamon.com/campaigns/d03d579d5bc7412776cb84b82a97f32f45526f59) added 285 and [0007bet Gambling Cert Farm](https://intel.webamon.com/campaigns/bcbb5ca163da72c4ea5d6e415db7c59280d10606) 188 — templates are being cycled.

## 🎯 Campaigns worth a look

**[Fake CAPTCHA Gate Network (Verifying you are human)](https://intel.webamon.com/campaigns/aa0b592f46ffd72770beb082f8234379602ced70)** — 7,051 domains, 100% online, with 399 new domains this window across compromised-looking business names.

**[ClickFix Fake-Cloudflare Challenge Malware Delivery](https://intel.webamon.com/campaigns/8d53e1ff4ffa544dbb1bf36efcab0b540f03c3fd)** — smaller at 397 domains, but 99 infrastructure changes against 29 new domains: heavy re-hosting on a malware-delivery estate.

## 📡 On the radar — emerging clusters

193 clusters are live (111 critical, 82 high) — unattributed infrastructure large enough to promote to tracked campaigns. Sharpest 24h growth:

    ssl cluster — 7,915 domains, +788 in a day ("CNAME Cross-User Banned | Cloudflare")
    ssl cluster — 9,248 domains, +412 ("Attention Required! | Cloudflare")
    ssl cluster — 7,351 domains, +374 ("Just a moment...")

See the full brief and every tracked campaign live in the Webamon console → intel.webamon.com/campaigns

Full Pdf Brief is available daily from 12:00UTC on our DTB Github Repo → https://github.com/webamon-org/Daily-Threat-Brief

---

*Generated from Webamon campaign intelligence · TLP:CLEAR · Full daily brief and live feeds at [intel.webamon.com](https://intel.webamon.com)*
