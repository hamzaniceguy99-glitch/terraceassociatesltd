# Terrace Associates — terrace associates ltd

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `terraceassociatesltd.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/terraceassociatesltd.mjs`).
> To change the content, edit that file and run `node build.mjs terraceassociatesltd` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@terraceassociatesltd.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($No fee / $£[AMOUNT] / $Declined) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
Terrace Associates Ltd buys and sells property on its own account from Charing in Kent, and has been trading since 2012. We are the principal in every transaction, which means we are the buyer or we are the seller, never an agent acting for someone else, and we do not charge sellers a fee. Two commitments follow from how this trade actually works. The first is material information. Since April 2025 the unfair commercial practices rules have sat in the Digital Markets, Competition and Consumers Act, and the failure that catches property is not lying, it is leaving something out, because an accurate description can still mislead by omission. So tenure, council tax band, price, and the things that apply to some properties and change everything when they do, such as flood risk, restrictive covenants, rights of way or mining history, go in front of a buyer before an offer rather than surfacing in conveyancing. The second is the price. When a company buys directly from an owner it pays below open market value, and what the seller is buying with that difference is speed and certainty. That is a legitimate trade and we state it in those words rather than dressing it up. Our view on price is not a survey or a formal valuation, and we will tell you to take your own. Site: terraceassociatesltd.shop
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
