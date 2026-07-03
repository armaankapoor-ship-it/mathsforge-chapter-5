# Continuity and Differentiability Forge

A separate, static Class 12 Mathematics learning website for **Chapter 5: Continuity and Differentiability**. It is part of **MathsForge** and is built as a frontend-only project, so it can be shared publicly through Netlify or GitHub Pages without paid hosting, paid APIs, databases, or subscriptions.

Netlify website name:

```text
continuity-differentiability-forge
```

Netlify public website:

```text
https://continuity-differentiability-forge.netlify.app/
```

GitHub Pages public website:

```text
https://armaankapoor-ship-it.github.io/mathsforge-chapter-5/
```

GitHub repository:

```text
https://github.com/armaankapoor-ship-it/mathsforge-chapter-5
```

## What Is Included

- Topic notes for Continuity and Differentiability
- Formula sheet
- Derivation and proof bank
- 2D SVG diagram bank
- Interactive simulations
- 20 chapter-specific detailed interactive 3D models
- Practice question bank with answer reveal
- Revision dashboard
- Printable revision sheet
- Responsive premium UI inspired by MathsForge
- Netlify deployment config
- GitHub Pages deployment workflow

## Run Locally

Open `index.html` in any modern browser.

No install, backend, database, paid API, or build step is required for local viewing.

## Project Structure

```text
.
├── index.html
├── README.md
├── netlify.toml
├── .nojekyll
└── .github/
    └── workflows/
        └── pages.yml
```

## How to Publish This Website for Free Using Netlify

1. Create a free Netlify account at `https://www.netlify.com`.
2. Click **Add new site**.
3. Choose **Deploy manually** for the fastest upload, or choose **Import an existing project** to connect the GitHub repository.
4. If deploying manually, drag this chapter folder into Netlify.
5. If importing from GitHub, select the matching repository and use these settings:

```text
Site name: continuity-differentiability-forge
Base directory: leave blank
Build command: leave blank
Publish directory: .
```

6. Click **Deploy**.
7. After deployment, Netlify will show the public link:

```text
https://continuity-differentiability-forge.netlify.app/
```

## How to Publish This Website for Free Using GitHub Pages

1. Create a free GitHub account at `https://github.com`.
2. Create a new public repository named `mathsforge-chapter-5`.
3. Upload or push all files from this folder into that repository.
4. Install dependencies: this project has no dependencies.
5. Build the project: no build command is required because this is a static website.
6. Open the repository on GitHub, then go to **Settings > Pages**.
7. Under **Build and deployment**, choose **GitHub Actions** as the source.
8. Wait for the Pages workflow to finish.
9. Copy the public website link shown by GitHub Pages.

Expected public link:

```text
https://armaankapoor-ship-it.github.io/mathsforge-chapter-5/
```

## Update the Website Later

Edit `index.html`, save the file, commit the change, and push it to GitHub. GitHub Pages will publish the updated website automatically after the workflow runs.

For Netlify, either push the update to the connected GitHub repository or open Netlify and redeploy the updated chapter folder manually.

## Add More Chapters Later

Create a new folder or repository for each chapter, copy this structure, replace the chapter content in `index.html`, update the README title, update the Netlify site name to `chapter-name-forge`, and publish it with Netlify or GitHub Pages.
