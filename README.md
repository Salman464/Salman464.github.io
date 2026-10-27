# Salman464.github.io

Source for my personal portfolio and resume site, hosted on GitHub Pages.

**Live:** https://salman464.github.io/portfolio/
**Resume:** https://salman464.github.io/resume/

## What's on the site

A single-page portfolio with these sections: Home, About, Services, Work, Contact, plus a separate resume page.

- **About:** background as a software engineer focused on Rails backends, APIs, and automated testing
- **Services:** backend development, API development, website optimisation, test automation, frontend development
- **Work:** project pages, each with its own page:
  - Game Districts, a Shopify integration dashboard (Ruby on Rails, Shopify API)
  - EasyLlama, a reporting platform (backend development, test automation)
  - TapScan, an inventory platform (Rails, Shopify, Amazon SP-API)
  - E-Wave, a taxi platform (Laravel, backend)
- **Testimonials** from clients
- **Contact** form and links

## Tech

Static site: HTML, CSS and JavaScript, served directly by GitHub Pages. No build step.

## Run locally

```
git clone https://github.com/Salman464/Salman464.github.io.git
cd Salman464.github.io
python3 -m http.server 8000
```

Then open http://localhost:8000/portfolio/.

## Deploying

Pushing to the default branch publishes the site automatically through GitHub Pages.
