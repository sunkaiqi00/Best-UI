## 安装

### npm 安装

```
npm i best-ui -S
# or
yarn add best-ui
```

## 快速上手

本节将介绍如何在项目中使用 best-ui。

### 引入 best-ui

你可以引入整个 best-ui，或是根据需要仅引入部分组件。我们先介绍如何引入完整的 best-ui。

#### 完整引入

在 main.js 中写入以下内容：

```javascript
import Vue from 'vue'
import App from './App.vue'
import BestUI from 'best-ui'
import 'best-ui/lib/styles/index.css'

Vue.use(BestUI)
```

以上代码便完成了 best-ui 的引入。需要注意的是，样式文件需要单独引入。
