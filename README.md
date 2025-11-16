# Coachsite

A professional triathlon coaching website built with [Astro](https://astro.build) and deployed to GitHub Pages.

## 🚀 Features

- **Home Page**: Overview of coaching services with call-to-action
- **About Page**: Coach credentials, approach, and philosophy
- **Contact Page**: Contact information and consultation details
- **Responsive Design**: Modern, clean design that works on all devices
- **GitHub Pages Deployment**: Automatic deployment via GitHub Actions

## 🏗️ Project Structure

```
/
├── public/           # Static assets
│   └── favicon.svg
├── src/
│   ├── layouts/      # Page layouts
│   │   └── Layout.astro
│   └── pages/        # Page routes
│       ├── index.astro
│       ├── about.astro
│       └── contact.astro
├── .github/
│   └── workflows/
│       └── deploy.yml  # GitHub Actions deployment
└── package.json
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |

## 🚀 Deployment

This site automatically deploys to GitHub Pages when changes are pushed to the `main` branch. The deployment is handled by the GitHub Actions workflow in `.github/workflows/deploy.yml`.

To enable GitHub Pages:
1. Go to your repository settings
2. Navigate to Pages section
3. Set Source to "GitHub Actions"

The site will be available at: `https://robbieveivers.github.io/Coachsite/`

## 📝 Customization

- Update the contact email in `src/pages/contact.astro`
- Modify the coaching information in `src/pages/about.astro`
- Adjust the services offered in `src/pages/index.astro`
- Change the site colors by modifying CSS variables in `src/layouts/Layout.astro`