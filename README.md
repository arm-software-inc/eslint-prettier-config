# eslint-prettier-config

## Usage
`$ yarn add eslint-config-myos eslint typescript`

Create a file .eslintrc in root:
```json
{
  "extends": "myos"
}
```

## Rules
- semicolon
- new line in the end of the file
- 3 equals (===)
- single quotes
- no-console

## Extends
- @typescript-eslint/recommended
- prettier/recommended
- eslint/recommended

## Plugins
- html
- prettier
- typescript-eslint

## Missing (please help)
- [ ] html format
- [ ] max-len not working
- [x] prettier rules
- [ ] husky
