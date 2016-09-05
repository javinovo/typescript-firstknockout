# typescript-firstknockout
https://github.com/Microsoft/TypeScript-Handbook/blob/master/pages/tutorials/Knockout.md
https://blogs.msdn.microsoft.com/typescript/2016/06/15/the-future-of-declaration-files/

Build & Run:
- npm update
- node_modules/.bin/tsc
- Browse index.html

Development steps:
- npm init
- npm install --save typescript@next @types/knockout @types/lodash
- mkdir src built externals
- Download externals/knockout-3.4.0.js & externals/require.js
- Create tsconfig.json
- Create src/hello.ts & src/require-config.ts
- Create index.html
- node_modules/.bin/tsc
- Browse index.html
