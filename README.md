PS C:\Users\Timur-SuperStrimer\Desktop\Clone> npm run start

> clone@1.0.0 start
> node src/index.js

node:internal/modules/cjs/loader:1080
  throw err;
  ^

Error: Cannot find module '@netology-code/ajs'
Require stack:
- C:\Users\Timur-SuperStrimer\Desktop\Clone\src\index.js
    at Module._resolveFilename (node:internal/modules/cjs/loader:1077:15)
    at Module._load (node:internal/modules/cjs/loader:922:27)
    at Module.require (node:internal/modules/cjs/loader:1143:19)
    at require (node:internal/modules/cjs/helpers:121:18)
    at Object.<anonymous> (C:\Users\Timur-SuperStrimer\Desktop\Clone\src\index.js:2:13)
    at Module._compile (node:internal/modules/cjs/loader:1256:14)
    at Module._extensions..js (node:internal/modules/cjs/loader:1310:10)
    at Module.load (node:internal/modules/cjs/loader:1119:32)
    at Module._load (node:internal/modules/cjs/loader:960:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:81:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [ 'C:\\Users\\Timur-SuperStrimer\\Desktop\\Clone\\src\\index.js' ]
}

Node.js v18.17.1
