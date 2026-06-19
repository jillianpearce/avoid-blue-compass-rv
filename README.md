# Avoid Blue Compass RV website

This is a simple static website for `www.avoidbluecompassrv.com`.

## What to edit first

1. Open `index.html` and replace any wording you want softened or expanded.
2. Open `timeline.html` and add exact dates.
3. Put redacted PDFs in the `docs` folder.
4. Put web-safe photos in the `images` folder.
5. Replace placeholder links in `documents.html`.
6. Replace the email address in `contact.html`.

## Recommended file names

- `docs/purchase-paperwork-redacted.pdf`
- `docs/pre-delivery-repair-redacted.pdf`
- `docs/insurance-determination-redacted.pdf`
- `docs/correspondence-redacted.pdf`

## Redaction reminders

Do not publish:
- home address
- personal phone numbers
- personal email addresses unless you want them public
- VIN, except maybe last 4 if needed
- account or loan numbers
- signatures
- driver's license info
- minor's information
- insurance claim numbers unless needed and reviewed

## GitHub Pages setup

1. Create a GitHub account if needed.
2. Create a new public repository, for example: `avoid-blue-compass-rv`.
3. Upload all files from this folder into the repository.
4. Go to repository Settings → Pages.
5. Under Build and deployment, choose:
   - Source: Deploy from a branch
   - Branch: main
   - Folder: /root
6. In Custom domain, enter:
   `www.avoidbluecompassrv.com`
7. Save.
8. After DNS is working, enable Enforce HTTPS.

## Namecheap DNS setup

In Namecheap:
1. Go to Domain List.
2. Click Manage next to `avoidbluecompassrv.com`.
3. Go to Advanced DNS.
4. Add these A records for the root domain:

| Type | Host | Value |
| --- | --- | --- |
| A Record | @ | 185.199.108.153 |
| A Record | @ | 185.199.109.153 |
| A Record | @ | 185.199.110.153 |
| A Record | @ | 185.199.111.153 |

5. Add this CNAME record:

| Type | Host | Value |
| --- | --- | --- |
| CNAME Record | www | YOUR-GITHUB-USERNAME.github.io |

Replace `YOUR-GITHUB-USERNAME` with your actual GitHub username.

DNS can take a little while to update.

## Safety note

Stick to factual statements, dates, direct quotes, documents, and your personal experience.
Avoid accusations like fraud/scam/criminal unless an attorney specifically advises that language.
