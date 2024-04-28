# Vue 3 + Vite

This template should help get you started developing with Vue 3 in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Vue - Official](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (previously Volar) and disable Vetur

```
npm create vite@latest
npm install
npm run dev
npm run build
git add dist -f
git commit -m "adding dist"
git subtree push --prefix dist origin gh-pages
npm run build
git add dist -f
git subtree push --prefix dist origin gh-pages
npm run build
git add dist -f
git commit -m "adding dist"
git subtree push --prefix dist origin gh-pages
```
