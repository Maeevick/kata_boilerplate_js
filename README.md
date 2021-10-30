# Starter Template for kata in javascript

Just a minimalist sandbox/boilerplate to train your skills with javascript, eslint and jest on kata/exercices or something else.

- eslint follow "standard" rules (with few personal choices*) feel free to adapt them to your usage

  ```shell
  npm run lint
  ```
  ```shell
  npm run lint:fix
  ```

  ```json
  "rules": {
      "indent": ["error", 4],
      "comma-dangle": ["error", "always-multiline"],
      "quotes": ["error", "single"],
      "space-before-function-paren": ["error", "never"]
  }
  ```

- jest is configured by default (no config file), feel free to custom it

  ```shell
  npm run test
  ```
  ```shell
  npm run test:watch
  ```
  ```shell
  npm run test:coverage
  ```
  
# Some resources/kata to train your skills

- https://kata-log.rocks/
- https://codingdojo.org/
- https://katalyst.codurance.com/browse
