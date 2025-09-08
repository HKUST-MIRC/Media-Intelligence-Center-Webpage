# Note for adding content
- `config.yaml` is the main configuration file for the site. You can set site-wide settings like title, description, and theme here.
- `src/navigation.ts` contains the navigation structure for the site, including **header links**, **footer links**, and social media links.
- `src/` directory contains the main source code for the website, including pages, components, styles
  - `src/components/` directory contains reusable UI components that can be used across different pages.
    - `src/components/logo.astro` is the logo component used in the header. 
  - `src/pages/` directory contains the individual pages of the website. Each .astro file corresponds to a route on the site. Markdown files (.md) can also be used for content pages.
    - `src/pages/index.astro` is the homepage of the site.

# Note for deployment
- Modify `.github/workflows/deploy.yml` for automated deployment settings.