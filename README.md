# Vite dev template

# ディレクトリ構成


```
root
  ├── dist
  ├── src
  │   ├── [pages]
  │   │    └── index.html
  │   ├── assets
  │   │   ├── scripts
  │   │   │   ├── pages
  │   │   │   │   └── [pages]
  │   │   │   │        └── index.js
  │   │   │   └── common.js
  │   │   └── styles
  │   │       ├── pages
  │   │       │   └── [pages]
  │   │       │        ├── _module.scss
  │   │       │        └── style.scss     //　同階層の'_*.scss'をimport   
  │   │       └── main.scss     // pages以外のファイルを全てimport
  │   ├── components
  │   │   ├── header.ejs
  │   │   ├── footer.ejs
  │   │   └── ...
  │   ├── public
  │   │   └── assets
  │   │       ├── images
  │   │       ├── scripts   // 圧縮したくないscripts
  │   │       └── styles    // 圧縮したくないstyles
  │   └── index.html
  ├── .stylelintrc.js
  ├── package.json
  └── vite.config.js

```
