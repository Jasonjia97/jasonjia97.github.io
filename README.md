# Jason Jia — Portfolio

A static Jekyll portfolio published as the GitHub user site `jasonjia97.github.io`. GitHub Pages builds directly from the `main` branch and repository root.

## Update the site

- Edit `index.md`, `about.md`, `work-experience.md`, and `contact.md` to update page content. Each page uses YAML front matter and Markdown.
- Change navigation labels or paths in `_config.yml`.
- Update colors, spacing, and responsive styles in `assets/css/styles.css`.
- Replace `assets/images/favicon.svg` to use a different favicon.
- Keep personal contact details private unless you explicitly want them published. The current Contact page links to LinkedIn and GitHub only.

## Preview locally

Install Ruby and Bundler, then run:

```sh
bundle install
bundle exec jekyll serve
```

Open `http://127.0.0.1:4000`. Jekyll watches the files and rebuilds as you edit.

## Check responsive layouts

Use your browser's developer tools to preview the site at 375px and 1280px viewport widths. Check that the navigation wraps cleanly, text remains readable, and links are usable by keyboard.

## Run Lighthouse

With the local preview running, open Chrome DevTools, select the **Lighthouse** panel, choose Performance, Accessibility, Best Practices, and SEO, then run an analysis for both mobile and desktop. The target is 90 or higher in each category.

## GitHub Pages

1. Create or use the `Jasonjia97/Jasonjia97.github.io` repository.
2. Commit the contents of this repository to its `main` branch.
3. In the repository's **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, and save.

The site uses only the `github-pages` Ruby gem for local preview. It does not require a separate build step, backend, database, framework, or client-side package manager when published with GitHub Pages.