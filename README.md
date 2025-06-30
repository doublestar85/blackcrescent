# Black Crescent Documentation

This repository hosts the source for a VuePress site. Clone the repository and drop your Markdown file into the `docs/` directory. The sidebar will be generated automatically from your headings.

## Local development

1. Install dependencies (requires Node.js):
   ```sh
   npm install
   ```
2. Start a local server:
   ```sh
   npm run docs:dev
   ```
3. Open `http://localhost:8080` to preview the site.

## Building for GitHub Pages

Run the build command and push the contents of `docs/.vuepress/dist` to the `gh-pages` branch or deploy using GitHub Actions:

```sh
npm run docs:build
```

GitHub Pages should be configured to serve from the `/blackcrescent/` base path.
