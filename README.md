# yurieff.github.io

A public home page, privacy policy and terms for each of my personal apps. Google requires all three before an OAuth app can be published "In production".

## New Google Cloud app checklist

1. Copy `clio/` to `<app>/` and rewrite the three pages: what the app does and which Google data it touches. Commit and push; the pages go live in about a minute.
2. Google Cloud → Google Auth Platform → **Branding**:
   - Application home page: `https://yurieff.github.io/<app>/`
   - Privacy policy: `https://yurieff.github.io/<app>/privacy.html`
   - Terms of service: `https://yurieff.github.io/<app>/terms.html`
   - Authorized domains: `yurieff.github.io`
   - Do **not** upload a logo: it triggers brand verification.
3. **Audience → Publish app**. Sensitive or restricted scopes stay "unverified": the consent screen shows a warning, and there is a cap of 100 users. That is fine for personal use.

Ownership of `https://yurieff.github.io/` is verified once in Google Search Console with the meta tag in `index.html`. Keep that tag.
