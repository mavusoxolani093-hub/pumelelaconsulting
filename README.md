# Pumelela Consulting Solutions

A responsive React website for Pumelela Consulting Solutions, built with Vite. Its layout and motion take direction from the Retro Rabbit reference supplied by the client, while the content and logo are Pumelela's. The three editorial images are generated illustrations of the subject matter; they do not depict actual Pumelela staff, offices or clients.

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
- Five service areas, three standards, delivery process, company overview, values, vision and mission
- Generated editorial images and scroll reveal animations with reduced-motion support
- Frequently asked questions
- Validated consultation form and downloadable enquiry
- Search metadata and branded SVG favicon

## Contact form

No business email address or form-delivery service was provided. The form validates inputs and creates a downloadable text enquiry. It does **not** transmit submissions or store personal information. The interface states this explicitly and never reports that a message was sent. Before launch, provide a verified contact address and connect an approved form endpoint if direct delivery is needed. Never put private API keys in client-side code.

Generated scenes are illustrative and do not establish staff membership, client relationships or completed engagements. No client statistics, certifications held, testimonials, addresses or phone numbers have been invented.
