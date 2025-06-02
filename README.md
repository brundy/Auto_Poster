# Auto_Poster

Auto_Poster is a tool for automating posts to various social media platforms.

## GitHub Pages Site

This repository includes a GitHub Pages site with the following pages:

- [Homepage](https://brundy.github.io/Auto_Poster/) - Overview of Auto_Poster and its features
- [Privacy Policy](https://brundy.github.io/Auto_Poster/privacy/privacy.md) - Detailed privacy policy for Auto_Poster

**Note:** The content for the GitHub Pages site is in the `gh-pages` directory, not in this README.md file. Changes to this README.md file won't affect the GitHub Pages site. To update the GitHub Pages site, you need to modify the files in the `gh-pages` directory.

**Important:** When accessing the GitHub Pages site, use the URL https://brundy.github.io/Auto_Poster/ (without index.html). The URL https://brundy.github.io/Auto_Poster/index.html will result in a 404 error because GitHub Pages is configured to serve the index.md file directly.

### Local Development

The GitHub Pages site is located in the `gh-pages` directory. To preview the site locally:

1. Install [Jekyll](https://jekyllrb.com/docs/installation/)
2. Open a terminal application
3. Navigate to the `gh-pages` directory using the `cd` command
4. Run Jekyll from the terminal:
   - If you installed Jekyll with Bundler: `bundle exec jekyll serve`
   - If you installed Jekyll with Homebrew: `jekyll serve`
5. Open your browser to `http://localhost:4000`

Note: Jekyll is a command-line tool and must be run from a terminal application.

### Deployment

The site is automatically deployed to GitHub Pages when changes are pushed to the main branch.
