# VSpaceCode(whichkey)
- 窗口化快捷键，挺好用，不用记太多快捷键。
- 可以自定义

## 初始化
- 召唤面面板
```JSON
// settings.json
{
  "vim.normalModeKeyBindingsNonRecursive": [
    {
      "before": ["<space>", ";"],
      "commands": ["vspacecode.space"]
    }
  ],
}

// keybindings.json
{
  {
    "key": "space",
    "command": "vspacecode.space",
    "when": "activeEditorGroupEmpty && focusedView == '' && !whichkeyActive && !inputFocus"
  },
  {
    "key": "space",
    "command": "vspacecode.space",
    "when": "sideBarFocus && !inputFocus && !whichkeyActive"
  },
}
```

## 自定义
```JSON
{
   "vspacecode.bindingOverrides": [
    {
      // 删除
      "keys": "g.s",
      "position": -1
    },
    {
      // 修改 or 添加
      "keys": "g.s",
      "name": "Go to line",
      "type": "command",
      "command": "workbench.action.gotoLine"
    },
    {
      // 整体覆盖
      "keys": "g",
      "name": "Go...",
      "type": "bindings",
      "bindings": [
        {
          "keys": "g.s",
          "name": "Go to line",
          "type": "command",
          "command": "workbench.action.gotoLine"
        }
      ]
    }
  ]
}
```
