# "Do I need Patch Today?"

Vulnerability & Patching needs prioritization or a risk based approach.

Different systems exists to help with prioritizing remediation efforts, namely:

- [NIST National Vulnerabiltiy Database CVSS](https://nvd.nist.gov/) CVSS Severity (latest v3.1)
- [FIRST EPSS](https://first.org/epss) Exploit Probability Scoring System

For prioritize the combination of a) the severity or impact to a system (provided by CVSS rating) and b) the probability of exploitation or high likely a vulnerability is exploited in the next 30 days.

## Simple _(opinionated)_ Decision Matrix

| _Severity_ (CVSS) | _Probability_ (EPPS) | Action       |
| ----------------- | -------------------- | ------------ |
| Critical/High     | High                 | FIX          |
| Critical/High     | Low                  | _Watch_    |
| Low               | High                 | _Caution!_   |
| Low               | Low                  | deprioritize |

[Read more](https://www.first.org/epss/user-guide) for more information.
