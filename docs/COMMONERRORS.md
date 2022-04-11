## Rollup options fail
## example-external-component doesn't appear to be written in CJS, but also doesn't appear to be a valid ES module (i.e. it doesn't have "type": "module" or an .mjs extension for the entry point). Please contact the package author to fix.

### Delete node_modules directory
### Delete package-lock.json
### Run `npm cache clear --force`
### Run `npm i`

# Files not appearing in dist/client when running `npm run build`
### Vitejs uses a tree shaking algorithm when building the dist directory.
### If none of the components in the page directory are dependent on other
### components in a different location. It will not be included in the build.