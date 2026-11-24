# Endless website

Marketing site for **Endless**, the flat-rate design subscription. It's exported from the Endless Design canvas and published with GitHub Pages.

- `index.html`: home page (hero, services, work, how it works, pricing, reviews, FAQ, team, footer)
- `*.dc.html`: the other pages (Pricing, Work, How it works, About, Reviews, FAQ, Contact, Book a call, Blog, Branding, Logo design, case studies)
- `assets/`: images and logo marks
- `_runtime/`: the small script bundle that renders the pages in the browser

## Run locally

```
python3 -m http.server
```

Then open http://localhost:8000. If you open the files straight from disk, the scripts won't run.
