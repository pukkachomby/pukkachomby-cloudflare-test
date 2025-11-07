# Project Overview

This is a business website template built with the [Hugo](https://gohugo.io/) static site generator. It uses the [Bookshop](https://github.com/CloudCannon/bookshop) component system for a modular and maintainable codebase. The project is optimized for editing and deployment on the [CloudCannon](https://cloudcannon.com/) Jamstack platform.

The visual styling is based on the [Megakit Bootstrap template](https://github.com/themefisher/Megakit-Bootstrap-Agency-Template) and is implemented using Sass.

# Building and Running

To build and run the project locally, you need to have Hugo installed. You can then use the following command:

```bash
hugo server
```

This will start a local development server, and you can view the site at `http://localhost:1313`.

# Development Conventions

## Components

The site is built using a component-based architecture, with components managed by Bookshop. Individual components can be found in the `component-library/components` directory. Each component has a Hugo template (`.hugo.html`) and a Bookshop configuration file (`.bookshop.yml`).

## Styling

The project uses Sass for styling, with the main stylesheet located at `assets/scss/style.scss`. The styling is organized into partials for different sections of the site, which can be found in the `assets/scss/templates` directory.

## Content

Website content is stored in the `content` directory as Markdown files. The site structure is defined by the organization of these files.
