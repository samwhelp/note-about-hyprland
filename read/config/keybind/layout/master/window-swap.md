---
title: 視窗交換 (Layout Master)
nav_order: 5028
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 視窗交換


## 前後交換

* [設定片段](https://github.com/samwhelp/note-about-hyprland/blob/gh-pages/_demo/config/hyprland-config/main/hyprland.conf#L315-L316)


| 按鍵組合  | 功能                   | 執行指令               |
| ----------| ---------------------- | ---------------------- |
| `Win + Shift + a` | 交換到前面一個視窗 | `layoutmsg` `swapprev` (hyprland 內建) |
| `Win + Shift + s` | 交換到後面一個視窗 | `layoutmsg` `swapnext` (hyprland 內建)  |


## 與 Master 交換

* [設定片段](https://github.com/samwhelp/note-about-hyprland/blob/gh-pages/_demo/config/hyprland-config/main/hyprland.conf#L315-L316)

| 按鍵組合  | 功能                   | 執行指令               |
| ----------| ---------------------- | ---------------------- |
| `Win + Shift + c` | 與 Master 交換 | `layoutmsg` `swapwithmaster` (hyprland 內建) |
