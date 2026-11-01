# Cavey Player — Releases & Official Website

Official releases and public Google OAuth information for Cavey Player.

- **Website:** https://creative-cave-uefn.github.io/Cavey-Player-Releases/
- **Privacy policy:** https://creative-cave-uefn.github.io/Cavey-Player-Releases/privacy.html
- **Terms:** https://creative-cave-uefn.github.io/Cavey-Player-Releases/terms.html
- **Releases:** https://github.com/Creative-Cave-uefn/Cavey-Player-Releases/releases/latest
- **Track deep-link gateway:** https://creative-cave-uefn.github.io/Cavey-Player-Releases/open/

## Publishing

The static website lives in the repository root and uses GitHub Pages (branch **main**, folder **/(root)**). The existing /open/ endpoint is preserved.

If GitHub Pages does not update automatically, open **Settings → Pages**, set **Deploy from a branch**, **main**, **/(root)**, and save. HTTPS should be enabled.

Google Cloud Console → Google Auth Platform → Branding:

- App name: **Cavey Player**
- User support email: **set your own, monitored real email in the Console** (it is not embedded in this public repository).
- App homepage: https://creative-cave-uefn.github.io/Cavey-Player-Releases/
- Privacy policy: https://creative-cave-uefn.github.io/Cavey-Player-Releases/privacy.html
- Terms of service: https://creative-cave-uefn.github.io/Cavey-Player-Releases/terms.html

**For Google verification:** verify domain ownership in Google Search Console. GitHub Pages on a shared github.io domain may not satisfy every OAuth verified-domain requirement. If Google rejects it, configure a domain you control via GitHub Pages and update the site's canonical and Google Cloud links accordingly.

**Accuracy note:** The current desktop app requests the full (restricted) Google Drive OAuth scope. The public policy discloses this. Publishing the website does not change OAuth scopes or bypass Google's restricted-scope verification requirements.

**Update privacy and terms when code or data practices change.** The support link currently uses GitHub Issues; the actual OAuth support email must be configured by the Google Cloud project owner.
