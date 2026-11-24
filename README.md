# {{BRAND_NAME}} Website

Recruiting website for {{BRAND_NAME}} ({{RECRUITING_FOCUS}}). Live at https://{{DOMAIN}} (GitHub Pages). Created with Recruit Hopper on {{TODAY}}.

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
| Logo | `assets/{{LOGO_FILE}}` (replace with a file of the same name) |

## 10DLC / A2P SMS compliance

The site includes what carriers and The Campaign Registry check for:

- **Opt-in on the contact form**: two separate, optional, unchecked checkboxes (recruiting/account texts and job alerts/promotional texts) with brand name, frequency, "Msg & data rates may apply", HELP/STOP, and a "not a condition of service" note.
- **Privacy Policy** (`privacy.html`) with the required "no mobile information will be shared with third parties" language.
- **SMS Terms & Conditions** (`terms.html`) with program description, frequency, rates, STOP/HELP, carrier disclaimer and contact info.
- **Business contact info** in the contact section and on both legal pages.

The legal name must match your registered brand exactly: **{{LEGAL_NAME}}**.

Campaign fields you can paste into Telnyx:

- **Website**: https://{{DOMAIN}}
- **Privacy Policy URL**: https://{{DOMAIN}}/privacy.html
- **Terms URL**: https://{{DOMAIN}}/terms.html
- **Opt-in workflow**: {{OPT_IN_WORKFLOW}}
- **Sample message 1**: {{SAMPLE_MESSAGE_1}}
- **Sample message 2**: {{SAMPLE_MESSAGE_2}}
- **HELP reply**: {{HELP_REPLY}}
- **STOP reply**: {{STOP_REPLY}}
- **Opt-in confirmation**: {{OPT_IN_REPLY}}
