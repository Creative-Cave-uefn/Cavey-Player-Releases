# Cavey Player — Releases & Official Website

Official releases and public Google OAuth information for Cavey Player.

- **Website:** https://caveyplayer.pp.ua/
- **Privacy policy:** https://caveyplayer.pp.ua/privacy.html
- **Terms:** https://caveyplayer.pp.ua/terms.html
- **Releases:** https://github.com/Creative-Cave-uefn/Cavey-Player-Releases/releases/latest
- **Track deep-link gateway:** https://caveyplayer.pp.ua/open/

## Publishing

The static website lives in the repository root and uses GitHub Pages (branch **main**, folder **/(root)**), with custom domain **caveyplayer.pp.ua**. The existing `/open/` endpoint is preserved at `https://caveyplayer.pp.ua/open/`.

NIC.UA DNS settings: use NIC.UA name servers rather than Parking NS; create four A records for `@`: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`; optionally `www` CNAME `creative-cave-uefn.github.io`. Avoid conflicting A records for `@`. Changes can take up to 24 hours to propagate.

If GitHub Pages does not update automatically, open **Settings → Pages**, set **Deploy from a branch**, **main**, **/(root)**, and save. HTTPS should be enabled.

Google Cloud Console → Google Auth Platform → Branding:

- App name: **Cavey Player**
- User support email: **set your own, monitored real email in the Console** (it is not embedded in this public repository).
- App homepage: https://caveyplayer.pp.ua/
- Privacy policy: https://caveyplayer.pp.ua/privacy.html
- Terms of service: https://caveyplayer.pp.ua/terms.html

**For Google verification:** verify ownership of `caveyplayer.pp.ua` as a Domain property in Google Search Console using the DNS TXT record provided by Google. Then add `caveyplayer.pp.ua` as an Authorized domain in Google Auth Platform → Branding. Do not use the old github.io links in OAuth Branding.

**Accuracy note:** The current desktop app requests the full (restricted) Google Drive OAuth scope. The public policy discloses this. Publishing the website does not change OAuth scopes or bypass Google's restricted-scope verification requirements.

**Update privacy and terms when code or data practices change.** The support link currently uses GitHub Issues; the actual OAuth support email must be configured by the Google Cloud project owner.
