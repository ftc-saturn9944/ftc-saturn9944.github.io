# Saturn 9944 Website

2025 rework of the Saturn9944 website using mkdocs.

## Development Setup

1. [Install uv][uv]
   following the official documentation.
2. Run `uv sync` to install dependencies.

## Updating the site

The vast majority of changes to the website can be handled by updating the
existing files under `docs/` to add new content.  Doing so requires some
knowledge of [Markdown][md] to get formatting
working.  If you are familiar with how to format text in Discord or Github then
you already know the basics.

If you need to add new pages or change the navigation settings you will have to
look in `./mkdocs.yml`.  Information about how to modify the settings can be
found on the [mkdocs][mkdocs] website.  Theme specific
information can be found on [mkdocs-material][mkdocs-material] and information
on how to manipulate images on the page at [mkdocs-glightbox][mkdocs-glightbox]

1. Run `uv run mkdocs serve` to get the live reload functionality of MKDocs to
   work.
2. In your browser go to http://localhost:8000 to view the website.  When you
   save changes to the pages under `docs/` the website will pick up the changes
   allowing you to see the results.

## Useful Links
These are included in the text above but are gathered here for ease of lookup

- [uv][uv]
- [markdown][md]
- [mkdocs][mkdocs]
- [mkdocs-material][mkdocs-material]
- [mkdocs-glightbox][mkdocs-glightbox]

  [uv]: https://docs.astral.sh/uv/getting-started/installation/
  [md]: https://www.markdownguide.org/
  [mkdocs]: https://www.mkdocs.org/
  [mkdocs-material]: https://squidfunk.github.io/mkdocs-material/
  [mkdocs-glightbox]: https://blueswen.github.io/mkdocs-glightbox/
