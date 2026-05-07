# ReviveWell — Cohort Landing Page

Static HTML landing page for the Founding Cohort, deployable to GitHub Pages.

## Files

- `index.html` — main landing page
- `application.html` — application form
- `README.md` — this file

## Deploy to GitHub Pages

1. Create a new repo (e.g., `revivewell-cohort-site`)
2. Push these files to the `main` branch
3. Repo → Settings → Pages → Source: `Deploy from a branch` → Branch: `main`, folder `/ (root)`
4. Add a custom domain (e.g., `cohort.revivewell.co`) in the Pages settings, then update DNS:
   - CNAME `cohort` → `<username>.github.io`
5. Enforce HTTPS (checkbox in Pages settings) once DNS resolves

## Wire up forms

Both pages contain a `// TODO` comment where you wire up real form submission. Recommended options:

| Option | Best for | Notes |
|---|---|---|
| **Formspree** | Fastest setup | Replace `YOUR_ENDPOINT` with your Formspree URL |
| **Netlify Forms** | If you ever migrate to Netlify | Add `netlify` attribute to `<form>` |
| **Zapier webhook → CRM** | Connecting to ConvertKit/Charm | Use webhook trigger, parse JSON, route to email tool + Charm |
| **Custom endpoint** | Full control | Build minimal API or use Cloudflare Worker |

### Recommended setup: Zapier flow

1. Form submission → Zapier webhook
2. Zapier → Add to ConvertKit/Klaviyo (tag: `cohort_application`)
3. Zapier → Send Slack/email notification to admin
4. Zapier → Create Charm patient record (if integration available) OR add to Notion applicant database

## Customize

- Brand colors: edit `:root` CSS variables at the top of each file
- Fonts: Fraunces (display) + Inter (body), loaded from Google Fonts
- Copy: search for `<!--` and replace placeholder text
- Images: SVG hero illustration is inline — replace with photography by swapping the `.hero-visual svg` block

## SEO checklist before launch

- Update `<title>` and meta description tags
- Replace placeholder open graph image (add `og:image` meta tag with hosted URL)
- Submit sitemap to Google Search Console
- Add `robots.txt` if needed
- Add Google Analytics or Plausible tracking script before `</body>`

## Compliance notes

- Medical disclaimer is included in the footer of `index.html`
- No outcome guarantees in copy
- GLP-1/peptide language is positioned as wellness/optimization, not disease treatment
- Run final copy review with legal/compliance counsel before launch
