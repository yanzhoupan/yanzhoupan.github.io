# yanzhoupan.github.io

Personal website of **Yanzhou Pan** — Senior Research Engineer at Google, working on trustworthy large language models, data valuation, and agentic AI systems.

Built with [al-folio](https://github.com/alshedivat/al-folio) (Jekyll) and deployed to GitHub Pages at <https://yanzhoupan.github.io/>.

## Pages

- **About** — professional bio and recent news: `_pages/about.md`
- **Experience** — work and research experience: `_pages/experience.md` + `_data/cv.yml`
- **Publications** — papers and preprints: `_bibliography/papers.bib`
- **Contact** — email and professional links: `_pages/contact.md`

The site intentionally uses no personal photos. The favicon is a simple monogram.

## Local development

Requires Ruby 3.3 and Bundler.

```bash
bundle install
bundle exec jekyll serve --livereload
```

Open <http://localhost:4000>.

## Deployment

This repository deploys through GitHub Actions:

1. In **Settings → Pages → Build and deployment**, set **Source** to **GitHub Actions**.
2. Push changes to `master` (or run the **Deploy site** workflow manually).
3. The workflow builds the Jekyll site and publishes it to GitHub Pages.

The legacy version of the site is preserved in the local `legacy-site` branch and in the repository history.

## Credits

Theme: [al-folio](https://github.com/alshedivat/al-folio), MIT License.
