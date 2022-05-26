<p>
<img src="https://img.fortawesome.com/349cfdf6/fontawesome-open-graph.png">
</p>
<h2 align="center">
Fontawesome Icon pack custom version
</h2>

### Installation: :arrow_down:
```bash
npm install @mohamadtsn/fontawesome-icon
```

## Usage for Webpack :arrow_down:

### Use all type:
Import `all font types` by adding this line to your app’s entry point (usually `index.js` or `app.js`):
```js
import "@mohamadtsn/fontawesome-icon/dist/css/all.css"
```

### Use a special type:
Import `*.[min].css` from `/dist/css/` by adding this line to your app’s entry point (usually `index.js` or `app.js`):
```js
import "@mohamadtsn/fontawesome-icon/dist/css/*.[min].css"
```

### Type:
```sh
.
├── package.json
├── dist
│   └── css
│   │   └── all[min].css
│   │   └── brands[min].css
│   │   └── duotone[min].css
│   │   └── light[min].css
│   │   └── regular[min].css
│   │   └── solid[min].css
│   │   └── thin[min].css
│   └── fonts
│      ├── fa-[brands,duotone,light,regular,solid,thin] => *.ttf | *.woff2
```
