# GridSome: Routing issue when use TypeScript + vue-class-component

Related to [this issue](https://github.com/gridsome/gridsome/issues/552)

```
TypeError: Cannot read property '_init' of undefined
    at e (app.18b52a11.js:7)
    at app.18b52a11.js:12
    at Array.map (<anonymous>)
    at app.18b52a11.js:12
    at l (app.18b52a11.js:12)
    at r (app.18b52a11.js:12)
    at app.18b52a11.js:12
    at app.18b52a11.js:12
    at e.a (app.18b52a11.js:7)
    at l (app.18b52a11.js:12)
```

## How to reproduce the issue

* Install dependencies (`npm ci`)
* Build production app (`npm run build`)
* Run static web-server (`npm run server`)
* Go to the URL web-server gives you
* From `Index` page navigate to `About us` page using a menu in the header
* Navigate back to the `Index` page via the menu

After this the issue should appear in the browser's console.

## Do you know the solution or have an idea how to fix it?

Please let me know here or on [the discussion](https://github.com/gridsome/gridsome/issues/552)'s page.
