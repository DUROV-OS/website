# DUROV.HOUSE

Static redesign of the DUROV.HOUSE website, published with GitHub Pages.

## Local preview

```sh
python3 -m http.server 4173 --bind 127.0.0.1 --directory dist
```

Main page: http://127.0.0.1:4173/
Catalog: http://127.0.0.1:4173/#/catalog

## Deployment

The workflow in `.github/workflows/pages.yml` validates JavaScript and deploys `dist/` on pushes to `main`. Select **GitHub Actions** as the Pages source in repository settings.

## Website

The site preserves Rubik, the original green palette, catalog photography and floor plans. It contains a 10-stage scroll-driven production visualization, the original Marquiz quiz in a modal, a 3D bestseller carousel (DH 27, DH 64, DH 93), architecture/area filters, sorting and project details.

3D models are procedural visual reconstructions from published plans and photographs. They are not manufacturer CAD models. Geometry, materials, glazing and terrace details are approximate. Production animation is an explanatory schematic, not a construction specification.

Catalog information is stored in `dist/data.json`. Prices, dimensions and options must be confirmed for a production release. Contact actions use the company's original public phone, email and Telegram account. Marquiz remains hosted by its existing provider. No new lead-processing backend is included.
