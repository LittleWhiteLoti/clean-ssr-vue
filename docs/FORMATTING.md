# minimalist-ssr-vue

> Before submitting code for pull requests do the following

-   Make sure there are 0 problems in vs code. Most of them will come from overprotective linting.
-   Run `npm run check`, if there are zero problems then you don't need to run `npm run format`.
-   Run `npm run format`
-   `Important`: Linting will not catch the next step so you will need to check it manually.
    If importing more than one destructured value, follow allman formatting with the opening curly
    brace on a separate line. On a newline after that, indent and include only one destructured
    value per line per destructured value. The closing brace should be on the same indentation level
    as the opening curly brace. For an example see the src/router.js file.
-   If you do add a yaml (.yaml, .yml) file please make a note in the commit message. The linters
    don't currently check for them but it may be needed in the future.
