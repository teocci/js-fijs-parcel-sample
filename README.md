## Flight Indicators JS Parcel Sample (FIJS Sample)

This basic implementation shows how to use [FIJS][2] with `npm` and [`parcel`][1].

[ ![NPM Status](https://img.shields.io/npm/v/flight-indicators-js.svg?style=flat) ][2]

### Installation

- Create a new module using `npm`:

```console
npm init -y
```

- Add `parcel`:

```console
npm install --save-dev parcel
```

- Create directories `src`, `img` and `css`:

```console
mkdir src
mkdir src/css

touch index.{js,html}
touch src/css/style.css
```
- Copy `package.json` and `.parcelrc` files from this repository into your project directory.

- In the `src` directory copy `index.html` and `index.js`

- Install `FIJS`:
```console
npm i flight-indicators-js@latest
```

- Copy the images form the library
```console
cp -v node_modules/flight-indicators-js/img src/
```

- Your directory must look like:

```console
project/
|-src/
    |-css/
        |-style.css
    |-img/
        |-*.svg
    |-index.js
    |-index.html
|-.parcelrc
|-package.json
```

- Finally, start (development) or build (production) the project.

`start`:
```console
$ npm run start

Server running at http://localhost:1234
√ Built in 36ms
```
- Then open `http://localhost:1234` in your browser.

Or `build` and deploy it:

```console
$ npm run build

√ Built in 3.61s

dist\index.html              615 B    1.19s
dist\index.18a9bc47.css      832 B    2.74s
dist\index.169f7d3f.js     7.62 KB    602ms
```

### Author

Teocci (teocci@yandex.com)

### License

The code supplied here is covered under the MIT Open Source License.

[1]: https://parceljs.org/
[2]: https://www.npmjs.com/package/flight-indicators-js
[3]: https://github.com/teocci/js-module-flight-indicators/blob/main/assets/fijs-sample.png?raw=true