# Storybook

This project was originally written in 2017 using JQuery to toggle HTML classes; Most of the page controller logic was written in JQuery. SASS was chosen for styles, I think just because of the page repitition and how SASS would offer a way to keep the styles organized. Eventually, Gulp became less maintained and surpassing webpack and Vite was selected; This is around that same time while it is also being rewritten in React. The React rewrite is an attempt to port code that can handle generic storybook objects. It is also a point of the rewrite to keep the build healthy, especially with the large amount of stylesheets controlling object placement. This application is mobile-friendly and does rely on SVG objects for storyboard compositites and JSON data for the composite dialogs. This application is multi-lingual and currently uses [English](./src/data/english.js) & [Spanish](./src/data/espanol.js) languages.

As of the latest commit, the SASS loads properly, imports fonts, and renders a simple React component. It was important for me to keep the build healthy, if anything, but to keep it available to work on here and there into the future.

## Dev
```
pnpm i & pnpm run dev
```

## Tasks

- [x] Port SASS
- [-] Port Images
- [ ] Test Screen Loads
- [ ] Load Languages

## Visual Design
[Visual Design](https://keepux-portfolio.netlify.app/ux-studies)

### React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript and enable type-aware lint rules. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
