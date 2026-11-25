# bpfina.com

A one-page hold site: a centered numeral **88**.

This repository is prepared locally and has not been pushed. GitHub Pages is not enabled.

`bpfina.com` is already registered at Porkbun (Brian owns it). Do not register `benfina.com` — Brian confirmed it is not his. See `../DNS-PLAN.md`.

Intended GitHub repo: `plinymiller/bpfina.com` (GitHub Pages from `main`, `CNAME` = `bpfina.com`), matching `plinymiller/b-tuff.co`, to be published only after Brian approves publishing.

## Local preview

```bash
python3 -m http.server 8083
```

## After approval

1. Domain is already at Porkbun — do not buy it again. Do not register `benfina.com`.
2. Create the GitHub repo and push this `main` branch (from the git bundle if needed).
3. Enable GitHub Pages from `main` only after Brian OKs publishing.
4. Apply the DNS and email-forwarding plan in `../DNS-PLAN.md` (`88@bpfina.com` → `plinymiller@gmail.com`). When adding GitHub Pages A / www CNAME records, **keep any existing MX and SPF** (Porkbun forwarding records are already on this zone).
