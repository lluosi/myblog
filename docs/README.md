---
home: true
title: Home
heroImage: https://vuejs.press/images/hero.png
actions:
  - text: Get Started
    link: /getting-started.html
    type: primary

  - text: Introduction
    link: https://vuejs.press/guide/introduction.html
    type: secondary

features:
  - title: Simplicity First
    details: Minimal setup with markdown-centered project structure helps you focus on writing.
  - title: Vue-Powered
    details: Enjoy the dev experience of Vue, use Vue components in markdown, and develop custom themes with Vue.
  - title: Performant
    details: VuePress generates pre-rendered static HTML for each page, and runs as an SPA once a page is loaded.
  - title: Themes
    details: Providing a default theme out of the box. You can also choose a community theme or create your own one.
  - title: Plugins
    details: Flexible plugin API, allowing plugins to provide lots of plug-and-play features for your site.
  - title: Bundlers
    details: Default bundler is Vite, while Webpack is also supported. Choose the one you like!

footer: MIT Licensed | Copyright © 2018-present VuePress Community
---

This is the content of home page. Check [Home Page Docs][default-theme-home] for more details.

[default-theme-home]: https://vuejs.press/reference/default-theme/frontmatter.html#home-page

git add .
git commit -m 'push dist'
// 将 dist 目录的内容推送到远程仓库的 gh-pages 分支（这个命令会创建对应分支，如果没有的话）
git subtree push --prefix docs/.vuepress/dist origin gh-pages


我最开始是使用的git add dist/*,然后push发现没用，还是没找到对应资源