<h1 align="center">
  chrisdettloff.com
</h1>
<p align="center">
  The second iteration of <a href="https://www.chrisdettloff.com" target="_blank">chrisdettloff.com</a>
</p>

<p align="center">
  <a href="https://app.netlify.com/sites/chrisdettloff/deploys" target="_blank">
    <img src="https://api.netlify.com/api/v1/badges/9cad7148-e002-4f7f-8431-02402fb64993/deploy-status" alt="Netlify Status" />
  </a>
</p>

![demo](static/images/demo.png)

## Stack

#### Foundation

Built using the **[GatsbyJS](https://github.com/gatsbyjs/gatsby)** framework.

#### Data
Page content is stored in markdown files and queried with [**GraphQL**](https://graphql.org/).

#### Styling

Styling is done using [**Styled Components**](https://www.styled-components.com).

## Linting & Formatting

The codebase is type-checked using **[TypeScript](https://www.typescriptlang.org/)**, the formatting is done using **[Prettier](https://github.com/prettier/prettier)** and linting is done using **[TSLint](https://palantir.github.io/tslint/)**. Enforced with commit hooks.

## CI/CD

The page is built and deployed by **[Netlify](https://netlify.com)** when changes are push to `master`. 
