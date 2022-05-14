# Next for Designers

Modifying the [React for Designers](https://designcode.io/react) course materials with [Next.js](https://nextjs.org/).

## Next.js [CLI](https://nextjs.org/docs/api-reference/cli)

### Create Next App

`npx create-next-app@latest`

### Development

`next dev` starts the application in development mode with hot-code reloading, error reporting, and more:

The application will start at `http://localhost:3000` by default.

### Build

`next build` creates an optimized production build of your application. The output displays information about each route.

### Production

`next start` starts the application in production mode. The application should be compiled with next build first.

The application will start at `http://localhost:3000` by default.

## Add `.gitignore`

```
.next
node_modules
```

## Update `index.js`

- `title`
- `meta`
- `h1`
- `p`

## Add Components

- `Layout`
- `Nav`
- `Header`

## Add Articles

- `components/ArticleItem.js`
- `components/ArticleList.js`
- `pages/article/`
- `styles/Article.module.css`

## getStaticPaths

## Data

-`data.js`

## API

- `pages/api/articles/[id].js`
- `pages/api/articles/index.js`
