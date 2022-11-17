# data-types

> 一个用于判断`javascript`变量类型的库，简单，便捷，开箱即用，提供了很多方法用于使用。


# 安装

```
npm i @savage181855/data-types
```

# 使用说明

```typescript
import { dataTypes } from "@savage181855/data-types";

console.log(dataTypes.isUndefined(undefined));

console.log(dataTypes.isNull(null));

console.log(dataTypes.isString(""));

console.log(dataTypes.isNumber("1"));

console.log(dataTypes.isString(""));

console.log(dataTypes.isString(""));

console.log(dataTypes.isArray([]));

console.log(dataTypes.isObject({}));

console.log(dataTypes.isMap(new Map()));
```
