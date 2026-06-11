# six9.uk — The History of Java ☕

An animated, single-page scroll-story of the Java programming language — from the Green Project and "Oak" in 1991 to virtual threads and Java 25. One `index.html`, no dependencies, no build step.

- Scroll-driven reveals (IntersectionObserver)
- A timeline line that "draws" itself as you scroll + top progress bar
- Coffee theme: steaming cup hero, Duke 👋 wave, Sun→Oracle morph
- Respects `prefers-reduced-motion`
- Pure vanilla HTML / CSS / JS

## Run locally
Open `index.html` in a browser, or:
```bash
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Deploy on Cloudflare Pages (free) + attach six9.uk
1. Push this folder to a GitHub repo.
2. Cloudflare dashboard → **Workers & Pages → Create → Pages → Connect to Git** → pick the repo.
3. Build settings: **Framework preset = None**, **Build command = (empty)**, **Output directory = `/`**. Deploy.
4. Pages project → **Custom domains → add `six9.uk`** → Cloudflare auto-creates the DNS record + SSL.
5. Visit **https://six9.uk** 🎉

## Timeline accuracy
Dates reflect the language's real history: Oak (1991), public release May 23 1995, JDK 1.0 (1996), Java 5/"Tiger" (2004), OpenJDK (2006–07), Oracle acquires Sun (2010), Java 8 lambdas/streams (2014), modules + 6-month cadence (2017), LTS 11 & 17 (2018/2021), virtual threads in Java 21 (2023), Java 25 (2025).
