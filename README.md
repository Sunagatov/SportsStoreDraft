# Sports Store Draft

An Angular storefront exercise with a product catalogue, shopping cart and checkout forms.

<p>
  <a href="https://buymeacoffee.com/lucky_1uck">
    <img src="https://img.shields.io/badge/Support_the_project-FFDD00?style=for-the-badge&amp;logo=buymeacoffee&amp;logoColor=black" alt="Support the project" width="260" height="40">
  </a>
</p>

## What is included

- Product and category browsing with a static product data source.
- Cart summary and cart detail components.
- Checkout and order models.
- A separate JSON Server script with authentication middleware for backend experiments.

The default `StaticDataSource` returns in-memory products and logs orders to the
console. Checkout does not imply a persisted order or a payment integration.

## Stack

Angular 7.2 · TypeScript 3.2 · RxJS · Bootstrap · Angular CLI 7.3

## Local development

Use a Node/npm environment compatible with Angular CLI 7.3. The dependency
versions in [package.json](package.json) belong to that original toolchain.

```bash
npm install
npm start
```

Open `http://localhost:4200/`. To start the optional mock API in another terminal:

```bash
npm run json
```

The mock server listens on port `3500`. The current static data source does not
automatically switch to this API.

## Available commands

| Command | Purpose |
| --- | --- |
| `npm run build` | Compile the Angular application |
| `npm test` | Run Karma/Jasmine tests |
| `npm run lint` | Run the configured TSLint checks |
| `npm run e2e` | Run Protractor end-to-end tests |

## Find your way around

- [Store UI](src/app/store): catalogue, cart and checkout components.
- [Models](src/app/model): products, cart, orders and the static data source.
- [Mock data](data.js) and [middleware](authMiddleware.js): JSON Server support.

## ☕ Support the project

If this project helps you learn or build, you can support its development.

<p>
  <a href="https://buymeacoffee.com/lucky_1uck">
    <img src="https://img.shields.io/badge/Support_the_project-FFDD00?style=for-the-badge&amp;logo=buymeacoffee&amp;logoColor=black" alt="Support the project" width="260" height="40">
  </a>
</p>
