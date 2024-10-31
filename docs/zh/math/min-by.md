# minBy

在`数组`中查找通过函数应用到每个元素后的`最小值`。如果数组为空，则返回 `undefined`。

### 使用

```ts
import { minBy } from 'rattail'

minBy([{ n: 5 }, { n: 2 }, { n: 8 }], ({ n }) => n)
// return { n: 2 }
```

### 参数列表

| 参数  |         类型         | 默认值 |
| ----- | :------------------: | -----: |
| `arr` |        `T[]`         |        |
| `fn`  | `(val: T) => number` |        |

### 返回值

|       类型        |
| :---------------: |
| `T  \| undefined` |