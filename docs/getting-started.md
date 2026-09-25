# Getting started with IronBOT

IronBOT runs an autonomous pentest against a target you authorize. You don't write security configuration, install an agent, or wait for a scheduled window — you register the target, approve the scope, and follow the test as it runs.

## 1. Create your account

Go to [app.ironbot.io](https://app.ironbot.io) and sign up.

## 2. Register your target

Choose what IronBOT should test:

- **Web application** — a URL you own or are authorized to test
- **API** — an API endpoint within your authorized scope
- **Code repository** — a GitHub repository you control

## 3. Approve the scope

IronBOT proposes the scope it intends to cover. Review and approve it. The agent acts **only** within the scope you authorize — nothing outside it.

> Only test systems you own or have explicit written permission to test. See [SECURITY.md](../SECURITY.md) for our own disclosure policy.

## 4. Follow the test

IronBOT works through four stages:

1. **Reconnaissance** — maps subdomains, endpoints, exposed technologies, and entry points, cross-referencing your source code against the live application.
2. **Exploitation** — specialized sub-agents attempt real exploitation, chaining vulnerabilities together.
3. **Validation** — every finding is validated to confirm real impact, so you get evidence instead of guesswork.
4. **Reporting** — each confirmed vulnerability is documented with a severity rating, reproducible proof, and a remediation recommendation.

## 5. Act on the report

At the end you get a complete report:

- Severity rating per finding
- Reproducible proof of exploitation
- Remediation recommendation, including ready-to-use LLM prompts your team can hand straight to a coding agent

Reports are downloadable, and for Enterprise customers they can also be emailed to stakeholders or delivered via API.

## Next steps

- [Plans](plans.md) — One-Shot vs. Enterprise
- [Vulnerability coverage](vulnerability-coverage.md) — what IronBOT looks for
- [FAQ](faq.md) — common questions
