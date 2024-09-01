---
title: 開啟應用程式 (常用的)
nav_order: 5013
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 開啟應用程式 (常用的)

* [常用的應用程式](#常用的應用程式)




## 常用的應用程式

| 按鍵組合          | 功能           | 執行指令     |
| ----------------- | -------------- | ------------ |
| `Alt + Shift + f` | 開啟檔案管理器 | `pcmanfm-qt` |
| `Alt + Shift + g` | 開啟檔案管理器 | `thunar`     |
| `Alt + Shift + e` | 開啟文字編輯器 | `mousepad`   |
| `Alt + Shift + b` | 開啟網頁瀏覽器 | `firefox --new-tab about:blank`    |
| `Alt + Shift + v` | 開啟音量控制器 | `mate-volume-control`    |
| `Alt + Shift + n` | 開啟網路連接器 | `kitty --class 'nmtui' --title 'Network Settings' nmtui`    |


* [設定片段](https://github.com/samwhelp/hyprland-adjustment/blob/main/prototype/main/hyprland-config/Main/asset/overlay/etc/skel/.config/hypr/hyprland.conf#L321-L330)

```
bind = ALT SHIFT, f, exec, pcmanfm-qt

bind = ALT SHIFT, g, exec, thunar

bind = ALT SHIFT, e, exec, mousepad

bind = ALT SHIFT, b, exec, firefox --new-tab about:blank

bind = ALT SHIFT, v, exec, mate-volume-control

bind = ALT SHIFT, n, exec, kitty --class 'nmtui' --title 'Network Settings' nmtui
```
