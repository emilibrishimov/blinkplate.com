# blinkplate.com

The Blinkplate website: a logo homepage and the app’s privacy policy at `/privacy.html`.

Plain HTML and CSS, with no build step, JavaScript, analytics, or external fonts. The outlined SVG logos come from the Blinkplate app’s `brand/` directory.

## Preview

Run `python3 -m http.server 8000`, then open http://localhost:8000.

## Publish

GitHub Pages serves the root of `main`. Changes pushed to `main` publish automatically. Both the repository and website are public.

Custom domain: `blinkplate.com`. Cloudflare manages DNS. Use GitHub Pages’ documented apex A records and a `www` CNAME to `emilibrishimov.github.io`, with DNS-only proxy mode until GitHub verifies the domain and issues HTTPS.

The policy’s contact address is `contact@blinkplate.com`; configure and verify mail delivery before using the policy for App Store submission. Keep the policy in sync with the app and its providers.

## App release follow-up

The app still needs an easily accessible policy link, consent before sending photos and context to DeepInfra, and an account deletion flow (including a reliable way to identify the anonymous account). The website does not implement these app requirements. Confirm service-provider protections and retention settings before App Store submission.
