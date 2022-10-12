# Browser modules

When supported by the browser we can work w/ them very similar as we do with a bundling tool like webpack.

We load the entry point of our application in the `index.html` and then we can import other modules in our application where we need them.

```html
<script src="./main.js" type="module"></script>>
```

**Note**: The `type="module"` attribute is required for the browser to know that we are working with a module. It loads the script in a `defer` mode. This eliminates the JS blocking behavior of the browser

More [here](https://bitsofco.de/async-vs-defer/)