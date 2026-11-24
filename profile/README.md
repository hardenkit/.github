<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./logo-dark.svg">
  <img src="./logo-light.svg" alt="HardenKit" width="56" height="56">
</picture>

# HardenKit

**Find the vulnerabilities attackers actually use.**

HardenKit is an open-source vulnerability scanner that ranks findings by real attack data and gives you one upgrade per package. Free CLI and GitHub Action.

```bash
curl -sSfL https://hardenkit.com/install.sh | sh
hardenkit scan
```

| Priority | Meaning |
|:---------|:--------|
| **FIX NOW** | Being exploited in the wild (on CISA's Known Exploited Vulnerabilities list) |
| **FIX SOON** | Critical, or likely to be exploited in the next 30 days (EPSS ≥ 10%) |
| **PLAN** | High severity |
| **BACKLOG** | Everything else |

- **Scanner:** [hardenkit/scan](https://github.com/hardenkit/scan) (Apache-2.0)
- **Docs:** [hardenkit.com/docs](https://hardenkit.com/docs)
- **Site:** [hardenkit.com](https://hardenkit.com)
- **Changelog:** [hardenkit.com/changelog](https://hardenkit.com/changelog)
- **Contact:** [hardenkit.com/contact](https://hardenkit.com/contact)
- **Report a vulnerability:** [hardenkit.com/legal/disclosure](https://hardenkit.com/legal/disclosure)
