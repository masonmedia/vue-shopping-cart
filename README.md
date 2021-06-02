# Vue Shopping Cart
---
## Intro
---
A shopping cart app using Vue, Vuex, BootstrapVue, and animate.css based on a tutorial by [Akash Ingole](https://www.youtube.com/watch?v=irr7ACcmW_4).

## Details
---
The project uses vuex, vue-router, SASS, vue-i18n for french translation, and is tailored for use on an LMS (`.xml` files, and router config in `router/index.js`). 

## Notes
---
This section details development and process notes, fixes, bugs, etc.

1. Any added/redundant `d-flex` classes will break row/col layout in IE11. BSVue rows come with display `flex` out of the box, and `col` classes receive flex treatment as children of the rows.
2. As of this writing, `object-fit: cover` does not work in IE, so be aware of image styling using this property.
3. Dynamic Vue `:style` bindings appear to break IE. Be sure to test and/or avoid them if IE functionality is necessary.


## Project setup
```
npm install
```

#### Compiles and hot-reloads for development
```
npm run serve
```

#### Compiles and minifies for production
```
npm run build
```

#### Lints and fixes files
```
npm run lint
```