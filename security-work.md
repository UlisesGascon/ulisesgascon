[Ulises Gascón](./README.md) / Security Work

# Security Work

When a vulnerability hits a package with 100M+ weekly downloads, someone needs to assess it, coordinate the fix, and ship a patch. Quickly and responsibly. That's the work. I serve as primary coordinator of the [OpenJS Foundation CNA](https://openjsf.org/blog/openjs-foundation-cna), I have authored threat models and incident response plans for Node.js, Express, Lodash, and Webpack, and I am credited on dozens of security advisories across the npm ecosystem. Most of this is volunteer work. Initiatives like [Alpha-Omega](https://alpha-omega.dev/) and the [Sovereign Tech Fund](https://openjsf.org/blog/sta-supports-lodash) have provided critical support at key moments, but funding is temporary. The work isn't.

## 🛡️ Vulnerability Response

I write fixes, review patches, and coordinate disclosure for some of the [most depended-on packages in the npm ecosystem](./npm-ecosystem-impact.md).

<!-- PACKAGE_VISUAL:START -->
**multer** (7) · **undici** (6) · **middie** (3) · **fastify** (3) · **lodash** (3) · **path-to-regexp** (3) · **fastify-static** (2) · **fastify-express** (2) · **body-parser** (2) · **express** (2) · **fastify-reply-from** (1) · **on-headers** (1) · **basic-auth-connect** (1) · **send** (1) · **serve-static** (1)

<!-- PACKAGE_VISUAL:END -->

<!-- ROLE_BREAKDOWN:START -->
| Role | Count |
|------|-------|
| Remediation Reviewer | 23 |
| Remediation Developer | 11 |
| Analyst | 3 |
| Coordinator | 1 |

<!-- ROLE_BREAKDOWN:END -->

<details>
<summary>Full advisory details by package</summary>

<!-- ADVISORIES_BY_PACKAGE:START -->
<details>
<summary><strong>multer</strong> — 7 advisories (Express.js file upload middleware)</summary>

| CVE | Severity | My Role |
|-----|----------|--------|
| [CVE-2026-3520](https://github.com/advisories/GHSA-5528-5vmv-3xc2) | High | Remediation Reviewer |
| [CVE-2026-3304](https://github.com/advisories/GHSA-xf7r-hgr6-v32p) | High | Remediation Reviewer |
| [CVE-2026-2359](https://github.com/advisories/GHSA-v52c-386h-88mc) | High | Remediation Reviewer |
| [CVE-2025-7338](https://github.com/advisories/GHSA-fjgf-rc76-4x9p) | High | Analyst |
| [CVE-2025-48997](https://github.com/advisories/GHSA-g5hg-p3ph-g8qg) | High | Remediation Reviewer |
| [CVE-2025-47944](https://github.com/advisories/GHSA-4pg4-qvpc-4q3h) | High | Remediation Reviewer |
| [CVE-2025-47935](https://github.com/advisories/GHSA-44fp-w29j-9vj5) | High | Coordinator |

</details>

<details>
<summary><strong>undici</strong> — 6 advisories (Node.js built-in HTTP client)</summary>

| CVE | Severity | My Role |
|-----|----------|--------|
| [CVE-2026-1526](https://github.com/advisories/GHSA-vrm6-8vpv-qv8q) | High | Remediation Reviewer |
| [CVE-2026-2229](https://github.com/advisories/GHSA-v9p9-hfj2-hcw8) | High | Remediation Reviewer |
| [CVE-2026-1528](https://github.com/advisories/GHSA-f269-vfmq-vjvj) | High | Remediation Developer |
| [CVE-2026-1527](https://github.com/advisories/GHSA-4992-7rv2-5pvq) | Moderate | Remediation Developer |
| [CVE-2026-2581](https://github.com/advisories/GHSA-phc3-fgpg-7m6h) | Moderate | Remediation Reviewer |
| [CVE-2026-1525](https://github.com/advisories/GHSA-2mjp-6q6p-2qxm) | Moderate | Remediation Reviewer |

</details>

<details>
<summary><strong>middie</strong> — 3 advisories (Fastify middleware engine)</summary>

| CVE | Severity | My Role |
|-----|----------|--------|
| [CVE-2026-33804](https://github.com/advisories/GHSA-v9ww-2j6r-98q6) | High | Remediation Reviewer |
| [CVE-2026-2880](https://github.com/advisories/GHSA-8p85-9qpw-fwgw) | High | Remediation Developer |
| [CVE-2026-6270](https://github.com/advisories/GHSA-72c6-fx6q-fr5w) | Critical | Remediation Developer |

</details>

<details>
<summary><strong>fastify</strong> — 3 advisories (Web framework for Node.js)</summary>

| CVE | Severity | My Role |
|-----|----------|--------|
| [CVE-2026-33806](https://github.com/advisories/GHSA-247c-9743-5963) | High | Remediation Reviewer |
| [CVE-2026-3635](https://github.com/advisories/GHSA-444r-cwp2-x5xf) | Moderate | Remediation Reviewer |
| [CVE-2026-3419](https://github.com/advisories/GHSA-573f-x89g-hqp9) | Moderate | Remediation Reviewer |

</details>

<details>
<summary><strong>lodash</strong> — 3 advisories (JavaScript utility library)</summary>

| CVE | Severity | My Role |
|-----|----------|--------|
| [CVE-2026-4800](https://github.com/advisories/GHSA-r5fr-rjxr-66jc) | High | Remediation Developer |
| [CVE-2026-2950](https://github.com/advisories/GHSA-f23m-r3pf-42rh) | Moderate | Remediation Reviewer |
| [CVE-2025-13465](https://github.com/advisories/GHSA-xxjr-mmjv-4gpg) | Moderate | Remediation Developer |

</details>

<details>
<summary><strong>path-to-regexp</strong> — 3 advisories</summary>

| CVE | Severity | My Role |
|-----|----------|--------|
| [CVE-2026-4926](https://github.com/advisories/GHSA-j3q9-mxjg-w52f) | High | Remediation Reviewer |
| [CVE-2026-4867](https://github.com/advisories/GHSA-37ch-88jc-xwx2) | High | Remediation Reviewer |
| [CVE-2026-4923](https://github.com/advisories/GHSA-27v5-c462-wpq7) | Moderate | Remediation Reviewer |

</details>

<details>
<summary><strong>fastify-static</strong> — 2 advisories</summary>

| CVE | Severity | My Role |
|-----|----------|--------|
| [CVE-2026-6410](https://github.com/advisories/GHSA-pr96-94w5-mx2h) | Moderate | Remediation Reviewer |
| [CVE-2026-6414](https://github.com/advisories/GHSA-x428-ghpx-8j92) | Moderate | Remediation Reviewer |

</details>

<details>
<summary><strong>fastify-express</strong> — 2 advisories</summary>

| CVE | Severity | My Role |
|-----|----------|--------|
| [CVE-2026-33808](https://github.com/advisories/GHSA-6hw5-45gm-fj88) | Critical | Remediation Reviewer |
| [CVE-2026-33807](https://github.com/advisories/GHSA-hrwm-hgmj-7p9c) | Critical | Remediation Reviewer |

</details>

<details>
<summary><strong>body-parser</strong> — 2 advisories (Express.js request body parsing)</summary>

| CVE | Severity | My Role |
|-----|----------|--------|
| [CVE-2024-45590](https://github.com/advisories/GHSA-qwcr-r2fm-qrc7) | High | Remediation Developer |
| [CVE-2025-13466](https://github.com/advisories/GHSA-wqch-xfxh-vrr4) | Moderate | Remediation Reviewer |

</details>

<details>
<summary><strong>express</strong> — 2 advisories (Web framework for Node.js)</summary>

| CVE | Severity | My Role |
|-----|----------|--------|
| [CVE-2024-29041](https://github.com/advisories/GHSA-rv95-896h-c2vc) | Moderate | Analyst |
| [CVE-2024-43796](https://github.com/advisories/GHSA-qw6h-vgh9-j6wx) | Low | Remediation Developer |

</details>

<details>
<summary><strong>Other packages</strong> — 5 advisories (fastify-reply-from, on-headers, basic-auth-connect, send, serve-static)</summary>

| CVE | Package | Severity | My Role |
|-----|---------|----------|--------|
| [CVE-2024-47178](https://github.com/advisories/GHSA-7p89-p6hx-q4fw) | basic-auth-connect | High | Remediation Developer |
| [CVE-2025-7339](https://github.com/advisories/GHSA-76c9-3jph-rj3q) | on-headers | Low | Analyst |
| [CVE-2024-43799](https://github.com/advisories/GHSA-m6fv-jmcg-4jfg) | send | Low | Remediation Developer |
| [CVE-2024-43800](https://github.com/advisories/GHSA-cm22-4g7w-348p) | serve-static | Low | Remediation Developer |
| [CVE-2026-33805](https://github.com/advisories/GHSA-gwhp-pf74-vj37) | fastify-reply-from | Critical | Remediation Reviewer |

</details>


<!-- ADVISORIES_BY_PACKAGE:END -->

</details>

*For the full and up-to-date list, see [my credited advisories on GitHub](https://github.com/advisories?query=credit%3AUlisesGascon).*

## 📋 Security Governance

Formal roles across the ecosystem:

- Primary Coordinator of [the OpenJS Foundation CNA (CVE Numbering Authority)](https://cna.openjsf.org/) since 2025
- Member of [the Webpack Security triage team](https://github.com/webpack/security-wg/pull/17) since 2026
- Member of [the Webpack Security WG](https://github.com/webpack/security-wg/pull/1) since 2025
- Participant of [the TC39 TG3 (Security WG)](https://github.com/tc39/tg3) since 2024
- Member of [the OpenJS Security Working Group](https://github.com/openjs-foundation/security-collab-space/pull/202) since 2024
- Member of [the Express.js Technical Committee](https://github.com/expressjs/expressjs.com/pull/1460) since 2024
- Member of [the Node.js Security WG](https://speaking.ulisesgascon.com/nodejs-security-working-group) since 2022
- [OWASP (The Open Web Application Security Project) Member](https://owasp.org/) since 2022
- Maintainer of [the OSSF Scorecard Monitor](https://github.com/ossf/scorecard-monitor/issues/79) and [the OSSF Scorecard Visualizer](https://github.com/ossf/scorecard-visualizer) since 2023
- Creator of [the Express.js Security Working Group](https://github.com/expressjs/discussions/issues/165) and [the security triage team](https://github.com/expressjs/security-wg#security-triage-team)
- Member of [the Express.js Triage Team](https://github.com/expressjs/express/pull/4175) since 2020

**Recognition:** [GitHub Secure Open Source Fund](https://github.com/github/secure-open-source-fund) participant · [Snyk Ambassador](https://snyk.io/snyk-ambassadors/) (2023-2026) · [JavaScriptLandia Awards, Leading by Example](https://openjsf.org/blog/2024-javascriptlandia-community-award-categories-a) (2024)

## 🏗️ Building Security From the Ground Up

**Threat Models**, defining what is and isn't a vulnerability:

- [Node.js Official Threat Model](https://github.com/nodejs/node/blob/main/SECURITY.md)
- [Node.js Contributor Threat Model](https://github.com/nodejs/TSC/issues/1618)
- [Node.js Maintainers Threat Model](https://github.com/nodejs/security-wg/blob/main/MAINTAINERS_THREAT_MODEL.md)
- [Express.js Threat Model](https://github.com/expressjs/security-wg/blob/main/docs/ThreatModel.md)
- [Lodash Threat Model](https://github.com/lodash/lodash/pull/6026)
- [Webpack Threat Model](https://github.com/webpack/security-wg/pull/9)

**Incident Response Plans**, what happens when a vulnerability is confirmed:

- [OpenJS Foundation Incident Response Plan](https://github.com/openjs-foundation/security-collab-space/pull/289)
- [Express.js Incident Response Plan](https://github.com/expressjs/security-wg/blob/main/docs/incident_response_plan.md)
- [Lodash Incident Response Plan](https://github.com/lodash/lodash/pull/6028)

**Guides & Standards:**

- [Node.js Security Best Practices](https://nodejs.org/en/docs/guides/security/)
- [GitHub's Open Source Guide, Security Best Practices](https://opensource.guide/security-best-practices-for-your-project/). [Extended](https://github.com/github/opensource.guide/pull/3465) with information on licenses, vulnerability reporting, threat models, and IRPs.
- [Publishing More Securely on npm](https://openjsf.org/blog/publishing-securely-on-npm)

**Tooling:**

- [OpenJS Foundation Command Center](https://github.com/openjs-foundation/command-center). Security and compliance dashboard for OpenJS Foundation projects.
- [OpenPathfinder](https://openpathfinder.com/). Security and health monitoring platform for open source projects.
- [OSSF Scorecard Monitor](https://github.com/ossf/scorecard-monitor). Tracks OpenSSF Scorecard results over time.
- [OSSF Scorecard Visualizer](https://github.com/ossf/scorecard-visualizer). Visual dashboard for OpenSSF Scorecard data.

**Initiatives:**

- Coordinated [the Express.js security audit with OSTIF](https://expressjs.com/2024/10/22/security-audit-milestone-achievement.html)
- Helped adopt [Never-Ending Support (NES) with HeroDevs for Express](https://openjsf.org/blog/at-the-openjs-foundation-were-excited-to-announce-)
- Led adoption of [the OpenSSF Scorecard](https://github.com/expressjs/discussions/issues/162) for Express.js and [Node.js](https://github.com/nodejs/security-wg/issues/851#issuecomment-1432257748)
- Achieved [OpenSSF CII Best Practices](https://github.com/nodejs/security-wg/issues/953) [Silver](https://github.com/nodejs/security-wg/pull/955) and [Gold](https://github.com/nodejs/security-wg/pull/956) for Node.js
- Driving the [Express.js bug bounty program](https://github.com/expressjs/security-wg/pull/90) on YesWeHack
- Kicked off the [Webpack Security WG](https://github.com/webpack/security-wg/pull/1)
- Contributed to the [EU Commission consultation on Cybersecurity Act revision](https://digital-strategy.ec.europa.eu/en/consultations/public-consultation-eu-cybersecurity-act-revision) via the ORC WG

## 🎙️ Security Talks

[What Comes After Chaos?](https://www.youtube.com/watch?v=NHsIxEy0_Qw) · [Making Sense of Threat Models](https://gitnation.com/contents/what-is-a-vulnerability-and-whats-not-making-sense-of-nodejs-and-express-threat-models) · [Strengthening the Supply Chain](https://www.youtube.com/watch?v=IaNE2LRuGQA) · [Node4Hackers](https://speaking.ulisesgascon.com/hack-madrid-27-node4hackers) · [Tu Servidor en NodeJS es vulnerable?](https://speaking.ulisesgascon.com/jsday-canarias-2019-servidor-nodejs-vulnerable) · [Personal Privacy 101](https://speaking.ulisesgascon.com/techparty19-personal-privacy-101) · [TOR para Developers 101](https://speaking.ulisesgascon.com/morcillaconf19-tor-para-developers) · [**All talks**](https://speaking.ulisesgascon.com/)

**JavaScript Security Snapshot** (video series with the OpenJS Foundation, Alpha-Omega, and NodeSource): [Incident Response Plan](https://www.youtube.com/shorts/mqPlCdMD8LY) · [How Express Handles Security](https://www.youtube.com/shorts/i_JcfmXgQ4w) · [How to Get Involved](https://www.youtube.com/shorts/4h7P71n1sjw) · [What is even a CVE?](https://www.youtube.com/shorts/0VGUfoxF8aQ)

## 📰 Security Blog Posts & Publications

### Vulnerability Analysis & Response

- [What CVE-2025-13465 Teaches Us About Prototype Pollution in JavaScript](https://orbitant.com/en/prototype-pollution-javascript-cve-2025-13465/) (Jan 2026)
- [Lodash Rolls Out Major Security Overhaul](https://openjsf.org/blog/lodash-security-overhaul) (Jan 2026)
- [Critical React Server Components Vulnerability: How We Responded at Orbitant](https://orbitant.com/en/critical-react-server-components-vulnerability/) (Dec 2025)
- [Node.js release fixes a critical HTTP security vulnerability](https://snyk.io/blog/node-js-release-fixes-a-critical-http-security-vulnerability/) (Feb 2020)

### Security Processes & Governance

- [OpenJS Foundation Security Program: Annual Report 2025](https://openjsf.org/blog/openjs-security-annual-report-2025) (2025)
- [Strengthening Yeoman: Our 2025 Security Overhaul](https://yeoman.io/blog/security-overhaul-2025) (Nov 2025)
- [How Express.js Rebuilt Its Vulnerability Reporting Process](https://expressjs.com/2025/06/05/vulnerability-reporting-process-overhaul.html) (Jun 2025)
- [Express.js Security Audit: A Milestone Achievement](https://expressjs.com/2024/10/22/security-audit-milestone-achievement.html) (Oct 2024)

### Security Education

- [Decoding CVEs: A practical guide to assessing and mitigating security risks](https://snyk.io/articles/decoding-cves-practical-guide-assessing-mitigating-security-risks/) (Oct 2024)
- [You should use the OpenSSF Scorecard](https://blog.ulisesgascon.com/openssf-scorecard-in-nodejs) (Jan 2023)
- [Safely store secrets in Git using Blackbox](https://blog.ulisesgascon.com/safely-store-secrets-in-git-using-blackbox) (Feb 2023)
- [Docker Seguro](https://dockerseguro.ulisesgascon.com/) (2022)
- [Cybersecurity Handbook](https://github.com/guidesmiths/cybersecurity-handbook) (2020)
- [What is a backdoor? Let's build one with Node.js](https://snyk.io/blog/what-is-a-backdoor/) (Mar 2020)

I have also authored a series of technical deep-dives on web security topics on [my blog](https://blog.ulisesgascon.com/).

## 💚 Why This Matters

Open source security doesn't happen by inertia. The gap between "widely depended on" and "actively secured" is where I spend my time.

[🔙 **Back to profile**](./README.md) · [**Become a sponsor**](https://github.com/sponsors/UlisesGascon) · [**Freelance & consulting**](./sponsors.md#working-together)
