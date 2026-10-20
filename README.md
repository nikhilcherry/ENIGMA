# ENIGMA

Website work for **ENIGMA**, an event run by the Entrepreneurship Cell at NMIT.

This is an early-stage project (September 2025) and is kept as a record rather than maintained.

## What is in here

| Folder | What it is |
| --- | --- |
| `enigma/` | The event landing page: `index.html` plus its `css/`, `js/`, `images/` and `assets/` |
| `ecellmirror/` | A Scrapy spider (`scrapy.cfg`) that mirrors the E-Cell NMIT site so its content could be reused |
| `site/` | The mirrored pages, cleaned up so they can be browsed offline |
| `social media pictures/` | Poster and social-media artwork |

## Run it

The landing page is static:

```bash
cd enigma
python3 -m http.server 8000     # http://localhost:8000
```

To re-run the scraper (needs `pip install scrapy`):

```bash
cd ecellmirror
scrapy crawl ecell
```

The scraped content belongs to its original site owners; it is here only as reference material for the redesign.
