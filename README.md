### Michael Dagan

Hands-on network and cloud security. I also run my own systems, secured the same way: two cloud servers, a home lab and twelve AI agents that work every day. AWS Certified Solutions Architect - Associate, with six years of technical operations and project management underneath.

**In public here**

- **[protfolio](https://github.com/MikesLabXYZ/protfolio)** holds the application and build steps behind my 422-page AWS and Palo Alto project guide: four AWS accounts behind an on-premises Palo Alto firewall, failed over to a second region in 83 seconds. The `aws-deployment` branch is the tested build the guide follows.

**In private, and why**

Most of what I run lives in private repositories, because it drives live servers or holds personal data. What it does:

- **Twelve AI agents** I designed and run, built with Claude Code. Each has one job, its own repository, rules, decision log and audit. They share one memory of over 2,000 cards, rebuilt every three hours, and guard hooks check every action they take.
- **Two cloud servers at zero cost** on Oracle, behind Cloudflare. Every night they rebuild, scan with Trivy, check nine security layers and restore last night's backup into a scratch database to prove it restores.
- **A nightly GitHub Actions build** of the web server: newest Go, proved against the published release, scanned, dependencies raised when a fix is published.
- **Ace**, the exam system I passed SAA with: no question served until its answer was checked against AWS's own documentation. It deploys itself on a push in 21 seconds.
- **Two machines, one body of work:** my laptop and a home GPU server synced through git every 15 minutes, and every repository backed up here hourly, checked for secrets first.

Write-ups of all of it: **[mdlabs.website/projects](https://mdlabs.website/projects)**
