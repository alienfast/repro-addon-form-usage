# reproduction for https://github.com/storybookjs/addon-kit/issues/84

1. `yarn install`
2. `yarn storybook`
3. Open browser and inspect console

```
TypeError: can't access property "recentlyCreatedOwnerStacks", ReactSharedInternals is undefined
    jsx http://localhost:7008/sb-addons/alienfast-form-1/manager-bundle.js:57707
    y http://localhost:7008/sb-addons/alienfast-form-1/manager-bundle.js:61292
    K_ http://localhost:7008/sb-manager/globals-runtime.js:3277
    Aq http://localhost:7008/sb-manager/globals-runtime.js:5795
    _q http://localhost:7008/sb-manager/globals-runtime.js:5546
    Pge http://localhost:7008/sb-manager/globals-runtime.js:5538
    lg http://localhost:7008/sb-manager/globals-runtime.js:5527
    b_ http://localhost:7008/sb-manager/globals-runtime.js:5303
    xq http://localhost:7008/sb-manager/globals-runtime.js:5253
    oC http://localhost:7008/sb-manager/globals-runtime.js:366
    Z4 http://localhost:7008/sb-manager/globals-runtime.js:393
```