# Typescript-Lite Nodejs Template

A beginner template for using nodejs with typescript.

The typescript config is super lenient, allowing implicit anys which makes converting `.js` files to `.ts` less daunting. Typescript will still encorage types to be used and will only enforce them when necessary for safe transpilation.

## Usage

1. Copy the template using [`degit`](https://github.com/Rich-Harris/degit)

```
npx degit metruzanca/ts-lite-node <project name>
```

2. Install dependencies with your package manager of choice

```
npm i # or pnpm i, yarn
```

3. Run application

In development you can just run `nodemon`. For production, set your CI to use `npm run build` and `npm run start:prod`.
