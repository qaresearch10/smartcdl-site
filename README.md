# Smart CDL — public site

Landing page and legal documents for the **Smart CDL** Android app, plus the
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

- The policy describes the app as having **no backend**: nothing the user enters
  leaves their device. If that ever changes — analytics, crash reporting, an
  account system, a sync service — the policy and the Play Console **Data safety**
  declaration must both be updated, and they must agree with each other.
- The three disclosed network cases are state-government handbook downloads, the
  `google_fonts` runtime font fetch, and Google Play purchase handling.
- Update the effective date at the top of `privacy.html` on any material change.
- Contact address is `smart.apps.ca@gmail.com`, which must match `kSupportEmail`
  in the app.
- `smartapps.html` is the publisher page, suitable as the developer website in
  the Play Console. Its claims (no accounts, no ads or tracking, on-device data,
  offline, one-time purchases) must hold for **every** app listed on it, so
  revisit it whenever an app is added or an existing one gains a backend. A
  Google Play link for Smart CDL sits commented out in it until the listing is
  public.

No build step — plain static HTML, self-contained, no external assets.
