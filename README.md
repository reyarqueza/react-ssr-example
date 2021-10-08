# React SSR Example

## Server Side React

Install and start it up!

```bash
reyarqueza@rey-mac : ~/react-ssr-starter-kit
$ npm install
$ npm start
```

## Development

Open up 2 terminals and run the following npm scripts:

### Run the Express server

```bash
reyarqueza@rey-mac : ~/react-ssr-starter-kit
$ npm start
```

### Run the Sass compile watcher (Dart with @use support)

```bash
reyarqueza@rey-mac : ~/react-ssr-starter-kit
$ npm run sass-watch
```

## Prod

Run the express server as usual. There is no build or bundle process, because its purely server side
rendered.

## The Secret (Not) Sauce

### ReactDOMServer

- ReactDOMServer - https://reactjs.org/docs/react-dom-server.html

### sass @use

- A little side bonus, but for SCSS, by using Dart Sass, we get access to this new feature which is
  a step beyond @import giving us es6 like imports in SCSS instead of global imports to make it easy
  to know which file a variable or mixin is coming from:
  https://sass-lang.com/documentation/at-rules/use It gives your SCSS an object oriented like
  flavor.

There is no sass example, but I added it for convenience. You can remove sass and the sass-watch
script from package.json if you like.
