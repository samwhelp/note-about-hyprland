---
title: 視窗交換 (Layout Master)
nav_order: 5028
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 視窗交換 (Layout Master)


## 前後交換

* [設定片段](https://github.com/samwhelp/note-about-hyprland/blob/gh-pages/_demo/config/hyprland-config/main/hyprland.conf#L315-L316)


| 按鍵組合  | 功能                   | 執行指令               |
| ----------| ---------------------- | ---------------------- |
| `Win + Shift + a` | 交換到前面一個視窗 | `layoutmsg` `swapprev` (hyprland 內建) |
| `Win + Shift + s` | 交換到後面一個視窗 | `layoutmsg` `swapnext` (hyprland 內建)  |


| 按鍵組合  | 功能                   | 執行指令               |
| ----------| ---------------------- | ---------------------- |
| `Win + grave` | 交換到前面一個視窗 | `swapnext` `prev` (hyprland 內建) |
| `Win + Tab` | 交換到後面一個視窗 | `swapnext` (hyprland 內建)  |


> 關於「grave」指的是「`」，也就是「Tab」上面那個按鍵。


## 與 Master 交換

* [設定片段](https://github.com/samwhelp/note-about-hyprland/blob/gh-pages/_demo/config/hyprland-config/main/hyprland.conf#L315-L316)

| 按鍵組合  | 功能                   | 執行指令               |
| ----------| ---------------------- | ---------------------- |
| `Win + Shift + c` | 與 Master 交換 | `layoutmsg` `swapwithmaster` (hyprland 內建) |


> 也可以在「非 Master 視窗」，透過「`Win + <Mouse Left Click>`」來跟「Master 視窗」交換。
