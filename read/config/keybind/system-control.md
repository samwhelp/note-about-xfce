---
title: 系統操作
nav_order: 2001
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 系統操作


* [設定片段](https://github.com/samwhelp/note-about-xfce/blob/gh-pages/_demo/config/xfce-config/main/config/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml#L49)

| 按鍵組合           | 功能        | 執行指令             |
| ----------------- | ------------ | -------------------- |
| `Ctrl + Alt + Delete`  | 重新套用設定 | `xflock4` |


## 顯示「視窗操作選單」

* [設定片段](https://github.com/samwhelp/note-about-xfce/blob/gh-pages/_demo/config/xfce-config/main/config/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml#L171)

| 按鍵組合           | 功能        | 執行指令             |
| ----------------- | ------------ | -------------------- |
| `Alt + Space`  | 顯示「視窗操作選單」 | `popup_menu_key` (xfwm4 內建) |

> 也可以在「視窗標題列」使用「滑鼠右鍵」，就會顯示「視窗操作選單」。


## 顯示「桌面操作選單」

* [設定片段](https://github.com/samwhelp/note-about-xfce/blob/gh-pages/_demo/config/xfce-config/main/config/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml#L72)

| 按鍵組合           | 功能        | 執行指令             |
| ----------------- | ------------ | -------------------- |
| `Win + Space`  | 顯示「桌面操作選單」 | `xfdesktop --menu` |

> 也可以在「桌面」使用「滑鼠右鍵」，就會顯示「桌面操作選單」。


## 顯示「工作空間操作選單」

* [設定片段](https://github.com/samwhelp/note-about-xfce/blob/gh-pages/_demo/config/xfce-config/main/config/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml#L73)

| 按鍵組合           | 功能        | 執行指令             |
| ----------------- | ------------ | -------------------- |
| `Win + c`  | 顯示「桌面操作選單」 | `xfdesktop --windowlist` |

> 也可以在「桌面」使用「滑鼠中鍵」，就會顯示「工作空間操作選單」。


## 切換「顯示桌面」

* [設定片段](https://github.com/samwhelp/note-about-xfce/blob/gh-pages/_demo/config/xfce-config/main/config/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml#L199)

| 按鍵組合           | 功能        | 執行指令             |
| ----------------- | ------------ | -------------------- |
| `Win + d`  | 顯示「桌面操作選單」 | `show_desktop_key` (xfwm4 內建) |

> 也可以使用「滑鼠左鍵」，在「Panel」的「顯示桌面按鈕」，切換「顯示桌面」，可反覆按下做切換。
