# Numio privacy website

Standalone public website, separate from the private Numio iOS repository.

Public URL: https://matthew-hughes3488.github.io/numio-privacy/

Plain HTML and CSS, with no build dependencies, JavaScript, analytics or external assets. GitHub Pages publishes the root of `main` automatically after pushes.

## Status

Published privacy page. At the operator's request on 20 September 2026, the draft label, banner and `noindex` were removed, and the under-13 provider issue was deferred. This publication change does not resolve the outstanding implementation or provider requirements below, or establish production compliance. The public page retains factual qualifications where retention enforcement is unverified.

Outstanding launch checks:

- Implement/verify the approved 90-day deletion of minimal abuse-prevention usage records following account deletion. This website does not change the backend.
- Required UK sole-trader accounting records: approved retention of five years after the relevant 31 January filing deadline, extended where specifically required by law. Identify which records are actually needed; this is not blanket retention for all subscription events.
- Set other operational billing, guest, log, backup and provider retention schedules; confirm downstream deletion behaviour.
- Confirm actual processing regions and international-transfer safeguards with the configured providers.
- Confirm lawful bases, age-appropriate safeguards and any necessary consent arrangements, including third-party AI disclosure/permission and analytics, for the intended audience that includes children.
- Concrete all-ages blocker: OpenAI's under-18 guidance says not to process personal data of children under 13/the applicable digital-consent age without Zero Data Retention. Project-level ZDR approval/configuration is unverified. `store: false` for recognition is not equivalent to ZDR; generation currently uses `store: true`. Confirm provider eligibility and compatible operation before serving these users. Do not silently replace the agreed all-ages audience with a 13+ restriction.
- Update the page's remaining retention qualifications when the corresponding arrangements are established and verified. Keep the same URL.

Owner/contact supplied by the operator: Matthew Hughes, 12hughesm@gmail.com.

## Content evidence

Content checked against the app's Supabase account/deletion schema, OpenAI recognition and generation requests, PostHog configuration and RevenueCat integration on 20 September 2026. Those implementation details establish data flows, not a claim of production compliance or verified deployed configuration.

Reference guidance:

- [ICO: children and the UK GDPR](https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/childrens-information/children-and-the-uk-gdpr/)
- [Apple: privacy guidelines](https://developer.apple.com/app-store/review/guidelines/#privacy)
- [Apple Standard EULA](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/)
- [OpenAI API data controls](https://developers.openai.com/api/docs/guides/your-data)
- [OpenAI under-18 guidance](https://developers.openai.com/api/docs/guides/safety-checks/under-18-api-guidance)

## Editing

Edit `index.html` and `styles.css`, then commit and push to `main`. Review factual claims against the actual service before changing the policy. No application code, credentials, customer records or private screenshots belong in this repository.
