# Architecture 2.0 — IISWC 2026

Static workshop and tutorial website. No dependencies or build step.

## Local preview

Run `python3 -m http.server 8000` in this directory and visit http://localhost:8000.

## Editing

- `index.html`: event details, tentative schedule, resources, and organizers.
- `styles.css`: responsive styling.
- `images/`: organizer photos reused from the organizer-owned ISCA 2026 website, with Zishen Wan’s updated portrait supplied by the organizer.
- `favicon.png`: existing Architecture 2.0 favicon.

The schedule follows the organizer’s supplied draft. Keynote speaker and title remain TBD.
Date, venue, and room were checked against the official IISWC 2026 program and venue pages on September 14, 2026 (UTC).
The public IISWC description still includes a submission invitation; this site follows the organizer’s updated tutorial-only format.

## GitHub Pages

The site uses relative local asset paths and is ready to serve from the root of the `main` branch. `.nojekyll` keeps the site buildless. Configure GitHub Pages to serve from the root of the `main` branch when ready to publish.

## Source references

- https://iiswc.org/iiswc2026/program.html
- https://iiswc.org/iiswc2026/venue.html
- https://harvard-edge.github.io/isca-26-arch-2-workshop/

Keynote recommendations are kept separately from this public website.

## Organizer updates

Zishen Wan is listed with Columbia University; Ankita Nayak is listed with Gimlet Labs, as supplied by the organizer. The public footer has no contact information. Full talk titles were supplied by the organizer.

## Resource list

Resources are grouped into books and guides, papers, perspectives, benchmarks and datasets, tools, and courses/community. The list draws from the ISCA 2026 workshop and the Architecture 2.0 book resource pages, checked September 14, 2026. Book metadata follows its current title: Principles of AI-Native System and Chip Design. The QuArch session label is QuArch & Archipedia, as requested.
