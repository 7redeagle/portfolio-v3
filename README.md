# portfolio-v3
* Add JQuery CDN instead of npm package
* Remove Resume and have the skills take the entire section and add pdf link to resume


{
  "name": "portfolio",
  "version": "3.0.0",
  "main": "index.js",
  "repository": "git@github.com:7redeagle/portfolio-v2.git",
  "author": "tiger-fish <25111698+7redeagle@users.noreply.github.com>",
  "license": "MIT",
  "devDependencies": {
    "parcel-bundler": "^1.12.4",
    "pug": "^3.0.1",
    "sass": "^1.29.0"
  },
  "scripts": {
    "dev": "parcel src/index.pug",
    "build": "parcel build src/index.pug"
  },
}
