---
title: 系統操作
nav_order: 5001
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 系統操作


## 登出

* [設定片段](https://github.com/samwhelp/note-about-hyprland/blob/gh-pages/_demo/config/hyprland-config/main/hyprland.conf#L1228-L229)

| 按鍵組合           | 功能        | 執行指令             |
| ----------------- | ------------ | -------------------- |
| `Alt + Shift + x`  | Show Exit Panel | `wlogout` |
| `Alt + Ctrl + x`  | 登出 | `exit` (hyprland 內建) |


## 關機

* [設定片段](https://github.com/samwhelp/note-about-hyprland/blob/gh-pages/_demo/config/hyprland-config/main/hyprland.conf#L231-L232)

| 按鍵組合           | 功能        | 執行指令             |
| ----------------- | ------------ | -------------------- |
| `Alt + Shift + z`  | Show Exit Panel | `wlogout` |
| `Alt + Ctrl + z`  | 關機 | `systemctl -i poweroff` |
