# React Component Library Template

You can use this repo to fork as a template for your own React library projects.

## Using

- [React](https://reactjs.org/)
- [Babel](https://babeljs.io/)
- [Rollup](https://rollupjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Sass](https://sass-lang.com/)
- [PostCSS](https://postcss.org/)
- [Jest](https://jestjs.io/pt-BR/)
- [Storybook](https://storybook.js.org/)

## Available Scripts

### Build the library

```
npm run rollup
```

### Publish the library

```
npm publish
```

### Run tests

```
npm run test
```

### Run storybook locally

```
npm run storybook
```

### Build storybook

```
npm run build-storybook
```

---

## Using

```bash
npm install @thompsonemerson/frontend-lib
```

```jsx
import { Button } from '@thompsonemerson/frontend-lib';

const MyApp = () => {
  return (
    <div>
      <Button>Hello button!</Button>
    </div>
  );
};
```

## Structure

```
.
├── src
│   ├── components
|   │   ├── Button
|   |   │   ├── Button.scss
|   |   │   ├── Button.stories.tsx
|   |   │   ├── Button.test.tsx
|   |   │   ├── Button.tsx
|   |   │   └── index.ts
|   │   └── index.ts
│   └── index.ts
├── package.json
├── package-lock.json
└── ...
```
