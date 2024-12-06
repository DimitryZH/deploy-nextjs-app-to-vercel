# Next.js Vercel Deployment

This project is a web application built with Next.js and deployed using Vercel. It includes automated workflows for building, linting, and deploying the application to both preview and production environments.

## Features

- **Next.js Framework**: Utilizes the powerful features of Next.js for server-side rendering and static site generation.
- **CSS Modules**: Scoped CSS with CSS Modules for styling components.
- **Automated Workflows**: GitHub Actions workflows for continuous integration and deployment.
- **Vercel Deployment**: Seamless deployment to Vercel with preview and production environments.

## Project Structure

- `.eslintrc.json`: Configuration file for ESLint.
- `.github/workflows/deploy.yaml`: GitHub Actions workflow for deploying the application.
- `.gitignore`: Specifies files and directories to be ignored by Git.
- `.vercel/project.json`: Configuration file for Vercel project settings.
- `.vercel/README.txt`: Information about the Vercel project.
- `next.config.mjs`: Configuration file for Next.js.
- `package.json`: Lists project dependencies and scripts.
- `pnpm-lock.yaml`: Lockfile for pnpm package manager.
- `public/`: Directory for static assets.
- `README.md`: Project documentation.
- `src/app/globals.css`: Global CSS styles.
- `src/app/layout.tsx`: Layout component for the application.
- `src/app/page.module.css`: CSS module for the main page.
- `src/app/page.tsx`: Main page component.
- `tsconfig.json`: TypeScript configuration file.
- `vercel.json`: Configuration file for Vercel deployment.

## Deployment

The project is configured to deploy automatically using GitHub Actions and Vercel.

### Preview Deployment

Deploys to a preview environment on every pull request.

### Production Deployment

Deploys to the production environment on every push to the `main` branch.
