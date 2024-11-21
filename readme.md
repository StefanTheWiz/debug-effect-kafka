```shell
nvm use
corepack enable
yarn
yarn demo
```
Demo returns:
```
node:internal/modules/esm/resolve:265
    throw new ERR_MODULE_NOT_FOUND(
          ^

Error [ERR_MODULE_NOT_FOUND]: Cannot find module '/path/to/project/debug-effect-kafka/node_modules/effect-kafka/dist/esm/Consumer' imported from /path/to/project/debug-effect-kafka/node_modules/effect-kafka/dist/esm/index.js
    at finalizeResolution (node:internal/modules/esm/resolve:265:11)
    at moduleResolve (node:internal/modules/esm/resolve:933:10)
    at defaultResolve (node:internal/modules/esm/resolve:1169:11)
    at ModuleLoader.defaultResolve (node:internal/modules/esm/loader:540:12)
    at ModuleLoader.resolve (node:internal/modules/esm/loader:509:25)
    at ModuleLoader.getModuleJob (node:internal/modules/esm/loader:239:38)
    at ModuleWrap.<anonymous> (node:internal/modules/esm/module_job:96:40)
    at link (node:internal/modules/esm/module_job:95:36) {
  code: 'ERR_MODULE_NOT_FOUND',
  url: 'file:///path/to/project/debug-effect-kafka/node_modules/effect-kafka/dist/esm/Consumer'
}

Node.js v20.17.0
```