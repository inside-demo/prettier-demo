# Prettier demo

[![code style: prettier][prettier-image]][prettier-url]

## Run demo
- Clone this repo
- Install packages
  ```shell
  npm install
  ```
- Run ESLint
  ```shell
  npm run lint
  ```

  <details>
   <summary>It will outputs list of style errors</summary>

  ```
  \work\prettier-demo\src\index.js
    1:1   error  Insert `;`                     prettier/prettier
    4:10  error  Replace `"BAR"` with `'BAR',`  prettier/prettier
    6:5   error  Delete `;`                     prettier/prettier

  ✖ 3 problems (3 errors, 0 warnings)
    3 errors, 0 warnings potentially fixable with the `--fix` option.
  ```
  </details>

- Format sources
  ```shell
  npm run format
  ```
  It will format source files `src/index.js` and `src/styles.css`

## Links
- [Prettier](https://github.com/prettier/prettier)
- [ESLint configuration](https://github.com/prettier/eslint-plugin-prettier#recommended-configuration)
- [Code Formatting](https://survivejs.com/maintenance/code-quality/code-formatting/)

## License
MIT

[prettier-url]: https://github.com/prettier/prettier
[prettier-image]: https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square
