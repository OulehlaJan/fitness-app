![GitHub License](https://img.shields.io/github/license/oulehlajan/fitness-app?style=for-the-badge)

<!-- Created by, animated text -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Noto+Sans&weight=600&size=32&duration=3300&pause=4800&color=79C0FF&center=true&vCenter=true&random=false&width=435&lines=%F0%9F%91%8B%2C+Created+by+%40OulehlaJan" />
</p>
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=noto&weight=600&size=22&duration=4000&pause=4350&color=FFA657&center=true&vCenter=true&random=false&width=910&lines=a+self-taught+passionate+Web+developer+from+Czechia" />
</p>

# :computer: Demo
[![Netlify Status](https://api.netlify.com/api/v1/badges/85d75531-9c42-484c-9a8e-22e65467d979/deploy-status)](https://app.netlify.com/sites/fitness-app-oulehlajan/deploys) <br />

<!-- Demo Link -->
<p align="center">
  <a href="https://fitness-app-oulehlajan.netlify.app/">Fitness App</a>:point_left: <br />
</p>

<!-- GIF -->
<p align="center">
  <img src="assets/FitnessApp.gif" />
</p>

## &#129513; Dependencies

+ React Anchor Link Smooth Scroll
+ React Hook Form
+ Framer Motion
+ Hero Icons

## :open_file_folder: What's inside?

A quick look at the structure of this project.

    .
    ├── public
    │   └─── favicon.ico
    ├── src
    │   ├─── assets
    │   │    └─── images...
    │   ├─── hooks
    │   │    └─── useMediaQuery.ts
    │   ├─── scenes
    │   │    ├─── benefits
    │   │    │    ├─── index.tsx
    │   │    │    └─── Benefit.tsx
    │   │    ├─── contactUs
    │   │    │    └─── index.tsx
    │   │    ├─── footer
    │   │    │    └─── index.tsx
    │   │    ├─── home
    │   │    │    └─── index.tsx
    │   │    ├─── navbar
    │   │    │    ├─── index.tsx
    │   │    │    └─── Link.tsx
    │   │    ├─── ourClasses
    │   │    │    ├─── index.tsx
    │   │    │    └─── Class.tsx 
    │   ├─── shared
    │   │    ├─── ActionButton.tsx
    │   │    ├─── HText.tsx
    │   │    └─── types.ts
    │   ├─── App.tsx
    │   ├─── index.css
    │   ├─── main.tsx
    │   └─── vite-env.d.ts
    ├── License
    ├── README.md
    ├── index.html
    ├── package-lock.json
    ├── package.json
    ├── postcss.config.js
    ├── prettier-config.cjs
    ├── tailwind.config.js
    ├── tsconfig.app.json
    ├── tsconfig.json
    ├── tsconfig.node.json
    └── vite.config.ts


# TypeScript + React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
