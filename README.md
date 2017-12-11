# Create OONI Next

This aids the process of creating a [React](https://facebook.github.io/react) app with server-side rendering thanks to [Next.js](https://github.com/zeit/next.js), styled-components and ooni-components.

It is a hard-fork of the excellent [segmentio/create-next-app](https://github.com/segmentio/create-next-app).

- [Getting Started](#getting-started) — How to create an app
- [Starting from Examples](#starting-from-examples) — How to create an app from a Next.js example

Though this primarily meant to be used internally by OONI, if you wish to use it and run into any issues or have feedback, please [file an issue](https://github.com/openobservatory/create-ooni-next/issues/new)

## Overview

```sh
npm install -g create-ooni-next

create-ooni-next my-app
cd my-app/
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view your running app.
When you're ready for production, run `npm run build` then `npm run start`.

### Start Coding Now

You **don't** need to install or setup Webpack or Babel.
They come packaged with `next`, so you can just start coding.

After running `create-ooni-next`, you're good to go!

## Getting Started

### Installation

Install it once globally:

```sh
npm install -g create-ooni-next
```

**You’ll need to have Node >= 6 on your machine**. You can use [nvm](https://github.com/creationix/nvm#usage) to easily switch Node versions between different projects.

**You don't need to use Node as your primary backend**. The Node installation is only required for Create Next App and running the Next.js server in development/production.

### Creating an App

To create a new app, run:

```
create-ooni-next my-app
cd my-app
```

It will create a directory called `my-app` inside the current folder.<br>
Inside that directory, it will generate the initial project structure and install necessary dependencies:

```
my-app/
  README.md
  package.json
  next.config.js
  components/
    Head.js
    Layout.js
    globalStyle.js
  pages/
    _document.js
    index.js
  static/
    favicon.ico
```

Routing in Next.js is based on the file system, so `./pages/index.js` maps to the `/` route and
`./pages/about.js` would map to `/about`.

The `./static` directory maps to `/static` in the `next` server, so you can put all your
other static resources like images or compiled CSS in there.

Out of the box, we get:

- Automatic transpilation and bundling (with webpack and babel)
- Hot code reloading
- Server rendering and indexing of `./pages`
- Static file serving. `./static/` is mapped to `/static/`

Once the installation is finished, you can run some commands in your project:

### `npm run dev` or `yarn dev`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any errors in the console.

### `npm run build` or `yarn build`

Builds the app for production to the `.next` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

### `npm run start` or `yarn start`

Starts the application in production mode.
The application should be compiled with \`npm run build\` first.

Now you're ready to code & deploy your app!

## Original License (MIT)

```
WWWWWW||WWWWWW
 W W W||W W W
      ||
    ( OO )__________
     /  |           \
    /o o|    MIT     \
    \___/||_||__||_|| *
         || ||  || ||
        _||_|| _||_||
       (__|__|(__|__|
```
Copyright (c) 2017-present Segment.io, Inc. friends@segment.com

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the 'Software'), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
