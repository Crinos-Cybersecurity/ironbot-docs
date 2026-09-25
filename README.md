# IronBOT

**Find the gaps before attackers do.**

Autonomous AI-powered pentesting — continuous reconnaissance, real exploitation, and validated findings for web apps, APIs, and code repositories.

[Website](https://ironbot.io) · [Run a pentest](https://app.ironbot.io) · [Documentation](docs/) · [Book a call](https://ironbot.io/#contact)

---

> **About this repository** — This is the public home for IronBOT's documentation and landing material. The IronBOT product source code is proprietary and not published here.

## What is IronBOT?

IronBOT is an autonomous AI pentest agent. It combines automated reconnaissance, active exploitation, and real vulnerability validation — always within the scope you authorize, following industry-recognized methodologies: **OWASP Top 10**, **MITRE ATT&CK**, and **SANS Top 25**.

Where traditional scanners return generic noise, IronBOT's specialized sub-agents (reconnaissance, exploitation, post-exploitation) work together, chain vulnerabilities, and prove real impact — not just vague findings.

## Who it's for

| Audience | The problem | What IronBOT changes |
| --- | --- | --- |
| **Vibe coders** | Idea to production in a weekend; security never keeps that pace. | Test your app the way a professional pentester would — without writing a line of security configuration. |
| **Tech leads & reviewers** | Writing code became cheap. Making every pull request secure didn't. | Code arrives already tested, with risks mapped and fixes suggested. The security bottleneck leaves your queue. |
| **Software maintainers** | AI sped up how fast your product changes; the yearly pentest didn't. | Every meaningful change is continuously validated — no waiting for the next cycle. |
| **Offensive security pros** | Client assurance work eats your billable time. | Automate security assurance for your clients' code and web apps, and focus on what an AI can't do in your place. |

## How it works

1. **Register your target securely** — define what should be tested: a web app, an API, or a GitHub code repository.
2. **Automated reconnaissance** — IronBOT maps the attack surface: subdomains, endpoints, exposed technologies, and entry points, cross-referencing source code with the live application.
3. **Exploitation and real validation** — each sub-agent specializes in one job, chaining vulnerabilities to prove real impact.
4. **Evidence and remediation** — every confirmed vulnerability ships with a severity rating, reproducible proof of exploitation, and a remediation recommendation (including ready-to-use LLM prompts).

## What IronBOT can find

- Access control flaws, such as IDOR and privilege escalation
- SQL, NoSQL, OS command, and SSTI injection
- Server-side issues: SSRF, XXE, insecure deserialization, and RCE
- Client-side flaws: XSS, CSRF, and prototype pollution
- Business logic flaws, such as race conditions and payment manipulation
- Authentication and session issues, including JWT attacks
- API vulnerabilities: broken authentication, mass assignment, and rate-limit bypass
- Insecure infrastructure configurations exposed during testing

See [docs/vulnerability-coverage.md](docs/vulnerability-coverage.md) for details.

## Plans

| Plan | Starting at | Best for |
| --- | --- | --- |
| **One-Shot Pentest** | $50 | A focused, single-target test with a complete report. No subscription. |
| **IronBOT Enterprise (PTaaS)** | Talk to us | Continuous security embedded in your development flow: recurring pentests, per-PR checks, API-delivered reports. |

Full breakdown in [docs/plans.md](docs/plans.md).

## Getting started

1. Go to [app.ironbot.io](https://app.ironbot.io)
2. Register a target (web app, API, or code repository)
3. Approve the scope and follow the test as it runs
4. Download the report with evidence and remediation steps

More in [docs/getting-started.md](docs/getting-started.md).

## Security

Found a vulnerability in IronBOT itself? We want to know. Please read [SECURITY.md](SECURITY.md) before reporting.

## Contact

- Website & contact form: [ironbot.io](https://ironbot.io/#contact)
- Enterprise: [Book 20 minutes with a specialist](https://ironbot.io/#contact)
- Coverage: Brazil · Global remote

---

© Crinos Cybersecurity. IronBOT is a Crinos Cybersecurity product. All rights reserved — see [LICENSE](LICENSE).
