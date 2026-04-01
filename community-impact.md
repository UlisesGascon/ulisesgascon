[Ulises Gascón](./README.md) / Community Impact

# Community Impact

Code is the easy part. The hard part is everything around it: governance, security, releases, mentoring, and the slow work of turning fragile projects into sustainable ones. Most of this happens in working groups and committees that few people outside the ecosystem ever see. I've been deeply involved in this world for over a decade. Along the way I've also written [books](https://www.amazon.com/dp/1803245174), spoken at [dozens of conferences](https://speaking.ulisesgascon.com/), and spent years mentoring new developers into open source. This is what that looks like.

## Express.js

Express is an ecosystem of 60+ packages spanning three GitHub organizations, powering millions of servers. I joined the triage team in 2020, but the real turning point came in 2024 when together with [Wes Todd](https://github.com/wesleytodd) and [Jean Burellier](https://github.com/sheplu) we put together the [Express Forward Plan](https://github.com/expressjs/discussions/issues/160). The project had been in maintenance mode for years. Express 5 had been "almost ready" for close to a decade. We needed a concrete path forward: reformed governance, new Technical Committee seats, a release strategy, and a clear roadmap through Express 5, 6, and 7.

That work led to [Express 5.0](https://expressjs.com/2024/10/15/v5-release.html) shipping after a decade of waiting, [Express 5.1](https://expressjs.com/2025/03/31/v5-1-latest-release.html) becoming the default on npm with the first-ever LTS plan, [Impact Project status](https://github.com/openjs-foundation/cross-project-council/issues/1378) at the OpenJS Foundation, a full [security audit coordinated with OSTIF](https://expressjs.com/2024/10/22/security-audit-milestone-achievement.html), and a [Security Working Group](https://github.com/expressjs/discussions/issues/165) with a dedicated [triage team](https://github.com/expressjs/security-wg#security-triage-team) and a [bug bounty program](https://github.com/expressjs/security-wg/pull/90). The Express security work was part of the [GitHub Secure Open Source Fund](https://github.com/github/secure-open-source-fund), a program that collectively disclosed 50+ CVEs and remediated 1,100+ vulnerabilities across 71 projects.

Today I serve as repo captain for [28+ libraries](https://github.com/expressjs/discussions/blob/master/docs/contributing/captains_and_committers.md) across the Express, jshttp, and pillarjs organizations, plus the triage team, security WG, and archived packages. We also [unified the security policy](https://expressjs.com/2025/06/05/vulnerability-reporting-process-overhaul.html) across all repositories, [deprecated legacy packages](https://expressjs.com/2025/05/16/express-cleanup-legacy-packages.html) to reduce attack surface, established the [Express Performance WG](https://github.com/expressjs/perf-wg), and adopted [Never-Ending Support (NES) with HeroDevs](https://openjsf.org/blog/at-the-openjs-foundation-were-excited-to-announce-) for enterprise-grade EOL support.

> "This mattered because it rebuilt something more important than code: trust." — [Source](https://blog.ulisesgascon.com/open-source-doesnt-fail-because-of-code)

**Learn more:** [Open Source Doesn't Fail Because of Code](https://blog.ulisesgascon.com/open-source-doesnt-fail-because-of-code), [A New Chapter for Express.js](https://expressjs.com/2025/01/09/rewind-2024-triumphs-and-2025-vision.html), and [What Comes After Chaos?](https://www.youtube.com/watch?v=NHsIxEy0_Qw) (talk)

<details>
<summary>Formal roles</summary>

- Member of [the Express.js Technical Committee](https://github.com/expressjs/expressjs.com/pull/1460) since 2024
- Repo captain for [28+ libraries](https://github.com/expressjs/discussions/blob/master/docs/contributing/captains_and_committers.md) across expressjs, jshttp, and pillarjs since 2024
- Founding member of [the Express.js Security Working Group](https://github.com/expressjs/discussions/issues/165) since 2024
- Founding member of [the Express.js Security Triage Team](https://github.com/expressjs/security-wg#security-triage-team) since 2024
- Member of [the Express.js Triage Team](https://github.com/expressjs/express/pull/4175) since 2020

</details>

## Lodash

Lodash is the [#1 most directly used version-agnostic npm package in production](https://www.linuxfoundation.org/research/census-ii-of-free-and-open-source-software-application-libraries). [2.4 billion weekly downloads](https://openjsf.org/blog/sta-supports-lodash). [9.3 million websites](https://trends.builtwith.com/websitelist/lodash) use it. One-third of the top 10,000 sites rely on it. And for years, one person carried the entire weight of maintaining it.

The problem was never commitment. It was structure. Hundreds of variant packages, a fragmented CI system, and a flood of invalid vulnerability reports that drained the maintainer's time. The community kept asking for Lodash 5 while the project was still trying to survive Lodash 4 without collapsing under its own operational weight.

We applied what we learned from Express. A [Technical Steering Committee](https://github.com/lodash/lodash/pull/6035) to distribute decisions. A [Threat Model](https://github.com/lodash/lodash/pull/6026) to define what counts as a vulnerability and what doesn't. An [Incident Response Plan](https://github.com/lodash/lodash/pull/6028) so security disclosures follow a process instead of panic. A [major security overhaul](https://openjsf.org/blog/lodash-security-overhaul) to clear the backlog and reset the project's security posture. Rebuilding CI forced us to make many things explicit that had previously lived only in people's heads: supported environments, security boundaries, release criteria.

From the Lodash creator, [John-David Dalton](https://github.com/jdalton):

> "The help around the project tech-debt... and help around process has been critical to achieve movement." — [Source](https://socket.dev/blog/inside-lodash-security-reset)

**Learn more:** [The Future of Lodash](https://blog.ulisesgascon.com/the-future-of-lodash), [Inside Lodash's Security Reset](https://socket.dev/blog/inside-lodash-security-reset), and [Lodash Rolls Out Major Security Overhaul](https://openjsf.org/blog/lodash-security-overhaul)

<details>
<summary>Formal roles</summary>

- Member of [the Lodash Technical Steering Committee (TSC)](https://github.com/lodash/lodash/pull/6035) since 2025

</details>

## Node.js

Node.js runs on hundreds of millions of machines. My involvement has evolved over the years depending on where the project needed help most: releases, build infrastructure, security, and performance. I have [hosted dozens of meetings](https://www.youtube.com/@nodejs-foundation) across these working groups.

**Releases**

I am one of a [small group of people](https://github.com/nodejs/node#release-keys) authorized to build, sign, and ship Node.js releases. Each release reaches hundreds of millions of environments.

[Node.js Core Collaborator](https://github.com/nodejs/node/pull/51991) since 2024. [Member of the Release WG](https://github.com/nodejs/Release/issues/892) since 2023. I have authored releases including [v20.6.0](https://nodejs.org/en/blog/release/v20.6.0), [v20.7.0](https://nodejs.org/en/blog/release/v20.7.0), [v20.11.0](https://nodejs.org/en/blog/release/v20.11.0), [v20.19.1](https://nodejs.org/en/blog/release/v20.19.1), and [v22.15.0](https://nodejs.org/en/blog/release/v22.15.0). I also participated in the initiative to [evolve the Node.js release schedule](https://github.com/nodejs/nodejs.org/pull/8631), transitioning from two major releases per year to one annual release starting with Node.js 27.x. Beyond releases, I [author commits](https://github.com/search?q=org%3Anodejs+author%3AUlisesGascon&type=commits), [review and merge contributions](https://github.com/nodejs/node/pulls?q=is%3Apr+reviewed-by%3AUlisesGascon), and help onboard new collaborators.

**Build infrastructure**

The [Node.js Build Team](https://github.com/nodejs/build) manages the CI/CD infrastructure that tests Node.js across dozens of OS and architecture combinations. When machines go down, someone brings them back. When Apple changes their signing tools, someone migrates.

Some of the work I've contributed: recovering [MacStadium](https://github.com/nodejs/build/issues/3179) and [Windows](https://github.com/nodejs/build/issues/3435) machines after failures, transitioning to [notarytool for macOS signing](https://github.com/nodejs/build/issues/3385), introducing [Terraform for Cloudflare](https://github.com/nodejs/build/issues/3270), moving to [ephemeral machines with Packer](https://github.com/nodejs/build/issues/3686#issuecomment-2278119351), and building the [distribution system monitoring](https://github.com/UlisesGascon/nodejs-distribution-system-monitoring) and [R2 migration monitoring](https://github.com/nodejs/build/issues/3469) tools. [Jenkins admin](https://github.com/nodejs/build/pull/3328) since 2023.

**Security posture**

[Member of the Node.js Security WG](https://twitter.com/kom_256/status/1529911534960398337) since 2022. I co-authored the [Official Threat Model](https://github.com/nodejs/node/pull/45223), the [Contributor Threat Model](https://github.com/nodejs/TSC/issues/1618), and the [Security Best Practices](https://github.com/nodejs/nodejs.org/pull/4896).

Adopting the [OpenSSF Scorecard](https://github.com/nodejs/security-wg/issues/851) across the Node.js organization was one of the harder initiatives. No existing tooling could track scorecard results across dozens of repositories over time, so we built it. The [OpenSSF Scorecard Monitor](https://github.com/ossf/scorecard-monitor) and the [OpenSSF Scorecard Visualizer](https://github.com/ossf/scorecard-visualizer) started as solutions for Node.js and ended up becoming official OSSF tools. We also helped achieve [CII Best Practices Gold](https://github.com/nodejs/security-wg/pull/956) for Node.js. Full details in [Security Work](./security-work.md).

**Shaping the future**

Founding member of [the Performance Team](https://github.com/nodejs/performance/pull/15) since 2022. Participant of [the Next 10 Team](https://github.com/nodejs/next-10), where I helped to kicked off [the security model initiative](https://www.youtube.com/watch?v=MqOdY58EW7M&t=4866s) that eventually led to [the Permission Model API](https://nodejs.org/api/permissions.html). Creator of the [Node.js News Feeder](https://github.com/nodejs/nodejs-news-feeder).

**Learn more:** [Evolving the Node.js Release Schedule](https://nodejs.org/en/blog/announcements/evolving-the-nodejs-release-schedule), [You should use the OpenSSF Scorecard](https://blog.ulisesgascon.com/openssf-scorecard-in-nodejs), [How does the Official Node.js News Feeder work?](https://dev.to/ulisesgascon/how-does-the-official-nodejs-news-feeder-work-2fa6)

<details>
<summary>Formal roles</summary>

- [Node.js Core Collaborator](https://github.com/nodejs/node/pull/51991) since 2024
- [Node.js Releaser](https://github.com/nodejs/Release/issues/892) since 2023
- Member of [the Node.js Build Team](https://github.com/nodejs/build/issues/3068) since 2022
- Member of [the Node.js Security WG](https://speaking.ulisesgascon.com/nodejs-security-working-group) since 2022
- Founding member of [the Node.js Performance Team](https://github.com/nodejs/performance/pull/15) since 2022

</details>

## OpenJS Foundation

The [OpenJS Foundation](https://openjsf.org/) hosts projects like Node.js, jQuery, webpack, Electron, and Express. I serve on its governance body and coordinate security across [many of them](https://cna.openjsf.org/).

[Voting Member of the Cross Project Council](https://github.com/openjs-foundation/cross-project-council/pull/1257) since 2024. I serve as primary coordinator of [the OpenJS Foundation CNA](https://cna.openjsf.org/). Creator of the [OpenJS Foundation Command Center](https://github.com/openjs-foundation/command-center) for security and compliance monitoring. Author of the [OpenJS Foundation Incident Response Plan](https://github.com/openjs-foundation/security-collab-space/pull/289).

As part of the [OpenJS Security Working Group](https://github.com/openjs-foundation/security-collab-space), I was in the emergency security meetings coordinating the response when the [npm Shai-Hulud supply-chain attack](https://github.com/openjs-foundation/security-collab-space/pull/296) and the [axios compromise](https://github.com/axios/axios/issues/10636) hit.

I also led the creation of a [sustainability working group](https://github.com/openjs-foundation/cross-project-council/issues/1357), co-authored research on [secure npm publishing](https://openjsf.org/blog/publishing-securely-on-npm), contributed to the [EU Commission consultation on the Cybersecurity Act](https://github.com/orcwg/orcwg/pull/127) via the ORC WG, and participated in the [OpenJS AI Working Group](https://github.com/openjs-foundation/ai-collab-space/commit/9dc22c3100635b5dce3f6e08eaa33333a5d5fb5a). In 2024, I received the [JavaScriptLandia Leading by Example award](https://openjsf.org/blog/2024-javascriptlandia-community-award-categories-a) from the OpenJS Foundation.

**Learn more:** [The OpenJS Foundation is now a CNA](https://openjsf.org/blog/openjs-foundation-cna), [OpenJS Foundation Security Program: Annual Report 2025](https://openjsf.org/blog/openjs-security-annual-report-2025), [Publishing More Securely on npm](https://openjsf.org/blog/publishing-securely-on-npm)

<details>
<summary>Formal roles</summary>

- [Voting Member of the Cross Project Council](https://github.com/openjs-foundation/cross-project-council/pull/1257) since 2024
- Primary Coordinator of [the OpenJS Foundation CNA](https://cna.openjsf.org/) since 2025
- Member of [the OpenJS Security Working Group](https://github.com/openjs-foundation/security-collab-space/pull/202) since 2024
- Member of [the OpenJS AI Working Group](https://github.com/openjs-foundation/ai-collab-space/commit/9dc22c3100635b5dce3f6e08eaa33333a5d5fb5a) since 2025

</details>

## Also involved in

**[TC39](https://github.com/openjs-foundation/standards/pull/305)** — Delegate for the OpenJS Foundation since 2024. TC39 is the standards body behind the JavaScript language. I focus on security through [TG3](https://github.com/tc39/tg3) and help bring ecosystem feedback through the [JS outreach groups](https://speaking.ulisesgascon.com/tc39-js-outreach-groups).

**[Yeoman](https://github.com/yeoman/yeoman.io/pull/793)** — Core Team since 2019 through my [contributions to generator-webapp](https://github.com/yeoman/generator-webapp/commits/main/?author=UlisesGascon). Together with Josh Goldberg, we co-led the [2025 maintenance reboot](https://yeoman.io/blog/maintenance-reboot) and I led the [security overhaul](https://yeoman.io/blog/security-overhaul-2025) across the organization.

**[Webpack](https://github.com/webpack/security-wg/pull/1)** — Kicked off the Security WG in 2025 and authored the [Threat Model](https://github.com/webpack/security-wg/pull/9). Part of the [triage team](https://github.com/webpack/security-wg/pull/17) since 2026.

**[OpenSSF](https://openssf.org/)** — Maintainer of [Scorecard Monitor](https://github.com/ossf/scorecard-monitor) and [Scorecard Visualizer](https://github.com/ossf/scorecard-visualizer), tools that started as solutions for Node.js and became official OpenSSF projects.

**[OWASP](https://owasp.org/)** — Member since 2022 and [NodeGoat contributor](https://github.com/OWASP/NodeGoat/commits?author=UlisesGascon) since 2019.

**[One Beyond](https://onebeyond-maintainers.netlify.app)** (previously Guidesmiths) — Built an Open Source Program Office (OSPO) from scratch as Head of Open Source. I keep maintaining many of the [npm packages](./npm-ecosystem-impact.md) to this day.

**Awards for community contributions:** [JavaScriptLandia, Leading by Example](https://openjsf.org/blog/2024-javascriptlandia-community-award-categories-a) (2024) · [Docker Captain](https://www.docker.com/captains/ulises-gascon/) (since 2023) · [Google Developer Expert](https://developers.google.com/community/experts/directory/profile/profile-ulises-gascon) (since 2019) · [Snyk Ambassador](https://snyk.io/snyk-ambassadors/) (2023-2026) · [Microsoft MVP](https://mvp.microsoft.com/en-us/PublicProfile/5005253) (2023-2025)

<details>
<summary>Formal roles</summary>

- [TC39 Delegate (OpenJS Foundation)](https://github.com/openjs-foundation/standards/pull/305) since 2024
- Participant of [the TC39 TG3 (Security WG)](https://github.com/tc39/tg3) since 2024
- Participant of [the TC39 JS outreach groups](https://speaking.ulisesgascon.com/tc39-js-outreach-groups) since 2022
- Member of [the Yeoman Core Team](https://github.com/yeoman/yeoman.io/pull/793) since 2019
- Maintainer of [the OSSF Scorecard Monitor](https://github.com/ossf/scorecard-monitor) and [the OSSF Scorecard Visualizer](https://github.com/ossf/scorecard-visualizer) since 2023
- Member of [the Webpack Security WG](https://github.com/webpack/security-wg/pull/1) since 2025
- Member of [the Webpack Security triage team](https://github.com/webpack/security-wg/pull/17) since 2026

</details>

## 💚 Why This Matters

Most of what I do doesn't show up in a contribution graph. Mentoring new maintainers. Writing governance documents. Hosting dozens of meetings across working groups. Reviewing security reports at odd hours. Building consensus across organizations that don't always agree. I keep doing it because the ecosystem is worth it.

> "This is slower work. Less visible. Less exciting on social media. But this is what transformation looks like in mature infrastructure." — [Source](https://blog.ulisesgascon.com/open-source-doesnt-fail-because-of-code)

[🔙 **Back to profile**](./README.md) · [**Become a sponsor**](https://github.com/sponsors/UlisesGascon) · [**Freelance & consulting**](./sponsors.md#working-together)
