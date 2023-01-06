# DOCS

`mkdir cypress-typescript`

`cd cypress-typescript`

`npm init -y`

add `dependencies` and `devDependencies` to the [package.json](../src/package.json).

Added a [.env](../src/.env) file with `SERVER_PORT` and `HOST_URL`
Created a [.gitignore](../.gitignore)

Added [tsconfig.json](../src/tsconfig.json) and [tslint.json](../src/tslint.json) files.
Added `lint` command to [package.json](../src/package.json)

Create a `src`, `dist` and `tools` folder.

Create new folders and files

```
public
routes
├── index.ts
views
├── partials
│   ├── footer.ejs
│   └── header.ejs
├── about.ejs
└── index.ejs
index.ts
```

Create a new file [copyAssets.ts](../src/tools/copyAssets.ts) in the [tools](../src/tools/) folder.

## eslint

- https://khalilstemmler.com/blogs/typescript/eslint-for-typescript/

`npm install --save-dev eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin`

`touch .eslintrc`

`touch .eslintignore`

Update `lint` command in [package.json](../src/package.json)

`"lint": "eslint . --ext .ts"`
