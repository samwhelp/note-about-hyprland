---
title: 工作空間切換
nav_order: 5040
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 工作空間切換


## 我個人定義的個工作空間

| 工作空間 | 名稱  |
| -------- | ----- |
| 1        | File  |
| 2        | Edit  |
| 3        | Web   |
| 4        | Term  |
| 5        | Misc  |


## 循環切換

* [設定片段](https://github.com/samwhelp/note-about-hyprland/blob/gh-pages/_demo/config/hyprland-config/main/hyprland.conf#L329-L330)


| 按鍵組合  | 功能                 | 執行指令                   |
| --------- | -------------------- | -------------------------- |
| `Alt + a` | 切換到上一個「工作空間」 | `workspace` `-1` (hyprland 內建) |
| `Alt + s` | 切換到下一個「工作空間」| `workspace` `+1` (hyprland 內建) |


* [設定片段](https://github.com/samwhelp/note-about-hyprland/blob/gh-pages/_demo/config/hyprland-config/main/hyprland.conf#L331)

| 按鍵組合  | 功能                 | 執行指令                   |
| --------- | -------------------- | -------------------------- |
| `Alt + z` | 切換到最近一個「工作空間」| `workspace` `previous` (hyprland 內建) |


> 也可以在「桌面」，使用「滑鼠中鍵」，上下滾動，切換「工作空間」。


## 指定切換

* [設定片段](https://github.com/samwhelp/note-about-hyprland/blob/gh-pages/_demo/config/hyprland-config/main/hyprland.conf#L321-L330)

| 按鍵組合          | 功能     | 執行指令         |
| --------- | -------------------------------------------- | --------------------------------------------------- |
| `Alt + 1` | 切換到「工作空間 1」 | `workspace` `1` (hyprland 內建) |
| `Alt + 2` | 切換到「工作空間 2」 | `workspace` `2` (hyprland 內建) |
| `Alt + 3` | 切換到「工作空間 3」 | `workspace` `3` (hyprland 內建) |
| `Alt + 4` | 切換到「工作空間 4」 | `workspace` `4` (hyprland 內建) |
| `Alt + 5` | 切換到「工作空間 5」 | `workspace` `5` (hyprland 內建) |
| `Alt + 6` | 切換到「工作空間 6」 | `workspace` `6` (hyprland 內建) |
| `Alt + 7` | 切換到「工作空間 7」 | `workspace` `7` (hyprland 內建) |
| `Alt + 8` | 切換到「工作空間 8」 | `workspace` `8` (hyprland 內建) |
| `Alt + 9` | 切換到「工作空間 9」 | `workspace` `9` (hyprland 內建) |
| `Alt + 0` | 切換到「工作空間 10」 | `workspace` `10` (hyprland 內建) |
