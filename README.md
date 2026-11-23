# KESA — Klotzek Executive Support Advisory

A responsive, no-build, multi-page static website ready for Netlify.

## Pages
- `index.html` — Home
- `services/index.html` — Services
- `about/index.html` — About
- `results/index.html` — Results & Impact
- `contact/index.html` — Contact with a Netlify Forms form
- `thank-you/index.html` — Form success page
- `privacy/index.html` — Basic privacy notice; review for your actual practices

## Deploy to Netlify
1. Back up your existing site and note the settings for domain, DNS, existing redirects, and forms.
2. Unzip the bundle. Netlify → Sites → Add new project → Deploy manually (drag the project directory) OR push the folder to a Git repository and connect that repository to Netlify.
3. If connecting to Git, set **build command** to blank and **publish directory** to `.`. If using a subfolder, set Netlify's base directory to that subfolder.
4. On your new/updated site, verify the domain `www.klotzekadvisory.com` and HTTPS. Make sure a competing deployment does not own the custom domain.
5. Submit a test inquiry from `/contact/` on the deployed site. Netlify Forms processes submissions from deployed HTML forms. Configure verified notification recipients/spam filtering in Netlify dashboard.
6. Confirm the legacy pages, redirects, mobile navigation, analytics, SEO and accessibility. Only then switch production traffic.

## Before publishing
- Validate the **four historical results metrics** presented on the site, and remove or revise any that cannot be substantiated; they are marked as historical leadership outcomes, not client guarantees.
- Review About biography and any role labels for precise accuracy.
- The contact form collects contact data. Align the privacy page with actual retention, form handling, analytics and any third-party services. Obtain legal review if needed.
- This bundle uses Google Fonts (Manrope and DM Sans) loaded from Google's servers. To avoid that external request, replace with system fonts or self-host appropriately licensed fonts.
- No Calendly URL or phone number is invented. Add your existing booking link where desired (buttons currently go to the contact page).
- The site uses an original CSS vector composition rather than unlicensed stock imagery.

## Editing
- Brand colors and typography: `assets/styles.css` under `:root`.
- Footer and site navigation are duplicated per static HTML page. Edit all pages when changing global content.
- Contact form: `contact/index.html`.
- Canonical domain, sitemap and robots are set to `www.klotzekadvisory.com`.

## Technical
No package installation, command line build, or API keys needed. Accessible mobile menu, SEO metadata, canonical URLs, JSON-LD organization schema (home), XML sitemap, and basic security headers are included.
