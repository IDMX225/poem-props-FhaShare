# README
[![Netlify Status](https://api.netlify.com/api/v1/badges/a81f22c8-24f9-4bb5-9896-8632ce867fe7/deploy-status)](https://app.netlify.com/sites/the-pumkin-by-jgw/deploys)

## The Pumpkin by John Greenleaf Whittier
This project presents a poem page showcasing The Pumpkin by John Greenleaf Whittier. The design incorporates Open Props and Normalize CSS for styling while adhering to best practices in semantic HTML and responsive design. The poem is part of the public domain and has been enhanced with an accompanying image from Unsplash, chosen to reflect its theme.

### Features
> Semantic HTML: Properly use elements like header, main, footer, section, and article.

> Responsive Design: The page is fully responsive, with content adjusting smoothly across screen sizes.

> Open Props: Pre-defined custom properties from Open Props are utilized for styling consistency.

> Normalize CSS: Standardization of styles across browsers using Normalize CSS.

> BEM Methodology: Styling uses the BEM naming convention to keep classes organized and specific.

> Accessibility: The page passes simple accessibility checks, with alt text on images and sufficient color contrast.

# IDMX 11ty Sass Starter

The set of development scripts in this starter is configured to watch and compile a simple Sass structure using 11ty.

The code is located in the `src` folder and the page is created in the `public` folder.

The `settings.json` in the `.vscode` folder sets the `LiveServer` configuration to serve from the `public` folder and can be used to serve the built page.

The build process includes minifiying and autoprefixing of styles via the `postbuild` script, which runs automatically after a `build`.

## Installation

**`npm install`**

>Run this command once to install the needed node modules.

## Development Scripts

**`npm start`**

> This script runs 11ty with hot reload and served at the url localhost:8080. It will reload whenever there are HTML or Sass changes.

**`npm run build`**

> This script does a production build and includes minified, autoprefixed CSS.

Use this as the "Publish command" if needed by hosting services such as Netlify.

## Resources

<small>The starter was inspired by [11ty Sass Skeleton](https://github.com/5t3ph/11ty-sass-skeleton) by [@5t3ph](https://twitter.com/5t3ph)</small>

## My Resources

<small>Poem is from [Public Domain Poetry](https://www.public-domain-poetry.com/john-greenleaf-whittier/pumpkin-6135)</small>

<small>Image is from [Unsplash](https://unsplash.com/photos/focus-photography-of-pumpkin-V1dae2Jj6-0)</small>

<small>Faviconis is from [Vecteezy](https://www.vecteezy.com/png/17398359-pumpkin-halloween-lantern-realistic)</small>
