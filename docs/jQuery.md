# jQuery

## Building a jQuery web app with Parcel

This repo was building by [parcel](https://parceljs.org/getting-started/webapp/).

###  A. Start parcel to render webpage

- Install parcel 

```
npm install --save-dev parcel jQuery
```

- set index.html

src/index.html

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8"/>
    <title>My jQuery Parcel App</title>
  </head>
  <body>
    <h1>Hello, World!</h1>
        <!-- Load jQuery -->
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script type="module" src="index.js"></script>
  </body>
</html>
```

- rend index.html 

```
npx parcel src/index.html 
```

- generate .gitignore

```
npx gitignore node
```

- Add `"start"` scripts to the `package.json` file  

```json
"scripts": {
    "start": "parcel index.html"
},
```
