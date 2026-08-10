# swiftform-legal

Static legal pages for SwiftForm, served via GitHub Pages.

- `index.html` — Privacy Policy
- `data-deletion.html` — Data Deletion Instructions

## Publishing

Repo must be **public** for GitHub Pages on a free plan.

Settings → Pages → Source: *Deploy from a branch* → Branch: `main`, folder: `/ (root)`.

URLs after deploy (~1 min):

- Privacy Policy: `https://<user>.github.io/swiftform-legal/`
- Data Deletion: `https://<user>.github.io/swiftform-legal/data-deletion.html`

## Where these go in the Meta App Dashboard

App Dashboard → Settings → Basic:

- **Privacy Policy URL** → the privacy policy URL above
- **User Data Deletion** → *Data Deletion Instructions URL* → the data deletion URL above

## Before going live

- Confirm `support@swiftform.co.za` exists and is monitored — both pages route all requests there.
- Confirm the dashboard really has **Settings → Account → Delete account**; if not, either build it or reword that section to email-only.
- Have a lawyer review before you take real customer data.
