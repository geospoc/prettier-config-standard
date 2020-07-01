# @geoospoc/prettier-config-standard

> [Prettier](https://prettier.io/) config for all GeoSpoc projects

## Install

```bash
npm i -D @geoospoc/prettier-config-standard
```

## Usage

In `package.json`:

```json
{
  "prettier": "@geoospoc/prettier-config-standard"
}
```
In dedicated `prettier.config.js`:

```js
module.exports = {
  ...require('@geoospoc/prettier-config-standard'),
};
```

## License

MIT.
