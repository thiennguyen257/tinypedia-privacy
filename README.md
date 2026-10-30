# Tinypedia privacy policy

The public privacy policy of the Android app **Tinypedia: Bé Khám Phá** (`com.tinypedia.app`) by the developer **CrisKisa**, a picture dictionary for children aged 3 to 6.

**Live page:** https://thiennguyen257.github.io/tinypedia-privacy/

Google Play asks for this URL in Play Console (App content, Privacy policy) and shows it on the store listing. The page must stay online, public and free of any login for as long as the app is on Google Play.

## What is here

| File | Purpose |
|---|---|
| `index.html` | The policy: Vietnamese first, then English, one page, no scripts, no trackers, no external assets |
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

- what the app stores on the device (today: stories heard, items seen, puzzle stars and best times with one unfinished puzzle, maze levels done with best times);
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

## History

| Effective | Change |
|---|---|
| 2026-10-30 | First version, for the first release (1.0.0): no data collected or shared, no ads, no account, no Internet permission, progress kept on the device only (backup and device transfer off), Azure synthetic voice made before release, developer CrisKisa |
| 2026-10-30 | `credits.html` added (photo credits for the store screenshots); the policy itself unchanged |

## Contact

CrisKisa, criskisa01@gmail.com
