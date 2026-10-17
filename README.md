# Abuja Properties Hub — starter website

A responsive static website concept for connecting Abuja landlords/agents with people looking to rent or buy properties.

## Included
- `index.html` — complete single-page website, styling and filtering JavaScript in one file.
- Rent/buy filters, area filter and keyword search.
- Responsive layout for mobile and desktop.
- WhatsApp enquiry links for **+234 813 727 2792**.
- Sample listing cards clearly marked as samples; no fake live prices are claimed.

## Before launch
1. Replace sample listings with real properties you have permission to advertise.
2. Add accurate prices, images, contact/agency information and availability.
3. Review the disclaimer and local legal/privacy requirements.
4. Test every WhatsApp link and the search filters on mobile and desktop.

## Deploy with GitHub + Cloudflare Pages
1. Create a GitHub repository named `abuja-properties-hub`.
2. Upload `index.html` and `README.md` to the repository root.
3. In Cloudflare, open **Workers & Pages** (or **Pages**, depending on dashboard layout) and create a Pages project connected to Git.
4. Select the repository and production branch (`main`).
5. For this plain HTML site, leave the build command blank and set the output directory to `/` or the repository root as accepted by the dashboard.
6. Deploy. Cloudflare will provide a `*.pages.dev` URL.
7. Test the deployed site and connect a custom domain later if desired.

## WhatsApp link
The site uses `https://wa.me/2348137272792` with pre-filled messages. The international number format excludes the leading `+`.
