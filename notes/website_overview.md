# Website Directory Overview

This document summarizes the purpose of the main folders and files in my website project for easy reference and maintenance.

---

## Top-Level Files

- **_config.yml**  
  Main Jekyll configuration file. Controls site settings, collections, plugins, and build options.

- **Gemfile / Gemfile.lock**  
  Ruby gem dependencies for Jekyll and plugins.

- **Dockerfile**  
  Instructions for building the site in a Docker container (optional). Can ignore. Only useful to containerize development environment or deploy site using Docker.

- **README.md**  
  Project overview and instructions (now stored in `/notes`).

---

## Main Content Folders

- **_pages/**  
  Contains individual markdown pages (e.g., about, cv, research, teaching, history).  
  *Edit or add new pages here.*

- **_posts/**  
  Blog posts, named by date.  
  Can ignore  
  *Add new posts here if you want a blog.*

- **_portfolio/**  
  Portfolio items for showcasing work or projects.  
  Not needed

- **_publications/**  
  Markdown files for academic publications.  
  Not needed.  Handled in "Research" page

- **_talks/**  
  Markdown files for talks and presentations.  
  Not needed.  Handled in relevant pages of website

- **_teaching/**  
  Teaching materials and course-related content.  
  Not needed.  Handled in relevant pages of website


- **_drafts/**  
  Unpublished draft posts.  
  Not relevant

---

## Layouts and Includes

- **_layouts/**  
  HTML templates for different page types (e.g., single, research, history_with_toc).

- **_includes/**  
  Reusable HTML snippets (navigation, footer, analytics, comments, etc.).

---

## Data and Configuration

- **_data/**  
  YAML files for navigation menus, author info, UI text, and static comments.

---

## Assets and Styling

- **assets/**  
  CSS, JavaScript, fonts, and webfonts for site styling and interactivity.

- **_sass/**  
  SCSS partials for custom and vendor styles.

---

## Static Files

- **files/**  
  PDFs, slides, and other downloadable resources.

- **files_from_ANU/**  
  Additional documents and images from ANU.

- **history_math/**  
  Historical mathematics documents.

- **images/**  
  Site images, icons, and logos.

---

## Notes and Documentation

- **notes/**  
  Internal documentation and reference files (e.g., `README.md`, `website_structure.txt`, this overview).  
  *Not published on the website; for personal use only.*

---

## Scripts and Automation

- **markdown_generator/**  
  Python and Jupyter scripts for generating markdown from BibTeX/Orcid data.

- **talkmap/**  
  Files for interactive map of talks (Leaflet.js, org-locations.js).

---

## Build Output

- **_site/**  
  Generated static site (output of Jekyll build).  
  *Do not edit directly.*

- **vendor/**  
  Ruby gems and theme dependencies for local builds.

---

## Other Files

- **package.json**  
  NPM dependencies and build scripts (for JS/CSS assets).

- **CONTRIBUTING.md, LICENSE**  
  Project contribution guidelines and license info.

---

## Usage Tips

- Edit content in `_pages`, `_posts`, `_talks`, etc.
- Customize layouts in `_layouts` and snippets in `_includes`.
- Update navigation and author info in `_data`.
- Keep notes and documentation in `/notes` for personal reference.
- Use version control (git) to track changes.

---

*This overview is for personal reference and is not published on the public website.*