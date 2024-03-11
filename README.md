# CSP: External script hashes with `strict-dynamic` present in `script-src`

Minimal reproduction for external script loading (via the `integrity` attribute) when `strict-dynamic` is present in the `script-src` directive.

## Instructions

You will need node installed, or a way to serve `index.html` and `externalScript.js`.

If you have node:

```shell
npx serve
```

### Testing

- Open your browser to http://localhost:3000
- Expect to see no CSP error logged, either on screen or in the console