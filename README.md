# Bangla Translations for React-Admin

Bangla translations for [React-Admin](https://github.com/marmelab/react-admin), the frontend framework for building admin applications on top of REST/GraphQL services.

[![react-admin-demo](https://marmelab.com/react-admin/img/react-admin-demo-still.png)](https://vimeo.com/268958716)

## Installation

```sh
npm install --save ra-language-bangla
```

## Usage

```js
import BanglaMessages from 'ra-language-bangla';

const messages = {
    'bn': BanglaMessages,
};

const i18nProvider = locale => messages[locale];

<Admin locale="bn" i18nProvider={i18nProvider}>
  ...
</Admin>
```
## License

This translation is licensed under the [MIT](LICENSE).