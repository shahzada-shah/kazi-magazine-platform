# New repo setup

## Name
`kazi-magazine-platform`

Why: "platform" says it is the whole system (SPA + CMS + edge), not a component library. Avoid "-react" (undersells the Worker/CMS work) and "-showcase" (reads as a demo, not a shipped product). If taken: `kazimagazine-platform`.

## Description (repo sidebar, ≤ 350 chars)
Editorial platform behind kazimagazine.com. React 19 + TypeScript SPA, Sanity content lake, 3D cover experiences, Cloudflare Worker for crawlers, sitemaps and edge APIs. Architecture and engineering decisions of a shipped product.

## Website
https://kazimagazine.com

## Topics (max 20; GitHub lowercases and hyphenates)
react · typescript · vite · tailwindcss · sanity · cloudflare-workers · cloudflare-pages · threejs · spa · edge-computing · seo · open-graph · performance · code-splitting · playwright · vitest · portfolio · case-study · music · digital-magazine

## Settings checklist
- Visibility: **Public**
- Social preview: Settings → General → Social preview → upload `docs/readme/og-image.png`
- Features: turn **off** Wikis, Projects, Discussions (nothing to fill them)
- Issues: **off**, or on with a single pinned "About this repo" issue
- Default branch: `main`
- Add `LICENSE`? No. It is documentation of proprietary work; leave it unlicensed (all rights reserved by default)
- Pin it on your profile, first slot

## First commit
```bash
git init -b main
git add .
git commit -m "docs: architecture and engineering showcase for Kazi Magazine"
git remote add origin git@github.com:shahzada-shah/kazi-magazine-platform.git
git push -u origin main
```

## Files in this repo
```
README.md
docs/readme/banner.png          # README header
docs/readme/architecture.png    # Architecture section
docs/readme/og-image.png        # Social preview (upload in Settings)
docs/readme/demo-home.gif       # to record
docs/readme/demo-globe.gif      # to record
docs/readme/ASSETS.md
docs/readme/REPO_SETUP.md       # this file
```
