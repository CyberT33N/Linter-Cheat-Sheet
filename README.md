# Linter Cheat Sheet
Linter Cheat Sheet with the most needed stuff..


<br><br>

# ESLint
- https://eslint.org/docs/user-guide/getting-started

## Install

```bash
npm i -g eslint

# cd into your project
eslint --init # will create .eslintrc.yml
```

#### Atom
https://atom.io/packages/linter-eslint (https://www.youtube.com/watch?v=dG9EEkSCbWM)

<br><br>

## Rules
- https://eslint.org/docs/rules/

#### Disable Rules
```yaml
rules:
  arrow-parens: off
``` 

#### Arrow Parens
https://eslint.org/docs/rules/arrow-parens
```javascript
// Bad
(a) => {}

// Good
a => {}
```
