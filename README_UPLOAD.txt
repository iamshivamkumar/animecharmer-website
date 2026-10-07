ANIME CHARMER — STATIC WEBSITE UPLOAD
Prepared 8 October 2026 for https://animecharmer.com

This folder contains the deployable website, not a deployment confirmation.
It is a single HTML page with local artwork. No framework, build step, CDN,
analytics, video embed, cookies, login, contact form backend or JavaScript is used.

UPLOAD
1. Arrange static website hosting for animecharmer.com. The domain currently
   redirects to the YouTube channel; replace that forwarding rule only when your
   chosen hosting is configured and you are ready to publish this site.
2. Extract this ZIP. Upload index.html, app-ads.txt, robots.txt and the assets
   directory directly into the public web root (often public_html or www).
   Do not upload an enclosing dist directory instead of its contents.
3. Point the domain DNS to the hosting provider using its exact instructions.
   Enable a valid HTTPS certificate. Hosting/DNS changes are not made by this ZIP.
4. Verify these public URLs on desktop and phone after upload:
   https://animecharmer.com/
   https://animecharmer.com/#support
   https://animecharmer.com/#privacy
   https://animecharmer.com/app-ads.txt
   https://animecharmer.com/assets/last-armourfall.png
5. Check that #support and #privacy land on the correct visible sections; that
   email links open your mail app; and that all text and images load without a
   password, interstitial, redirect to YouTube or broken image.
6. Only after live checks, update the game's Config/release profile, Play Console
   website/privacy/deletion-request entries and applicable AdMob website/privacy
   message fields. Existing receipts and published-history records stay intact.

GITHUB PAGES + HOSTINGER DNS
1. Upload these public files to the chosen GitHub repository's Pages source.
   Keep CNAME (animecharmer.com) and .nojekyll in the published root. Do not put
   private release reports, game binaries, credentials or builder scripts there.
2. In repository Settings > Pages, select the actual publishing branch/folder
   or the root-owned Pages workflow. Set the custom domain to animecharmer.com.
3. In Hostinger's DNS editor, remove the old website/URL forwarding to YouTube
   when the new Pages site is ready. Keep unrelated email verification/MX/TXT
   records. Use the CURRENT GitHub Pages apex-domain DNS records from GitHub's
   official documentation; do not guess IPs or create a conflicting apex CNAME.
   A www CNAME, if wanted, must point to the actual GitHub Pages hostname for the
   chosen account. The root task owns the exact repo and DNS values.
4. Wait for GitHub's DNS check and certificate provisioning, then enable Enforce
   HTTPS and verify root, both anchors, local assets and app-ads.txt publicly.
   DNS propagation and HTTPS provisioning can take time. This ZIP does neither.
Official guidance:
https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

SUPPORT / POLICY
Public email: iam.shivamsng@gmail.com
The page includes the complete current Last Armourfall privacy clauses, with an
8 October 2026 date and a short website-hosting paragraph. It preserves the
age-group policy, adult-only ads/consent, local saves and Google Play map-download
disclosures. Review any hosting provider's added analytics or cookies before
enabling them: this download does not include them.

app-ads.txt was copied verbatim from the current game support site. Serve it at
the DOMAIN ROOT as plain text. Do not place it only under /assets or a game path.
The existing email and YouTube link remain available; no store release is claimed.

BACKUP
Keep a copy of this ZIP and your hosting credentials privately. Do not add keys,
passwords, private receipts or game save files to the public upload directory.
