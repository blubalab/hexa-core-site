# hexa-core-site

Public site for Hexa Core: Awakening, served by GitHub Pages at `https://hexa-core.blubalab.com`.
Its own public repo because the game's source repo stays private.

- `index.html` - "coming soon" teaser (no screenshots until the game is finished)
- `privacy/index.html` - privacy policy. The game opens this URL from its privacy notice
  (`MonetizationConfigDefinition.PrivacyPolicyUrl`), and Play Console needs it in the store
  listing and the Data safety form. The authored draft lives in the game repo at
  `Docs/Release/PrivacyPolicy.html`; copy changes over here when it's updated.
- `img/` - banner and icon, web-sized from `Assets/Art/Store/Play/`

No build step. `CNAME` pins the custom domain; `.nojekyll` turns off Jekyll.

DNS (Porkbun, zone `blubalab.com`): `CNAME` host `hexa-core` -> `blubalab.github.io`.
