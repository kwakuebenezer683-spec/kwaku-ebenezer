# Kwaku Ebenezer

A simple responsive business website for Kwaku Ebenezer, built as a static web app that can be published as a live public page.

## Run locally

```bash
python -m http.server 3000
```

Then open http://localhost:3000

## Publish as a live web page

This project is set up for GitHub Pages deployment.

1. Push this repository to GitHub.
2. Open the repository on GitHub.
3. Go to Settings > Pages.
4. Under Build and deployment, choose "GitHub Actions".
5. The workflow file is already included at `.github/workflows/deploy.yml`.
6. After the workflow runs, your live URL will be:

```text
https://<your-github-username>.github.io/kwaku-ebenezer/
```

## Share the app link

Share the GitHub Pages URL with customers so they can open the site from any device. Because the page includes a web app manifest, mobile users can also install it to their home screen like an app.

## Custom domain setup

For a branded URL, add a custom domain in GitHub Pages:

1. Buy or choose your domain.
2. In GitHub, open Settings > Pages.
3. Add your domain under Custom domain.
4. Update your DNS provider to point the domain to GitHub Pages.
5. Use the included CNAME file as the base setup for the domain configuration.

Example pattern:

```text
https://www.yourdomain.com
```

## App icon set

The project includes branded SVG app icons in the assets folder, including 192px and 512px versions, which can be used for install prompts, favicons, and home-screen display.

## Android-style install page

Open the install page from the browser to preview a mobile app launch screen:

```text
http://localhost:3000/install.html
```

This page is designed to look like an Android app install screen and can be used as the public landing page before customers download or install the app.

## Real download button for files and apps

A real downloadable package is included in the downloads folder:

```text
downloads/kwaku-ebenezer-package.zip
```

You can add this package to the app landing page or publish it from the live site so customers can click a working download button.
