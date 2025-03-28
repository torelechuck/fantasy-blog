This is for workshop at [Booster Conference 2025](https://www.boosterconf.no/2025/)

# From zero to your own blog

We are going to set up a minimal Eleventy project, using as little code as we can get away with, to be able to focus on writing posts in Markdown — and publish them with GitHub Pages.

## Write a post ✍️

Add a `.md` file in this directory: `posts/2025/` with a bit of meta info at the top:

```
---
title: Hello world
date: 2025-03-25
author: Elisabeth
---
Text here! Optionally using Markdown for formatting
```

## Run a local development server (optional)

Depending on your inclination, you don’t have to do this part. Feel free to skip it and follow instructions in the workbook you got! Anyone who wants to run a Node.js server locally, can to that with these getting started commands:

- `node --version` to verify that you have Node.js
- `npm install` to plant dependencies
- `npm start` to run locally at http://localhost:8080
- `npm run build` to generate static HTML/CSS
