# 第九天

## 更加高效的移动
- 两个 vim 插件
- 目的一样  快速的移动光标

## vim-easymotion
> 快速搜索某个单词
> <leader> 已经被我改为 <Space>
- <leader> + <leader> + w —— 向下搜字的开头
- <leader> + <leader> + b —— 向上搜字的开头
- <leader> + <leader> + j —— 向下搜行
- <leader> + <leader> + k —— 向上搜行

## vim-sneak 
> 用来替代 f 可以输入2个字符
- 改建
  - 替换原生的 f
  - 利用映射来实现原有的s/S/z/Z
- v/normal + f + 2char
- operation + z + 2cahr

## 感受
> 远距离用 easymotion
> 近距离用 sneak


```js
function fn(){
  // fn fn
  const a = 1;
  return a;
}
```