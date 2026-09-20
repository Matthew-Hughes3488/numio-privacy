# Numio privacy website

Standalone public website, separate from the private Numio iOS repository.

Public URL: https://matthew-hughes3488.github.io/numio-privacy/

Plain HTML and CSS, with no build dependencies, JavaScript, analytics or external assets. GitHub Pages publishes the root of `main` automatically after pushes.

## Status

Published **pre-launch draft**, not a final release privacy notice. The page visibly identifies unresolved points and is marked `noindex` while under review. No effective date is claimed.

Before finalising:

- Implement/verify the approved 90-day deletion of minimal abuse-prevention usage records following account deletion. This website does not change the backend.
- Set billing, guest, log, backup and provider retention schedules; confirm downstream deletion behaviour.
- Confirm actual processing regions and international-transfer safeguards with the configured providers.
- Confirm lawful bases, age-appropriate safeguards and any necessary consent arrangements, including third-party AI disclosure/permission and analytics, for the intended audience that includes children.
- Replace the draft-only passages with verified arrangements, set an effective date, and remove the draft banner and `noindex` once accurate. Keep the same URL.

Owner/contact supplied by the operator: Matthew Hughes, 12hughesm@gmail.com.

## Content evidence

Draft checked against the app's Supabase account/deletion schema, OpenAI recognition and generation requests, PostHog configuration and RevenueCat integration on 20 September 2026. Those implementation details establish data flows, not a claim of production compliance or verified deployed configuration.

Reference guidance:

- [ICO: children and the UK GDPR](https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/childrens-information/children-and-the-uk-gdpr/)
- [Apple: privacy guidelines](https://developer.apple.com/app-store/review/guidelines/#privacy)
- [Apple Standard EULA](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/)

## Editing

Edit `index.html` and `styles.css`, then commit and push to `main`. Review factual claims against the actual service before changing the policy. No application code, credentials, customer records or private screenshots belong in this repository.
