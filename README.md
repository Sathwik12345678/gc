# GrowClinic Homepage Redesign

A responsive React + Vite homepage concept based on the existing GrowClinic website and the requested section-by-section redesign.

## Run locally

1. Install Node.js (18+ recommended).
2. Extract this ZIP.
3. Open a terminal in the project folder.
4. Run:

   ```bash
   npm install
   npm run dev
   ```

5. Open the local URL printed by Vite (usually http://localhost:5173).

To create a production build:

```bash
npm run build
npm run preview
```

## Important customisation notes

- **Logo:** The header attempts to load the existing site logo from `https://www.growclinic.io/images/logo.png`. If it is unavailable, a text-based GrowClinic fallback is shown. To make the logo fully local, download the approved logo and replace the image URL in `src/main.jsx` with `/images/growclinic-logo.png`.
- **Photography:** The IVF, cosmetology and trichology speciality cards use supplied images from `public/images`; the other speciality cards use remote Unsplash image URLs as visual placeholders.
- **Client logos:** The client section uses the supplied Bedi Medicose, Esthetique Le Divine, VHCA Hair and Skin Clinic, and Qurederma logo assets. An unidentified generic icon is intentionally omitted.
- **Case studies:** The three campaign examples use the figures published on the existing GrowClinic homepage. Messaging conversations are explicitly not represented as confirmed patients or appointments.
- **Audit:** The on-page priority selector provides general starting points only; it does not calculate a score or collect details. The full audit CTA continues to the existing `https://audit.growclinic.io/` experience.
- **Contact:** Email and WhatsApp links use the contact details published on the existing website.
- **Technology marks:** The technology row uses typographic marks as placeholders. Replace with official SVG logos and confirm actual platform usage/relationships before launch.
- **No pricing section or prices** are included.

## Stack

- React 18
- Vite 6
- Framer Motion
- Lucide React
- Custom responsive CSS

## Production checklist

- Confirm permissions for the supplied client logos.
- Replace remote photography with licensed/approved local assets.
- Confirm logo source and localise it.
- Confirm all testimonials and case study permissions.
- Test the audit flow and all external links.
- Test mobile, tablet and desktop breakpoints.
- Run Lighthouse and accessibility checks.
