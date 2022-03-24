---
title: 工作空間切換
nav_order: 5040
has_children: false
parent: 使用情境(客製)
grand_parent: 使用情境
---


# 工作空間切換


## 我個人定義的個工作空間

| 工作空間 | 名稱  |
| -------- | ----- |
| 1        | Term  |
| 2        | Edit  |
| 3        | Web   |
| 4        | File  |
| 5        | Misc  |


## 指定切換

* [設定片段](https://github.com/samwhelp/note-about-xfce/blob/gh-pages/_demo/config/xfce-config/main/config/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml#L174)

| 按鍵組合  | 功能                    | 執行指令                       |
| --------- | ----------------------- | ------------------------------ |
| `Alt + 1` | 切換到工作空間 1 (Term) | `workspace_1_key` (xfwm4 內建) |
| `Alt + 2` | 切換到工作空間 2 (Edit) | `workspace_2_key` (xfwm4 內建) |
| `Alt + 3` | 切換到工作空間 3 (Web)  | `workspace_3_key` (xfwm4 內建) |
| `Alt + 4` | 切換到工作空間 4 (File) | `workspace_4_key` (xfwm4 內建) |
| `Alt + 5` | 切換到工作空間 5 (Misc) | `workspace_5_key` (xfwm4 內建) |
| `Alt + 6` | 切換到工作空間 1        | `workspace_6_key` (xfwm4 內建) |
| `Alt + 7` | 切換到工作空間 2        | `workspace_7_key` (xfwm4 內建) |
| `Alt + 8` | 切換到工作空間 3        | `workspace_8_key` (xfwm4 內建) |
| `Alt + 9` | 切換到工作空間 4        | `workspace_9_key` (xfwm4 內建) |
| `Alt + 0` | 切換到工作空間 5        | `workspace_10_key` (xfwm4 內建) |

## 循環切換

* [設定片段](https://github.com/samwhelp/note-about-xfce/blob/gh-pages/_demo/config/xfce-config/main/config/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml#L184)


| 按鍵組合  | 功能                 | 執行指令                   |
| --------- | -------------------- | -------------------------- |
| `Alt + a` | 切換到上一個工作空間 | `workspace prev` (xfwm4 內建) |
| `Alt + s` | 切換到下一個工作空間 | `workspace next` (xfwm4 內建) |


> 也可以在「桌面」，使用「滑鼠中鍵」，上下滾動，切換「工作空間」。

> 也可以在「Panel」的「Workspace區」，使用「滑鼠中鍵」，上下滾動，切換「工作空間」。
