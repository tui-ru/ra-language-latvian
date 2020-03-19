# Latvian Messages for React-Admin

[![npm](https://img.shields.io/npm/v/ra-language-latvian.svg)](https://npmjs.org/package/ra-language-latvian)
[![npm downloads](https://img.shields.io/npm/dm/ra-language-latvian.svg)](https://www.npmjs.com/package/ra-language-latvian)
[![npm bundle size](https://img.shields.io/bundlephobia/minzip/ra-language-latvian.svg)](https://bundlephobia.com/result?p=ra-language-latvian)

Latvian messages for [react-admin](https://github.com/marmelab/react-admin), the frontend framework for building admin applications on top of REST/GraphQL services.

## Installation

```sh
npm install --save ra-language-latvian
```

## Usage

```js
import latvianMessages from 'ra-language-latvian';
import polyglotI18nProvider from 'ra-i18n-polyglot';

const messages = {
    'lv': latvianMessages,
};
const i18nProvider = polyglotI18nProvider(locale => messages[locale]);

<Admin locale="lv" i18nProvider={i18nProvider}>
  ...
</Admin>
```

## License

This translation is licensed under the [MIT Licence](LICENSE).
