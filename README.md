# blinkplate.com

The Blinkplate website: a logo homepage and the app’s privacy policy at `/privacy.html`.

Plain HTML and CSS, with no build step, JavaScript, analytics, or external fonts.
The outlined SVG logos come from the Blinkplate app’s `brand/` directory.

## Preview

Run `python3 -m http.server 8000`, then open http://localhost:8000.

## Publish

Serve the repository root as a static website. The source repository stays private; the website is public.

Before publishing the policy, confirm the operator and contact details and keep its statements in sync with the app and its service providers.

## Current setup

Private GitHub repository: https://github.com/emilibrishimov/blinkplate.com

GitHub Pages rejected activation because the current account plan does not support Pages for private repositories. Hosting choice is pending: GitHub Pro with Pages, or Cloudflare Pages connected to this private repository. Cloudflare currently manages the domain’s DNS.

The privacy policy is a draft until `OWNER_NAME` and `CONTACT_EMAIL` are confirmed. Do not publish placeholders.

## App release follow-up

The app still needs an easily accessible policy link, consent before sending photos and context to DeepInfra, and an account deletion flow (including a reliable way to identify the anonymous account). The website does not implement these app requirements. Confirm service-provider protections and retention settings before App Store submission.
