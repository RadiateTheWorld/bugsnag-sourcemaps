# Example: TypeScript

This example contains a Node project which is written in TypeScript. The `upload-source-maps` command in `package.json` uses the `bugsnag-sourcemaps`' `--directory` mode to upload all of the generated source maps.

Be sure to replace the API key in `package.json` and `src/services/bugsnag.ts` before you begin.

## Usage:

```
npm install
npm run build
npm run upload-source-maps
npm start
```
