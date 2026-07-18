# Prepared OSINT Workflows

*Published 2026-07-18*

You can now trigger ready-made OSINT lookups directly in chat — no need to know which tools to run or in what order.

**Triggers:**

- `osint:email <address>` — checks which platforms an email is registered on, plus domain/MX lookup
- `osint:person <name>` — public profile and username enumeration across platforms
- `osint:company <name>` — resolves a company name to its official domain, then maps infrastructure and org info
- `osint:domain <domain>` — whois, subdomain enumeration, DNS records
- Send `osint` on its own to see the full list again

Each workflow runs real tools (whois, dig, holehe, sherlock, theHarvester, crt.sh) on your own rented Kali Linux VPS — rent one in the Virtual Machines section if you don't have one yet. If you don't have a machine, the model will tell you so directly instead of guessing or making anything up.

---

[All news](https://imbutus.com/news) · [imbutus.com](https://imbutus.com)
