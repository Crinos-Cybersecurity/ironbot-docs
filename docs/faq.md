# FAQ

## Does IronBOT replace my security team?

No. IronBOT automates reconnaissance, exploitation, and vulnerability validation with the same methodological rigor as a professional pentest — but scope decisions and acting on findings stay with your team. It's built to extend your team's capacity, not replace it.

## Is it just another scanner?

No. Scanners produce candidates; IronBOT validates. Its sub-agents perform real reconnaissance and active exploitation, chaining vulnerabilities together to prove actual impact. Every confirmed finding comes with reproducible evidence, not a generic warning.

## What targets can I test?

Web applications, APIs, and code repositories. For a code repository, IronBOT cross-references the source against the live application to catch issues that neither a static scan nor a black-box scan would find alone.

## Which methodologies does it follow?

OWASP Top 10, MITRE ATT&CK, and SANS Top 25. See [vulnerability-coverage.md](vulnerability-coverage.md).

## What do I get at the end?

A report with, per finding: severity rating, reproducible proof of exploitation, and a remediation recommendation — including ready-to-use LLM prompts your team can hand straight to a coding agent.

## Do I need to be a security expert to use it?

No. If you can describe what you want tested, IronBOT handles the security work. Vibe coders ship with it; security pros use it to save time on client assurance work.

## Is testing legal?

Only test systems you own or have explicit written permission to test. IronBOT acts strictly within the scope you authorize.

## How is pricing structured?

A single pentest starts at **$15** (One-Shot Pentest). Continuous security is sold as **IronBOT Enterprise (PTaaS)** — [book a call](https://ironbot.io/#contact) and we'll size it to your company.

## How do I report a security issue in IronBOT itself?

See [SECURITY.md](../SECURITY.md). Please report privately — not in a public issue.
