# 🛡️ Webamon Daily Threat Brief — Sunday, 08 November 2026

**TLP:CLEAR** · Estate: 148 campaigns tracked · 1,057,468 unique domains · 78.5% online

Automated campaign intelligence from Webamon. Here's what our sensors saw across tracked phishing and malware-delivery estates in the last 24 hours.

## ⭐ New campaign spotlight — parked domains → fake "Secure File Download" landers

We've added a new tracked campaign this window: [Parked-Domain Malvertising to Fake "Secure File Download" Landers (rtmark TDS)](https://intel.webamon.com/campaigns/386d7c4b354682ffdc00b4f9d70e94457b2d87d3) — 455 domains, 99% still online (450), first seen 16 August 2026, active today.

Lapsed small-business domains (mostly .de and .com) and drop-caught names sit on a parking feed (parklogic.com); visitors are sold through the rtmark.net ad redirect hop and wy903/fhvfd redirectors to rotating batch-registered .xyz landers (cececoteco, actionn, linkbrisora, zeroazucar, reflecttive, lexmann, routeengine and others; Namecheap, all on 162.19.234.204). The landers serve a fake "Secure File Download / Virus scan: Safe" page that pushes a download and clicks out to handsomeone.site. A single-use `lp_key` means replays render blank, and the redirect hop rotates — the same parked domain can land on a gambling affiliate on rescan. Entry-domain owners and the parking provider are abused channels, not the operator.

## 📊 By the numbers (last 24h)

- **70** campaigns with activity
- **5,807** new malicious domains observed
- **496** domains went offline
- **8,817** infrastructure changes (IP / ASN / cert)
- **4,434** new page-title lures
- **200** emerging clusters live on the radar

## 🔍 What moved today

🔺 **Fastest-growing** — [Rolling sqllq.com subdomain phishing](https://intel.webamon.com/campaigns/2f41c3bbec077af4f1c44fff61a425759f949713) added 3,793 new domains — active registration and rotation in progress.

🔻 **Takedowns** — 178 domains in the [Brazilian 'Plataforma Oficial' Betting Kit Family](https://intel.webamon.com/campaigns/f04cc4c7e2513dcd0015e26eea0755ea908f3aab) now resolve NXDOMAIN — takedowns/expiry confirmed by double-checked DNS.

🔁 **Infra rotation** — [Brazilian Casino Network (0007bet / 001bet / 001win / aavip)](https://intel.webamon.com/campaigns/0899610610c7f95d7b22ee8339b585b573f7a1b2) moved onto 4,516 new IPs, and [Brazilian Online Casino Doorway Network (Cassino Online Brasil, 944bet / 001WIN / 0007bet)](https://intel.webamon.com/campaigns/b78ce38e9f9e53ef933db4c098dc27ef239353a6) onto 956 — refresh blocklists.

🎭 **Lure refresh** — the same [Brazilian Casino Network](https://intel.webamon.com/campaigns/0899610610c7f95d7b22ee8339b585b573f7a1b2) deployed 1,197 new page titles — content templates are being rotated.

## 🎯 Campaigns worth a look

**[Fake CAPTCHA Gate Network (Verifying you are human)](https://intel.webamon.com/campaigns/aa0b592f46ffd72770beb082f8234379602ced70)** — 520 new domains this window across a 39,160-domain estate at 99% online, with only 16 infra changes: growth by registration, not re-hosting.

**[china k8 phishing portal](https://intel.webamon.com/campaigns/f8baac9d9fa365f2adf7414919aa45f6f37a0450)** — 67 new domains and 1,006 infrastructure changes across 55,612 domains.

## 📡 On the radar — emerging clusters

 200 clusters are live — unattributed infrastructure large enough to promote to tracked campaigns. Sharpest 24h growth:

    ns_set cluster — 9,936 domains, +441 in a day (1024pcb[.]com)
    ns_set cluster — 9,897 domains, +255 (01801[.]com)
    header_order cluster — 9,857 domains, +189 (023255[.]com)
    dom cluster — 9,919 domains, +61 (18-10[.]ch)
    dom_structure cluster — 9,892 domains, +46 (39V.COM)

See the full brief and every tracked campaign live in the Webamon console → intel.webamon.com/campaigns

Full Pdf Brief is available daily from 12:00UTC on our DTB Github Repo → https://github.com/webamon-org/Daily-Threat-Brief

---

*Generated from Webamon campaign intelligence · TLP:CLEAR · Full daily brief and live feeds at [intel.webamon.com](https://intel.webamon.com)*
