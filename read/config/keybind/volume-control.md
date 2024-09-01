---
title: 音量控制
nav_order: 5052
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 音量控制


* [pamixer 版本](#pamixer-版本)
* [amixer 版本](#amixer-版本)




## pamixer 版本

| 按鍵組合               | 功能           | 執行指令                                    |
| ---------------------- | -------------- | ------------------------------------------- |
| `XF86_AudioMute (XF86AudioMute)`        | 音量切換成靜音 | `pamixer --toggle-mute`     |
| `XF86_AudioLowerVolume (XF86AudioLowerVolume)` | 減小音量       | `pamixer -d 5` |
| `XF86_AudioRaiseVolume (XF86AudioRaiseVolume)` | 增加音量       | `pamixer -i 5` |


* [設定片段](https://github.com/samwhelp/hyprland-adjustment/blob/main/prototype/main/hyprland-config/Main/asset/overlay/etc/skel/.config/hypr/hyprland.conf#L475-L477)

```
bind = , XF86AudioMute, exec, pamixer --toggle-mute

bind = , XF86AudioLowerVolume, exec, pamixer -d 10

bind = , XF86AudioRaiseVolume, exec, pamixer -i 10
```




| 按鍵組合          | 功能             | 執行指令                                    |
| ----------------- | ---------------- | ------------------------------------------- |
| `Alt + Shift + v` | 開啟音量控制面板 | `mate-volume-control`                       |


* [設定片段](https://github.com/samwhelp/hyprland-adjustment/blob/main/prototype/main/hyprland-config/Main/asset/overlay/etc/skel/.config/hypr/hyprland.conf#L329)

```
bind = ALT SHIFT, v, exec, mate-volume-control
```




| 按鍵組合          | 功能             | 執行指令                                    |
| ----------------- | ---------------- |
| `Alt + m`         | 音量切換成靜音   | `amixer -q -D pulse sset Master toggle`     |


| 按鍵組合          | 功能             | 執行指令                                    |
| ----------------- | ---------------- |
| `Alt + Shift + <` | 減小音量         | `pamixer -d 10` |
| `Alt + Shift + >` | 增加音量         | `pamixer -i 10` |


| 按鍵組合          | 功能             | 執行指令                                    |
| ----------------- | ---------------- |
| `Alt + Ctrl + ,`  | 緩慢地減小音量   | `pamixer -d 5` |
| `Alt + Ctrl + .`  | 緩慢地增加音量   | `pamixer -i 5` |


* [設定片段](https://github.com/samwhelp/hyprland-adjustment/blob/main/prototype/main/hyprland-config/Main/asset/overlay/etc/skel/.config/hypr/hyprland.conf#L480-L486)

```
bind = ALT, m, exec, pamixer --toggle-mute

bind = ALT SHIFT, comma, exec, pamixer -d 10
bind = ALT SHIFT, period, exec, pamixer -i 10

bind = ALT CTRL, comma, exec, pamixer -d 5
bind = ALT CTRL, period, exec, pamixer -i 5
```








## amixer 版本

| 按鍵組合               | 功能           | 執行指令                                    |
| ---------------------- | -------------- | ------------------------------------------- |
| `XF86AudioMute`        | 音量切換成靜音 | `amixer -q -D pulse sset Master toggle`     |
| `XF86AudioLowerVolume` | 減小音量       | `amixer -q -D pulse sset Master 5%- unmute` |
| `XF86AudioRaiseVolume` | 增加音量       | `amixer -q -D pulse sset Master 5%+ unmute` |


* [設定片段](https://github.com/samwhelp/hyprland-adjustment/blob/main/prototype/main/hyprland-config/Main/asset/overlay/etc/skel/.config/hypr/hyprland.conf#L451-L453)

```
bind = , XF86AudioMute, exec, amixer -q -D pulse sset Master toggle

bind = , XF86AudioLowerVolume, exec, amixer -q -D pulse sset Master 5%- unmute

bind = , XF86AudioRaiseVolume, exec, amixer -q -D pulse sset Master 5%+ unmute
```




| 按鍵組合          | 功能             | 執行指令                                    |
| ----------------- | ---------------- | ------------------------------------------- |
| `Alt + Shift + v` | 開啟音量控制面板 | `mate-volume-control`                       |


* [設定片段](https://github.com/samwhelp/hyprland-adjustment/blob/main/prototype/main/hyprland-config/Main/asset/overlay/etc/skel/.config/hypr/hyprland.conf#L329)

```
bind = ALT SHIFT, v, exec, mate-volume-control
```




| 按鍵組合          | 功能             | 執行指令                                    |
| ----------------- | ---------------- |
| `Alt + m`         | 音量切換成靜音   | `amixer -q -D pulse sset Master toggle`     |


| 按鍵組合          | 功能             | 執行指令                                    |
| ----------------- | ---------------- |
| `Alt + Shift + <` | 減小音量         | `amixer -q -D pulse sset Master 5%- unmute` |
| `Alt + Shift + >` | 增加音量         | `amixer -q -D pulse sset Master 5%+ unmute` |


| 按鍵組合          | 功能             | 執行指令                                    |
| ----------------- | ---------------- |
| `Alt + Ctrl + ,`  | 緩慢地減小音量   | `amixer -q -D pulse sset Master 1%- unmute` |
| `Alt + Ctrl + .`  | 緩慢地增加音量   | `amixer -q -D pulse sset Master 1%+ unmute` |


* [設定片段](https://github.com/samwhelp/hyprland-adjustment/blob/main/prototype/main/hyprland-config/Main/asset/overlay/etc/skel/.config/hypr/hyprland.conf#L456-L462)

```
bind = ALT, m, exec, amixer -q -D pulse sset Master toggle

bind = ALT SHIFT, comma, exec, amixer -q -D pulse sset Master 5%- unmute
bind = ALT SHIFT, period, exec, amixer -q -D pulse sset Master 5%+ unmute

bind = ALT CTRL, comma, exec, amixer -q -D pulse sset Master 1%- unmute
bind = ALT CTRL, period, exec, amixer -q -D pulse sset Master 1%+ unmute
```




## 用法對照

* [螢幕亮度控制](https://samwhelp.github.io/note-about-ultramarine-hyprland/read/config/keybind/monitor-brightness-control.html)
