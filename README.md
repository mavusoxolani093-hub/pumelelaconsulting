# Pumelela Consulting Solutions

A responsive React website for Pumelela Consulting Solutions, built with Vite. The visual direction follows the supplied brand gallery's colour palette and identity. The site uses a custom animated brand composition in place of staged imagery; company content comes from the supplied business profile.

## Develop

Requires Node.js 20.19+ or 22.12+ (validated with Node.js 24).

```sh
npm ci
npm run dev
```

## Production

```sh
npm run build
npm run preview
```

Deploy the generated `dist/` directory to a static host. Assets and fonts are bundled locally; no external font or image service is required.

## Website features

- Responsive, accessible navigation and keyboard focus styles
- A ten-part narrative covering the challenge, transformation, services, standards, approach, vision and values
- Five detailed service areas and three standards
- Scroll-triggered motion, a reading progress indicator and reduced-motion support
- Frequently asked questions
- Validated consultation form and downloadable enquiry
- Search metadata and branded SVG favicon

## Contact form

No business email address or form-delivery service was provided. The form validates inputs and creates a downloadable text enquiry. It does **not** transmit submissions or store personal information. The interface states this explicitly and never reports that a message was sent. Before launch, provide a verified contact address and connect an approved form endpoint if direct delivery is needed. Never put private API keys in client-side code.

Brand-gallery scenes are illustrative brand assets, not evidence of an office, staff membership, client relationships or completed engagements. No client statistics, certifications held, testimonials, addresses or phone numbers have been invented.
