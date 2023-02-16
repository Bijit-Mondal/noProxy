## Steps of Developing
### Installation Of Ionic Vue and Typescript removal

```npm install -g @ionic/cli```
```ionic start noBunk --type vue```
```cd noBunk```
```npm uninstall --save typescript @types/jest @typescript-eslint/eslint-plugin @typescript-eslint/parser @vue/cli-plugin-typescript @vue/eslint-config-typescript```

> Change all .ts files to .js. In a blank Ionic Vue app, this should only be router/index.ts and main.ts. Remove @vue/typescript/recommended and @typescript-eslint/no-explicit-any: ‘off’, from .eslintrc.js.
Remove Array<RouteRecordRaw> from router/index.js. Delete the shims-vue.d.ts file. Remove lang="ts" from the script tags in any of your Vue components that have them. In a blank Ionic Vue app, this should only be App.vue and views/Home.vue.
