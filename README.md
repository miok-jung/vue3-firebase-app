2023. 11. 15 ~

# Day 2

## unplugin-vue-router

1. 먼저 플러그인을 활성화 한다.

```js
// quasar.config.js | vite.config.ts
// ...
  vitePlugins: [
    [
      'unplugin-vue-router/vite',
    ],
  ],
// ...
```

2. 라우트 세팅을 설정한다.

```js
// src/router/index.js
// ...
import {
  createRouter,
  createMemoryHistory,
  createWebHistory,
  createWebHashHistory,
} from 'vue-router/auto';
// auto 추가
// import routes from './routes' // 제거

// ...
const Router = createRouter({
  // ...
  // routes, // 제거
  // ...
});

return Router;
// ...
```
