# Smart CDL — public site

Landing page and legal documents for the **Smart CDL** Android app, served via
GitHub Pages.

| Page | URL |
|---|---|
| Landing | https://qaresearch10.github.io/smartcdl-site/ |
| Privacy policy | https://qaresearch10.github.io/smartcdl-site/privacy.html |

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

No build step — plain static HTML, self-contained, no external assets.
