---
title: 畫面布局 (Layout Master)
nav_order: 5036
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 畫面布局 (Layout Master)


## 布局切換

* [設定片段](https://github.com/samwhelp/note-about-hyprland/blob/gh-pages/_demo/config/hyprland-config/main/hyprland.conf#L315-L316)


| 按鍵組合  | 功能                   | 執行指令               |
| ----------| ---------------------- | ---------------------- |
| `Win + grave` | 切換到上一個布局 | `layoutmsg` `orientationprev` (hyprland 內建) |
| `Win + Tab` | 切換到下一個布局 | `layoutmsg` `orientationnext` (hyprland 內建)  |


## Master 個數


| 按鍵組合  | 功能                   | 執行指令               |
| ----------| ---------------------- | ---------------------- |
| `Win + o` | 減少 Master 個數 | `layoutmsg` `removemaster` (hyprland 內建) |
| `Win + p` | 增加 Master 個數 | `layoutmsg` `addmaster` (hyprland 內建)  |
