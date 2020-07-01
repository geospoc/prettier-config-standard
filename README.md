# @geospoc/prettier-config-standard

> [Prettier](https://prettier.io/) config for all GeoSpoc projects

## Install

```bash
npm i -D @geospoc/prettier-config-standard
```

## Usage

In `package.json`:

```json
{
  "prettier": "@geospoc/prettier-config-standard"
}
```
In dedicated `prettier.config.js`:

```js
module.exports = {
  ...require('@geospoc/prettier-config-standard'),
};
```

## License

MIT.
