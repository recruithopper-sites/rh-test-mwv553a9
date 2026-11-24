# Testco Recruiting Website

Recruiting website for Testco Recruiting (warehouse and logistics, hourly). Live at https://rh-test-mwv553a9.sites.recruithopper.com (GitHub Pages). Created with Recruit Hopper on November 24, 2026.

## Editing without a computer setup

Everything can be edited right on GitHub:

1. Open a file (e.g. `index.html`) and click the pencil icon.
2. Make your change and click **Commit changes**.
3. The live site updates automatically in about a minute.

## Common edits

| What | Where |
|---|---|
| Legal name, email, phone, address | `script.js`, the `SITE` block at the top, **and** the same text in `index.html`, `privacy.html` and `terms.html` |
| Page text | `index.html` |
| Colors, fonts, spacing | `styles.css` |
| Logo | `assets/logo.png` (replace with a file of the same name) |

## 10DLC / A2P SMS compliance

The site includes what carriers and The Campaign Registry check for:

- **Opt-in on the contact form**: two separate, optional, unchecked checkboxes (recruiting/account texts and job alerts/promotional texts) with brand name, frequency, "Msg & data rates may apply", HELP/STOP, and a "not a condition of service" note.
- **Privacy Policy** (`privacy.html`) with the required "no mobile information will be shared with third parties" language.
- **SMS Terms & Conditions** (`terms.html`) with program description, frequency, rates, STOP/HELP, carrier disclaimer and contact info.
- **Business contact info** in the contact section and on both legal pages.

The legal name must match your registered brand exactly: **Testco Recruiting LLC**.

Campaign fields you can paste into Telnyx:

- **Website**: https://rh-test-mwv553a9.sites.recruithopper.com
- **Privacy Policy URL**: https://rh-test-mwv553a9.sites.recruithopper.com/privacy.html
- **Terms URL**: https://rh-test-mwv553a9.sites.recruithopper.com/terms.html
- **Opt-in workflow**: Users opt in via the contact form at https://rh-test-mwv553a9.sites.recruithopper.com/#contact by checking an optional, unchecked SMS consent checkbox and providing their mobile number. Disclosures include brand name, message frequency, msg &amp; data rates, HELP/STOP, and links to the Privacy Policy (https://rh-test-mwv553a9.sites.recruithopper.com/privacy.html) and Terms (https://rh-test-mwv553a9.sites.recruithopper.com/terms.html).
- **Sample message 1**: Testco Recruiting: Hi {name}, your interview with {company} is confirmed for {date} at {time}. Reply STOP to opt out.
- **Sample message 2**: Testco Recruiting: New warehouse and logistics role in {city}: {title}. Interested? Reply YES and we will reach out. Reply STOP to opt out, HELP for help.
- **HELP reply**: Testco Recruiting: For help, email test@example.com or call (555) 555-0100. Msg &amp; data rates may apply. Reply STOP to opt out.
- **STOP reply**: Testco Recruiting: You have been unsubscribed and will receive no further messages. Reply START to resubscribe.
- **Opt-in confirmation**: Testco Recruiting: Thanks for subscribing to recruiting updates. Msg frequency varies. Msg &amp; data rates may apply. Reply HELP for help, STOP to opt out.
