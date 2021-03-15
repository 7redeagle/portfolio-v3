## Parcel 
.gitignore: node-modules, .cache, dist 

```
yarn init -y
yarn add parcel-bundler

# In package.json: 
"scripts": { "dev": "parcel src/pug/index.pug", "build": "parcel build src/pug/index.pug" }

yarn dev : local server
yarn build : build production version (netlify)
```

## Assets
- Logo SVG and PNG (Use as Parcel Favicon)
- Navbar Icons: work, project, and contact
- Social Icons: Github and Codepen 
- Skills Icons 
- Background Texture 
- Project Pictures 

## HTML and Pug 
- Multiple Pug Files: Mixins, Header, Nav, Hero, Projects, Skills, Contact, and Footer 
- Put inline SVG in separate PUG files and include them (can change fill) 
- Setup BEM naming
- Json and Mixins 
- SCSS 
- Use multiline comments and nesting with BEM 

## SCSS
1-vendors: normalize, grid, frameworks
2-abstracts: mixins (breakpoints), variables, helpers 
3-base: base (colors), typography
4-components: buttons, icons
5-layout: sections, main, navbar, footer 
6-sections: hero, about, projects, contact 
Main.scss: import all partials 

## README and LICENSE
- Language, Tools, Bundlers, and Hosting 
- Link and Clone instructions
- Folder Structure layout
- Credit and License

## Javascript
- Vanilla JS ScrollSpy 
- JQuery: Google CDN

## Layout: 
- min-height: 100vh
- Grid System and Margins
- Mixins Breakpoints: Mobile First Breakpoints 
- Typography: Primary: Montserrat, Headings: Lato (heading class modifier)
- The elements of responsive typography 

## Variables: 
- $color-name: color (use hsl);
- $body-bg: $color-name; 
- Body bg, text-color, heading-color, card-bg, navbar-bg, icon-fill and so on 

## Navbar
- Left Nav: Home, Projects, Gallery, Skills, Contact, Social 
- Bottom Nav: Logo, Projects, Skill, Contact. Social Icon hidden.

## Hero 
- Social icon: hidden when on desktop, visible in mobile. 
- Lato heading: Hi (color modifier), I’m Ina! 
- Montserrat: I am a front-end web developer looking for new opportunities where I am always learning and improving. 
- Projects button

## Projects
- Pug: Mixins for each projects 
- Make all cards the same height 
- Card layout: Name, Pic, Description, Tools Icon, Demo, Github
- Json and Html or Array-objects in pug

## Gallery 
- Inkscape Work and Logos

## Skills and Work Experience
- ½--lap for each side 
- ⅓ for desktop - ½ for mobile: Grid 3 columns for skills try to make even
- Resume: Download resume 

## Contact
- Link to Netlify with honeypot spam filter
- Placeholder: John Doe email@email.com 
- No email, use Netlify contact form instead

## Footer
2020 @ Copyright Website and Artwork designed and created by Me 







