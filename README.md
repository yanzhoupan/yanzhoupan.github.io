# yanzhoupan.github.io

Personal website of **Yanzhou Pan** — Senior Research Engineer at Google, working on agentic AI, data valuation, and trustworthy large language models.

Built with [al-folio](https://github.com/alshedivat/al-folio) (Jekyll) and deployed to GitHub Pages at <https://yanzhoupan.github.io/>.

## Pages

- **About** — bio, avatar, contact links, recent news, and the complete publication list: `_pages/about.md`
- **Experience** — work experience and education: `_pages/experience.md` + `_data/cv.yml`

Contact details sit at the top of the About page, so there is no separate Contact page, and the small publication list lives directly on About instead of a dedicated tab. The site supports light and dark themes only.

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
