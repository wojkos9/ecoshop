# Ecoshop - eCommerce frontend
## Setup

1. Create a `.env` inline with `middleware.config.js` file and fill the following required variables

```bash
SHOPIFY_STOREFRONT_TOKEN=<SHOPIFY_ACCESS_TOKEN>
SHOPIFY_DOMAIN=<SHOPIFY_DOMAIN> # example: vsf-next-pwa.myshopify.com
BASE_URL=<API_DOMAIN> # example: localhost:3001
```

2. Run the project

``` bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production and launch server
$ yarn build
$ yarn start

# generate static project
$ yarn generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org) / [Vue Storefront Docs](https://docs.vuestorefront.io/v2/).
