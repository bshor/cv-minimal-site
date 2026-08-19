# Minimal CV website

This is a stripped-down starter for a one-page Quarto website that links directly to a PDF CV. It contains no instructor biography, publications, teaching pages, images, sample CV, or HTML-CV machinery. It is used in POLS 6394, Social Science Computation and Data Science.

## Attribution

This starter was adapted and greatly simplified by [Boris Shor](https://github.com/bshor) from [Gang He's Quarto Academic Website Template](https://github.com/drganghe/quarto-academic-website-template), the MIT-licensed upstream template for Boris's academic site. The original copyright and license are preserved in `LICENSE`, which also identifies Boris's 2026 modifications.

## Make it yours

1. Rename the repository to `yourusername.github.io`.
2. Replace the name, subtitle, paragraph, email address, and GitHub URL in `index.qmd`.
3. Replace `Your Name` in `_quarto.yml`.
4. Put your rendered PDF CV at `files/cv.pdf`.
5. Run `quarto render`.
6. Commit and push the source files and the generated `docs/` folder.
7. In GitHub **Settings → Pages**, publish the `docs/` folder on the `main` branch.

There is intentionally no HTML CV. The website links directly to the PDF produced by the separate `quarto-cv` project.
