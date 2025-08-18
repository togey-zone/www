# TOGEY Minimal Single Page — Deploy Guide

This folder contains a minimal bilingual (ZH/EN) landing page for **TOGEY LIMITED** suitable for Wise / ZA Bank KYC.

## Files
- `index.html` — the page (no external deps).
- Optional: create a `CNAME` file if you use GitHub Pages with a custom domain (e.g. `business.togey.com`).

---

## Option A — Cloudflare Pages (recommended if your DNS is on Cloudflare)
1. Create a new Pages project in Cloudflare Dashboard.
2. Choose **Direct Upload** and upload `index.html`.
3. Bind a custom domain or subdomain (e.g. `business.togey.com`).
4. In your DNS, add a CNAME from `business.togey.com` → assigned Pages hostname.
5. Enable HTTPS.

Pros: fastest, zero repo required, perfect with your existing Cloudflare setup.

---

## Option B — GitHub Pages (classic)
1. Create a new GitHub repo (public or private with Pages enabled).
2. Commit `index.html` to the repo root.
3. In **Settings → Pages**, set:
   - Source: `Deploy from a branch`
   - Branch: `main` (or `master`), folder `/root`
4. (Custom domain) Add `CNAME` file containing your domain, e.g. `business.togey.com` and configure DNS CNAME to `<user>.github.io`.
5. Wait for Pages to publish and TLS to issue.

Pros: easy versioning; Cons: one more platform in the loop.

---

## Suggested Domains
- `business.togey.com` (clean corporate face)
- `about.togey.com` (brand profile)
- `hk.togey.com` (HK‑specific info)
