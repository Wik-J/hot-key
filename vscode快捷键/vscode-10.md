# 终端操作

## 打开
- ctrl + ` ——> cmd + ,（workbench.action.terminal.toggleTerminal）
- cmd + j

## 清空
- cmd + k

## 分屏
- cmd + \

## 分屏切换
- cmd + [
- workbench.action.terminal.focusPreviousPane
- cmd + ]
- workbench.action.terminal.focusNextPane

## 关闭
- shift + alt + q
- workbench.action.terminal.kill

## 新建
- shift + alt + n
- workbench.action.terminal.new

## 切换窗口(不是分屏情况下)
- shift + cmd + [
- shift + cmd + ]

## 直接打开终端
- shift + cmd + c
```json (settings.json)
    "terminal.external.osxExec": "iTerm.app"
```

## iterm 终端
- 新建分屏（左右）
- command d

- 新建分屏（上下）
- command + shift + d

- 新建窗口
- command + t

- 关闭窗口 
- command + w

- 左右屏切换
- command + [ 或 ]