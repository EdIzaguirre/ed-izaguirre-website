# Ed Izaguirre's Personal Website

Welcome to the repository for my personal website. This site showcases my professional background, featured projects, and other accomplishments. The website is built using Jekyll, a static site generator, and is styled with custom CSS.

## Table of Contents

- [Project Structure](#project-structure)
- [Usage](#usage)
- [Customization](#customization)
- [Deployment](#deployment)
- [Technologies Used](#technologies-used)

## Project Structure
```
├── _layouts/
│   └── default.html         # Main layout template
├── _sass/
│   ├── fonts.scss           # Font definitions
│   ├── jekyll-theme-minimal.scss  # Main theme styles
│   ├── minimal.scss         # Additional minimal styles
│   └── rouge-github.scss    # GitHub-style syntax highlighting
├── assets/
│   ├── css/
│   │   └── style.scss       # Main stylesheet
│   ├── fonts/               # Font files
│   ├── img/                 # Image assets
│   └── js/
│       └── scale.fix.js     # JavaScript for scaling
├── _config.yml              # Jekyll configuration
├── index.md                 # Main content file
├── Gemfile                  # Ruby dependencies
├── LICENSE                  # License information
└── README.md                # This file
```

## Usage
- Build the site with `bundle exec jekyll build`. This command generates the static files in the _site directory.
- Serve the site with `bundle exec jekyll serve`. This command serves the site locally and watches for changes.

## Customization
### Content

- Edit `index.md` to update the main content of the website.
- Modify `_layouts/default.html` to change the overall structure of the page.
### Styling
- The main stylesheet is `assets/css/style.scss`. Edit this file to customize the site's appearance.
- Additional styles are in the `_sass/ directory`.
### Images
- Add or replace images in the `assets/img/ directory`.
- Update image references in `index.md` or `_layouts/default.html` as needed.

## Deployment
This site is designed to be deployed on GitHub Pages:

1. Push your changes to the main branch of your GitHub repository.
2. Go to your repository settings on GitHub.
3. In the "Pages" section, set the source to the main branch.
4. Your site will be published at https://yourusername.github.io/ed-izaguirre-website/.

## Technologies Used
- Jekyll
- HTML5
- CSS3 (SCSS)
- GitHub Pages