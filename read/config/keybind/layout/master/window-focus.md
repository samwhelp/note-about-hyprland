---
title: 視窗聚焦切換 (Layout Master)
nav_order: 5023
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 視窗聚焦切換


## 前後聚焦切換

* [設定片段](https://github.com/samwhelp/note-about-hyprland/blob/gh-pages/_demo/config/hyprland-config/main/hyprland.conf#L315-L316)


| 按鍵組合  | 功能                   | 執行指令               |
| ----------| ---------------------- | ---------------------- |
| `Win + a` | 聚焦切換到前面一個視窗 | `cycleprev` (hyprland 內建) |
| `Win + s` | 聚焦切換到後面一個視窗 | `cyclenext` (hyprland 內建)  |


> 一般「切換視窗」的按鍵綁定是在「`Alt + Tab`」。


## 上下左右聚焦切換

* [設定片段](https://github.com/samwhelp/note-about-hyprland/blob/gh-pages/_demo/config/hyprland-config/main/hyprland.conf#L296-L299)

| 按鍵組合  | 功能                   | 執行指令               |
| ----------| ---------------------- | ---------------------- |
| `Win + Up` | 聚焦切換到上方的視窗 | `movefocus` `u` (hyprland 內建) |
| `Win + Down` | 聚焦切換到下方的視窗 | `movefocus` `d` (hyprland 內建)  |
| `Win + Left` | 聚焦切換到左方的視窗 | `movefocus` `l` (hyprland 內建) |
| `Win + Right` | 聚焦切換到右方的視窗 | `movefocus` `r` (hyprland 內建)  |


* [設定片段](https://github.com/samwhelp/note-about-hyprland/blob/gh-pages/_demo/config/hyprland-config/main/hyprland.conf#L303-L306)

| 按鍵組合  | 功能                | 執行指令                         |
| ----------| ----------------- | ------------------------------ |
| `Win + k` | 聚焦切換到上方的視窗 | `movefocus` `u` (hyprland 內建) |
| `Win + j` | 聚焦切換到下方的視窗 | `movefocus` `d` (hyprland 內建)  |
| `Win + h` | 聚焦切換到左方的視窗 | `movefocus` `l` (hyprland 內建) |
| `Win + l` | 聚焦切換到右方的視窗 | `movefocus` `r` (hyprland 內建)  |
