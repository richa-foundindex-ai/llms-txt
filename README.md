# llms.txt

**A proposed standard for AI-readable websites**

[![AI-Readable Site](https://foundindex.com/badges/ai-readable.svg)](https://foundindex.com/llms-txt)

## What is llms.txt?

llms.txt is a machine-readable file that tells AI systems how to interpret a website's content. Like robots.txt guides crawlers, llms.txt guides AI systems in understanding site purpose, audience, and authoritative content.

**Current Version:** 0.1 (Draft)  
**Status:** Community proposal  
**Proposed by:** [FoundIndex](https://foundindex.com)

## Quick Start

Create a file at `https://yoursite.com/llms.txt` (or `/.well-known/llms.txt`) with:
```txt
# llms.txt v0.1
# Learn more: https://foundindex.com/llms-txt

version: 0.1
site-purpose: Your site's core purpose
primary-audience: Your target audience  
authoritative-pages:
  - /docs
  - /pricing
update-frequency: weekly
contact: hello@example.com
last-updated: 2025-12-16
language: en
```

## Full Specification

See the complete technical specification at:  
**https://foundindex.com/llms-txt**

## Validator & Generator

- **Validator:** Test your llms.txt implementation at https://foundindex.com/llms-txt
- **Generator:** Use the 5-field form to auto-generate your file

## Examples

Reference implementations for different site types:

- [SaaS Product](examples/saas-example.txt)
- [Blog](examples/blog-example.txt)
- [Documentation Site](examples/docs-example.txt)
- [E-commerce](examples/ecommerce-example.txt)
- [Portfolio](examples/portfolio-example.txt)

## Implementations

Sites currently using llms.txt:
- [FoundIndex](https://foundindex.com/llms.txt) - AI visibility diagnostic
- [Light Travel Action](https://lighttravelaction.com/llms.txt) - Travel photography blog

_Add your site via pull request!_

## Contributing

This is a community-driven specification. We welcome:
- 📝 Issues for spec clarifications
- 💡 Suggestions for new directives
- 🌟 Pull requests with example implementations
- 🐛 Bug reports for the validator

## Versioning

This specification follows semantic versioning (v0.1, v0.2, v1.0):
- **Major versions** (1.0 → 2.0): Breaking changes
- **Minor versions** (0.1 → 0.2): New optional directives
- **Patch versions** (0.1.0 → 0.1.1): Clarifications

Backward compatibility is prioritized.

## Roadmap

**v0.2 (Q2 2026):**
- Multi-language support
- Content categorization directives
- Time-based scoping

**v1.0 (Q3 2026):**
- W3C Community Group submission
- Formal parser specification

## License

CC0 - Public Domain

This specification is released under [Creative Commons Zero](https://creativecommons.org/publicdomain/zero/1.0/) to maximize adoption and reuse.

## Contact

- **Questions:** hello@foundindex.com
- **Website:** https://foundindex.com
