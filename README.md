# html-and-ts-starter

HTML and TypeScript small starter.

# Usage

1. Install dependencies after clone this repository.

```
 $ yarn install
```

1. Start to auto compiler.
   `.ts` files at `.src/ts/*` are auto compile to `.dist/js/*`.

```
 $ npx tsc --watch
```

2. Server start
   To refresh browser when you edit the source file.
   Set up a this server for it.

- When Using VSCode
  Recommend to you add [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) Extension.

- Other
  Please use [lite-server](https://github.com/johnpapa/lite-server).

```
 $ yarn start
```
