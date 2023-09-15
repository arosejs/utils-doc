---
title: 生成随机数
group:
  title: 工具类
nav:
  title: 工具类
  order: 1
---

## 生成随机数

```js
import { getRandom } from '@arosejs/utils';

const num = getRandom(6);

console.log(num); // jw123m
```

| 参数   | 说明             | 类型   | 默认值 | 是否必填 |
| ------ | ---------------- | ------ | ------ | -------- |
| 参数 1 | 生成随机数的位数 | number | 6      | 否       |
