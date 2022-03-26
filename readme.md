# bluestar-NoRecord

## 暂无数据占位图

## 引入

在script标签中引入组件

```typescript
//使用HBuilderX导入插件
import NoRecord from "@/uni_modules/bluestar-NoRecord/components/bluestar-NoRecord/bluestar-NoRecord.vue"

//使用npm install
import NoRecord from "bluestar-norecord/components/bluestar-NoRecord/bluestar-NoRecord.vue"
```

## 代码演示

```vue

<template>
	<NoRecord height="100" backgroundColor="#FFF">暂无数据</NoRecord>
</template>
```

## API

#### Props

| 参数 | 说明 | 类型                | 默认值      |
| :----- | :----- |:------------------|:---------|
| height | 组件高度，单位vh | `number` `string` | 100 |
| backgroundColor | 组件背景色 | `string`          | #FFFFFF  |

#### Slot

| 名称 | 说明 | 默认值 |
| :----- | :----- | :----- |
| - | 自定义内容 | 暂无数据 |

## 作者

![](https://img.shields.io/static/v1?label=蓝星软件&message=@caisheng&labelColor=0E75FC)
