# Eslint-Config

ESLint Library bundle for us.

## Requirement

these packages are required.

```json
{
  "@typescript-eslint/eslint-plugin": "4.0.1",
  "@typescript-eslint/parser": "4.0.1",
  "@typescript-eslint/typescript-estree": "4.0.1",
  "eslint": "7.8.1",
  "eslint-plugin-import": "2.22.0",
  "eslint-plugin-jest": "23.20.0",
  "eslint-plugin-jsx-a11y": "6.3.1",
  "eslint-plugin-react": "7.20.6",
  "eslint-plugin-react-hooks": "4.1.0",
  "jest": "26.4.2",
  "typescript": "4.0.2"
}
```
## Rules

### `@jamashita/eslint-config`

Base config. TypeScript required.

### Install

```text
yarn add @jamashita/eslint-config \
  @typescript-eslint/eslint-plugin \
  @typescript-eslint/parser \
  @typescript-eslint/typescript-estree \
  eslint \
  eslint-plugin-import \
  typescript -D
```

### Append in `.eslintrc`

```json
'extends': [
  '@jamashita/eslint-config'
]
```

### `@jamashita/eslint-config/jest`

Jest config. Jest required.

### Install

```text
yarn add @jamashita/eslint-config \
  eslint \
  eslint-plugin-jest \
  jest -D
```

### Append in `.eslintrc`

```json
'extends': [
  '@jamashita/eslint-config/jest'
]
```

### `@jamashita/eslint-config/react`

React config.

### Install

```text
yarn add @jamashita/eslint-config \
  eslint \
  eslint-plugin-jsx-a11y \
  eslint-plugin-react \
  eslint-plugin-react-hooks -D
```

### Append in `.eslintrc`

```json
'extends': [
  '@jamashita/eslint-config/react'
]
```

## Lisence

[MIT](LICENSE)