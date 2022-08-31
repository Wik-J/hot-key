# 第六天
## 文本对象
- 可以快速选择
- 范围

> 语法
- operator + (内部/外部) + 文本对象
- 可视模式 + (内部/外部) + 文本对象

> operator
- d —— 删除
- c —— 删除并插入
- v —— 进入可视化
- y —— 复制

内部 —— i
外部 —— a

> 对象
- w —— 一个单词
- (或) —— 一对()
- b —— 一对()
- [或] —— 一对[]
- {或} —— 一对{}
- B —— 一对{}
- <>
- t —— XML标签
- '
- "
- `
- s —— 一个句子
- p —— 一个段落

## vim-textobj-arguments
- ia 不包含分割符
- aa 包含分割符
- dia 删除一个入参
- cia 修改一个入参

## vim-textobj-entire
- ae 删除当前文档所有内容
- ie 删除当前文档除了前后空格外的所有内容

```js
function handler(sdfa, sdfb){
  const a = 1
  return a
}
```