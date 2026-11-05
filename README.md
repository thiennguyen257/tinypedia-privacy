# Tinypedia privacy policy and terms

The public privacy policy and terms of service of the Android app **Tinypedia: Little Explorer** (Vietnamese name and Google Play title: **Tinypedia: Bé Khám Phá**; `com.tinypedia.app`) by the developer **CrisKisa**, a picture dictionary for children aged 3 to 6.

**Live pages:** https://thiennguyen257.github.io/tinypedia-privacy/ (privacy policy) and https://thiennguyen257.github.io/tinypedia-privacy/terms.html (terms of service)

Google Play asks for the privacy URL in Play Console (App content, Privacy policy) and shows it on the store listing. The terms URL goes in App content, "Trader status at app level and Terms of Service" (the app is declared as offered by a trader); Google shows it to users worldwide from 2027-03-01. Both pages must stay online, public and free of any login for as long as the app is on Google Play.

## What is here

| File | Purpose |
|---|---|
| `index.html` | The policy: English first, then Vietnamese, one page, no scripts, no trackers, no external assets |
| `terms.html` | The terms of service, same look and layout as `index.html` (its `<head>` styles and icons are a copy: change both together). Specific to this app; keeps mandatory consumer rights (EEA, UK) intact |
| `credits.html` | Credits for the CC BY photos shown in the app's Google Play screenshots (linked from the store description). Generated, do not edit by hand: `python app/tool/store_art.py --credits <this repo>` in the app repo, whenever the screenshots change |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are, without a Jekyll build |
| `.gitignore` | Keeps editor and OS files out of the repo |
| `.gitattributes` | Stores text files with LF line endings |

The app's source lives in a separate, private repository. This repo holds only what is meant to be public.

## Publishing

GitHub Pages serves the `main` branch, folder `/ (root)` (repo Settings, Pages). A push to `main` is live within a minute or two. Check afterwards, in a private browser window:

- the URL answers without a login, over HTTPS;
- both the Vietnamese and the English section show the new text and the new effective date.

## When to update the policy

The policy describes one app version. Update it **before** releasing a version that changes any of these:

- what the app stores on the device (today: stories heard, items seen, puzzle levels done with best times and one unfinished puzzle, maze levels done with best times);
- permissions, above all `INTERNET` (the app has none today);
- ads, accounts, analytics, crash reporting or any third-party SDK that handles data;
- in-app purchases (none today);
- the contact e-mail or the developer name (it must match the name on the store listing);
- Android backup (the app turns off cloud backup and device-to-device transfer today).

Then, in the same change:

1. Edit both language sections so they say the same thing (the English text is written for English readers, not translated word for word).
2. Set the new effective date at the top of the page.
3. Add a row to the history below.
4. Bring Play Console's Data safety form and the app's own privacy text (parent area) in line with the page: Google compares them.

Wording rule: describe the current version only. Do not promise "always free", "free forever" or "never any purchase".

## When to update the terms

Update `terms.html` before releasing a version that adds paid content or in-app purchases, ads, accounts, or changes what the app's license allows; also when the developer name or contact e-mail changes. Same steps as for the policy: both languages, new effective date, a history row. The wording rule above applies too.

## History

| Effective | Change |
|---|---|
| 2026-10-30 | First version, for the first release (1.0.0): no data collected or shared, no ads, no account, no Internet permission, progress kept on the device only (backup and device transfer off), Azure synthetic voice made before release, developer CrisKisa |
| 2026-10-30 | `credits.html` added (photo credits for the store screenshots); darker accent colour on both pages for readable links (WCAG AA); the policy text unchanged |
| 2026-11-03 | The app's stars now come from levels done, not from times: the jigsaw line says "levels done with their best times" (vi and en), no "stars" or game wording; new look (header band in the app's colours, summary cards, inline SVG icons, sticky language switch, dark mode and print styles), still one page with no scripts and no external assets |
| 2026-11-04 | The kept list gains "how far the hoa bé ngoan flower of each practice pack has opened" (vi and en), for the practice corner's flowers in build 2; the header shows the new app logo (a chick beside a toddler), as inline SVG written by `app/tool/store_art.py --logo` |
| 2026-11-05 | `terms.html` added: terms of service for the trader declaration in Play Console (free current version, personal license, content credits, learning content, "as is" within the law, consumer rights kept, Vietnamese law); the policy footer links to it; the policy text unchanged |
| 2026-11-05 | English first on all three pages (`lang="en"`, the English section, title, header and language switch before the Vietnamese), ahead of an English-first app; the texts unchanged |
| 2026-11-05 | The English name **Tinypedia: Little Explorer** (the app's `appTitle` in English) in the titles, headers, footers and English sections; the English sections name the Google Play title once; the Vietnamese sections keep **Tinypedia: Bé Khám Phá** |

## Contact

CrisKisa, criskisa01@gmail.com
