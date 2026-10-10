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

The site preserves Rubik, the original green palette, catalog photography and floor plans. It contains a scroll-driven production visualization (01–02 combined, through 11 Ready), a native six-question house-selection quiz in a modal, a 3D bestseller carousel (DH 27, DH 64, DH 93), architecture/area filters, sorting and project details.

3D models are procedural visual reconstructions from published plans and photographs. They are not manufacturer CAD models. Geometry, materials, glazing and terrace details are approximate. Production animation is an explanatory schematic, not a construction specification.

Catalog information is stored in `dist/data.json`. Prices, dimensions and options must be confirmed for a production release. Contact actions use the company's original public phone, email and Telegram account. The quiz runs locally, recommends catalog models, and prepares an email with the visitor’s answers. No lead-processing backend is included.

## Animation and archives

The production timeline includes stored materials, 20 floor/ceiling tile batches, facade panels arriving from the sides, stairs at completion, opening doors and a landscaped completion scene. Menu navigation jumps immediately. The catalog displays all three bestseller models simultaneously.

Uploaded archives were inspected locally. Convertible SketchUp samples have different dimensions/plans from the three bestseller models, so they were not substituted. BIMx files contain proprietary geometry and useful preview references. Raw archives and research stay excluded from the public repository.

## Landscape assets

Poly Haven CC0 assets: [Tree Small 02](https://polyhaven.com/a/tree_small_02) by Rico Cilliers and [Leafy Grass](https://polyhaven.com/a/leafy_grass). Tree geometry simplified for the web while preserving UVs; leaf alpha mask restored, textures packed into WebP. [License](https://polyhaven.com/license). The scene has no people or crane.

3D-модели: PBR-дерево [Synthetic Wood](https://polyhaven.com/a/synthetic_wood), Poly Haven, CC0. Модели дополнены водостоками, оконной фурнитурой, фактурной облицовкой и меблированными помещениями. Кнопка «Интерьер» включает разрез с автоматическим скрытием ближайших стен при вращении.
