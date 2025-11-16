# Chelsea Seymour Coaching

A professional Ironman and triathlon coaching website for Chelsea Seymour, built with [Astro](https://astro.build) and deployed to GitHub Pages.

**🌐 Live Site:** [https://robbieveivers.github.io/Coachsite/](https://robbieveivers.github.io/Coachsite/)

## 🚀 Features

- **Home Page**: Overview of Chelsea's coaching services with Ironman and swim focus
- **About Page**: Chelsea's background, approach, and coaching philosophy
- **Contact Page**: Contact information and free consultation details
- **Pink Theme**: Custom color scheme reflecting Chelsea's brand
- **Responsive Design**: Modern, clean design that works on all devices
- **YouTube Integration**: Links to Chelsea's YouTube channel
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

## 📝 About Chelsea Seymour

Chelsea Seymour is an Ironman athlete and triathlon coach specializing in swim technique and endurance training. Her coaching focuses on:
- 🏊‍♀️ Swim technique excellence
- 🚴‍♀️ Personalized Ironman training plans
- 🏃‍♀️ Race day preparation and strategy

Connect with Chelsea:
- **YouTube**: [@chels.seymour](https://youtube.com/@chels.seymour)
- **Email**: chelsea@example.com