# MyMeds — Privacy Policy · سياسة خصوصية دوائي

The published privacy policy and support page for **MyMeds (دوائي)**, the bilingual iOS medication
reminder.

**Live page:** https://qtrcipher.github.io/mymeds-privacy/

Used for two App Store Connect fields:

| App Store Connect field | URL |
|---|---|
| Privacy Policy URL | `https://qtrcipher.github.io/mymeds-privacy/` |
| Support URL | `https://qtrcipher.github.io/mymeds-privacy/#support` |

## Why this repo is public and separate

App Store Connect requires a privacy policy URL that anyone can open without signing in, so the
page must be public. The app's own repository is private, so the policy lives here instead of
being the one public file in a private project.

## Editing

`index.html` is the whole site — one page, no build step, no dependencies. GitHub Pages serves it
from the `main` branch. Arabic comes first on the page, deliberately: MyMeds is Arabic-first, and
so is its policy.

**If you change what the app does with data, change this page in the same release.** The two claims
most easily invalidated are "no third-party SDKs" and "no analytics" — adding a single dependency
can make both false. The app's `docs/10-app-store-compliance.md` records how each claim was
verified.

Update the effective date at the top of **both** language sections when the policy changes.
