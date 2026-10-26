# FRB Builders — frb builders ltd

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `frbbuildersltd.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/frbbuildersltd.mjs`).
> To change the content, edit that file and run `node build.mjs frbbuildersltd` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@frbbuildersltd.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Quote / $Referred) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
FRB Builders Ltd is a construction company based in Barnet, north London, building domestic and commercial buildings since 2020. We take on new builds, extensions and loft conversions, full refurbishment, and commercial fit-out. Two pieces of paper decide whether a job is actually finished, and both get skipped often enough to be worth stating. Before work that affects a shared wall or excavates near a neighbour's building, the Party Wall etc. Act 1996 requires notice to be served on that neighbour, and starting without it is how an injunction and a stopped site happen. And at the end, the Building Regulations completion certificate is what you will need when you sell or remortgage, so we see it issued rather than leaving it open. Notifiable electrical work and all gas work go to registered specialists. Site: frbbuildersltd.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
