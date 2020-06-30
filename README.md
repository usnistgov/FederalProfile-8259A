# 8259 Catalog

This repository is for development of _Recommendations for IoT Device Manufacturers: Catalog of Device Capabilities_.

## Editing

Core document sections are in `_Nontechnical` and `_Technical` markdown files, and frontmatter sections are in `_Frontmatter`.

## Viewing

To view a rendered copy of the site locally, run `docker-compose up` in the project root directory, then direct your browser to <http://localhost:4000/8259-Catalog/>.

To render a PDF of the document, run `docker-compose -f docker-compose-pdf.yml up` in the project root directory. If successful, this will render to `_pdf/8259-Catalog/8259-Catalog.pdf`.
