# Steps to replicate this repository using the vitejs repository at https://github.com/vitejs/vite

# To use this project separately go to the vite directly and run `pnpm install`
# Go back to packages/playground/ssr-vue
# Go to the package.json and remmove @vitejs/plugin-vue and @vitejs/plugin-jsx from dev dependencies.
# For some reason these are linked the vite root project so they have to be manually installed
# Run `npm install @vitejs/plugin-vue@latest @vitejs/plugin-jsx@latest --save-dev`
# In the package.json switch `"dep-import-type": "link:./dep-import-type"` to `"dep-import-type": "file:./dep-import-type"` as link is no longer supported by npm
# Delete the node_modules folder and the package-lock.json
# Run `npm cache clear --force`
# Run `npm i` to rebuild node_modules and package.json
# Run `npm run build` to rebuild the project