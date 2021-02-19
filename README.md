# vue3-ts-prettier

## how I create
```
vue create vue3-ts-prettier
vue add typescript
install Eslint、Prettier、Vetur in vscode
npm i -D eslint babel-eslint eslint-plugin-vue @vue/cli-plugin-eslint 
(eslint: ESLint 的核心代码
babel-eslint: eslint 与 babel 整合包
eslint-plugin-vue @vue/cli-plugin-eslint: eslint 与 vue 整合包)
npm i -D prettier eslint-plugin-prettier eslint-config-prettier prettier-eslint-cli
(prettier：prettier 插件的核心代码
eslint-plugin-prettier：将 prettier 作为 ESLint 规范来使用
eslint-config-prettier：解决 ESLint 中的样式规范和 prettier 中样式规范的冲突，以 prettier 的样式规范为准，使 ESLint 中的样式规范自动失效
prettier-eslint-cli:prettier-eslint-cli 允许你对多个文件用 prettier-eslint 进行格式化。)
touch .eslintrc.js
touch .prettierrc.js
```
y## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
