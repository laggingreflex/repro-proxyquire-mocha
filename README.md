https://github.com/thlorenz/proxyquire/issues/230

```
npm i
```
```
npm start
```
```
TypeError: Cannot read property 'onReady' of undefined
    at Module.load (internal/modules/cjs/loader.js:631:22)
    at tryModuleLoad (internal/modules/cjs/loader.js:560:12)
    at Function.Module._load (internal/modules/cjs/loader.js:552:3)
    at Module.require (internal/modules/cjs/loader.js:659:17)
    at require (internal/modules/cjs/helpers.js:22:18)
    at Object.<anonymous> (C:\<this-repo>\test\b.js:1:82)
    at Module._compile (internal/modules/cjs/loader.js:723:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:734:10)
    at Module.load (internal/modules/cjs/loader.js:620:32)
    at tryModuleLoad (internal/modules/cjs/loader.js:560:12)
```

* Windows 10 1809
* Node 11.4
