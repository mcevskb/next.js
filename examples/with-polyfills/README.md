[![Deploy to now](https://deploy.now.sh/static/button.svg)](https://deploy.now.sh/?repo=https://github.com/zeit/next.js/tree/master/examples/with-polyfills)

# Example app with polyfills

## How to use

Download the example [or clone the repo](https://github.com/zeit/next.js):

```bash
curl https://codeload.github.com/zeit/next.js/tar.gz/master | tar -xz --strip=2 next.js-master/examples/with-polyfills
cd with-polyfills
```

Install it and run:

```bash
npm install
npm run dev
```

Deploy it to the cloud with [now](https://zeit.co/now) ([download](https://zeit.co/download))

```bash
now
```

## The idea behind the example

Next.js supports browsers from IE10 to the latest. It adds polyfills as they need. But Next.js cannot add polyfills for code inside NPM modules.
So sometimes, you need to add polyfills by yourself.

This how you can do it easily with Next.js's custom webpack config feature.
