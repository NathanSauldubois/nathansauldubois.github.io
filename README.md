# Nathan Sauldubois Academic Website

This repository contains a minimal Jekyll website for GitHub Pages.

## Site Structure

- `index.md`: About page and homepage.
- `cv.md`: CV page with a link to `files/cv.pdf`.
- `articles.md`: Publications and preprints.
- `teaching.md`: Teaching interests and experience.
- `repositories.md`: Selected GitHub repositories.
- `contact.md`: Contact and profile links.
- `_data/navigation.yml`: Main navigation menu.
- `_config.yml`: Site metadata and Jekyll configuration.
- `assets/css/style.css`: Minimal academic styling.

## Editing Pages

Edit the Markdown files in the repository root to update page content. Each page has a short YAML header at the top that controls the title, layout, and URL.

## Adding or Replacing the CV

Place the current CV PDF at:

```text
files/cv.pdf
```

The CV page links to this file with the text "Download CV".

## Adding Articles

Edit `articles.md` and add new entries to the article list. Keep each entry in a consistent format:

- title
- authors
- year
- venue
- link
- short description

## Adding GitHub Repositories

Edit `repositories.md` and replace the placeholder repository names and links with active GitHub repositories.

## Running Locally

Install Ruby 3 and Bundler, then run:

```bash
bundle install
bundle exec jekyll serve
```

Open the local URL printed by Jekyll, usually `http://127.0.0.1:4000`.

## Deploying with GitHub Pages

1. Push this repository to GitHub.
2. In the repository settings, open "Pages".
3. Set the source to deploy from the main branch.
4. Select the root folder.
5. Save the settings.

GitHub Pages will build and publish the site automatically.
