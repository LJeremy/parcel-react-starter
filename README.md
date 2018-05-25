# React Parcel Example

📦 Simple React.js boilerplate with parcel. [Parcel Bundler](https://parceljs.org)

**What's inside?**

* `parcel-bundler`
* `react`
* `react-dom`
* `babel-preset-env`
* `autoprefixer`
* `node-sass`
* `postcss`

## Getting started

Clone and install

```
git clone https://github.com/LJeremy/parcel-react-starter.git
cd react-parcel-starter
npm install
npm start
```

## Building for Production

```
npm run build
```

This will compile your JS and copy your `index.html` to the `dist` folder which
you can deploy wherever as a good ol' webpage.

### Moving `index.html`

If you want to move `index.html`, you will need to update your npm scripts in
`package.json` with the new relative path.

## Deployment

Refer to the deployment guide in `create-react-app`, just note that you will
need to account for the fact that Parcel builds out to a `dist` directory, while
CRA builds to a `build` directory. You can make it identical by adding
`--out-dir build` to both `start` and `build` npm tasks in `package.json`.
