# 第十二天

## 处理包裹字符的符号

## vim-surround 
- 改变 —— c + s + 现存包裹符号 + 目标包裹符号
- 添加 —— y + s + 动作 + 包裹符号
- 删除 —— d + s + 现存包裹符号
- 可视化话模式下添加 —— S + 包裹符号 
  - 适用于给多个字符添加

```js
function fun(){
  const name = `jack  wo`
  const age = `28${name}`
  const a = 1;
  return a;
}
```