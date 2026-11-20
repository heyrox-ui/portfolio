# heyrox

A responsive marketing and automation portfolio targeting US real estate agents and small teams.

## What's included
- Meta Ads, organic social media, and GHL/n8n automation services
- Lead-to-follow-up concept workflow
- About section and consultation contact section
- Google Forms embed integration (configuration ready; **not live until form URL is added**)

## Connect Google Forms
1. Sign in at https://forms.google.com using **roxanneligason@gmail.com**.
2. Create a form named **Project Rox | Consultation Request** with:
   - Full Name (required)
   - Business Email (required, email validation)
   - Brokerage / Business Name (optional)
   - Website (optional)
   - Services needed (checkboxes: Meta Ads, Organic Social, CRM, Automation, Full Growth System)
   - Biggest challenge (paragraph, optional)
   - Consent to be contacted about the inquiry (required)
3. Link responses to a Google Sheet using the form's **Responses** tab, and turn on new-response notifications.
4. Publish the form for external respondents. Avoid requiring Google sign-in.
5. Obtain the **Embed HTML** and copy the `src` URL, beginning `https://docs.google.com/forms/d/e/` and containing `/viewform`.
6. In this repository, edit `form-config.js` and set `window.ROX_GOOGLE_FORM_EMBED_URL` to the published embed URL.
7. Test from a private/incognito window and confirm the submission arrives in the linked Sheet.

Never put passwords, private credentials, or client data in this public repository. Add a clear privacy notice to the form. Do not add inquiry contacts to marketing sequences without appropriate consent.

## Deployment
Source files: `index.html` and `form-config.js` (no build step).

GitHub Pages may serve personal portfolio showcases: in repository Settings → Pages → Deploy from branch → `main` → `/(root)`. Review GitHub's Pages acceptable-use limits before using it as a primarily commercial business site. Cloudflare Pages can host the same static files on a free tier if needed.

**Current status:** Website source exists in GitHub. Contact form not connected, and public deployment not verified.
