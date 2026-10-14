# Smart CDL — public site

Landing page and legal documents for the **Smart CDL** Android and iOS app, plus the
publisher page for **Smart Apps**, served via GitHub Pages.

| Page | URL |
|---|---|
| Landing | https://qaresearch10.github.io/smartcdl-site/ |
| Privacy policy | https://qaresearch10.github.io/smartcdl-site/privacy.html |
| Official sources | https://qaresearch10.github.io/smartcdl-site/sources.html |
| Smart Apps (publisher) | https://qaresearch10.github.io/smartcdl-site/smartapps.html |

The privacy policy URL is referenced from the app's Google Play listing, so **it
must stay reachable** — a broken link can get the listing flagged or removed.

## Notes for future edits

- This branch contains the privacy and marketing changes for remote content
  delivery and optional Firebase Analytics usage reports. Publish them with the
  configured app release, set the policy's actual
  effective date, and update Google Play Data safety and Apple App Privacy.
- Name, answers, saved reviews, and progress stay on-device. Content requests
  disclose selected state, app build, release identifiers, attestation information,
  and standard network metadata. Optional push uses Firebase registration and
  state/global topic subscriptions. Keep provider/log retention disclosures in sync
  with the deployed configuration.
- Network features include Google Cloud/Firebase content delivery and optional
  push and usage analytics, official handbook downloads, platform-store
  purchases, and user-submitted
  support email. Fonts are bundled; runtime font fetching is disabled.
- Usage sharing defaults off. Opted-in Analytics includes licensing state and
  feature events plus automatic app/device/session and possible purchase metadata.
  It does not upload study answers or scores; keep the policy aligned with the
  SDK and release store disclosures.
- Contact address is `smart.apps.ca@gmail.com`, which must match `kSupportEmail`
  in the app.
- `smartapps.html` is the publisher page, suitable as the developer website in
  the Play Console. Its claims (no accounts, no ads or tracking, on-device data,
  offline, one-time purchases) must hold for **every** app listed on it, so
  revisit it whenever an app is added or an existing one gains a backend. A
  Google Play link for Smart CDL sits commented out in it until the listing is
  public.

No build step — plain static HTML, self-contained, no external assets.
