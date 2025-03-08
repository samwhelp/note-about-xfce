---
title: 鍵盤按鍵綁定一覽表
nav_order: 9010
has_children: false
parent: 一覽表
---


# 鍵盤按鍵綁定一覽表




## 主題

* [系統操作](#系統操作)
* [開啟應用程式](#開啟應用程式)
* [視窗操作](#視窗操作)
* [切換](#切換)
* [相關連結](#相關連結)




## 設定檔

> 關於「按鍵綁定」的設定檔

| 設定檔 |
| ----- |
| [~/.config/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml](https://github.com/samwhelp/xfce-adjustment/blob/main/prototype/main/xfce-config/full/Main/asset/overlay/etc/skel/.config/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml) |




## 系統操作


## 系統操作 / 離開系統

| 按鍵組合           | 功能                   | 執行指令                |
| ------------------ | ---------------------- | ----------------------- |
| `Alt + Shift + z`  | 鎖住                   | `xflock4`               |
| `Alt + Shift + x`  | 離開選單 (登出或關機)  | `xfce4-session-logout`  |




## 開啟應用程式


## 開啟應用程式 / 透過「應用程式啟動器」

| 按鍵組合    | 功能                                   | 執行指令                       |
| ----------- | -------------------------------------- | ------------------------------ |
| `Alt + F1`  | 開啟「應用程式啟動主選單(Main Menu)」  | `xfce4-popup-whiskermenu`      |
| `Alt + F2`  | 開啟「應用程式啟動器(Runner)」         | `xfce4-appfinder`              |
| `Alt + F3`  | 開啟「應用程式啟動器(Runner)」         | `xfce4-appfinder --collapsed`  |




## 開啟應用程式 / 透過「Rofi」

| 按鍵組合           | 功能                            | 執行指令                         |
| ------------------ | ------------------------------- | -------------------------------- |
| `Alt + Shift + d`  | 開啟 Rofi (可用應用程式列表)    | `rofi -show drun -show-icons`    |
| `Alt + Shift + w`  | 開啟 Rofi (已經開啟的視窗列表)  | `rofi -show window -show-icons`  |
| `Alt + Shift + r`  | 開啟 Rofi (可用指令列表)        | `rofi -show run`                 |




## 開啟應用程式 / Terminal

| 按鍵組合           | 功能           | 執行指令          |
| ------------------ | -------------- | ----------------- |
| `Alt + Enter`      | 開啟 Terminal  | `xfce4-terminal`  |
| `Alt + Shift + a`  | 開啟 Terminal  | `xfce4-terminal`  |
| `Alt + Ctrl + a`   | 開啟 Terminal  | `sakura`          |
| `Alt + Shift + t`  | 開啟 Terminal  | `xterm`           |
| `Alt + Ctrl + t`   | 開啟 Terminal  | `urxvt`           |


| 按鍵組合           | 功能                     | 執行指令                      |
| ------------------ | ------------------------ | ----------------------------- |
| `Alt + Shift + y`  | 開啟 Drop Down Terminal  | `xfce4-terminal --drop-down`  |




## 開啟應用程式 / 常用的應用程式

| 按鍵組合           | 功能            | 執行指令                         |
| ------------------ | --------------- | -------------------------------- |
| `Alt + Shift + f`  | 開啟檔案管理器  | `thunar`                         |
| `Alt + Shift + g`  | 開啟檔案管理器  | `pcmanfm-qt`                     |
| `Alt + Shift + e`  | 開啟文字編輯器  | `mousepad`                       |
| `Alt + Shift + b`  | 開啟網頁瀏覽器  | `firefox --new-tab about:blank`  |
| `Alt + Shift + v`  | 開啟系統設定    | `pavucontrol`                    |


| 按鍵組合           | 功能                  | 執行指令                     |
| ------------------ | --------------------- | ---------------------------- |
| `Alt + Shift + s`  | 開啟系統設定          | `xfce4-settings-manager`     |
| `Alt + Ctrl + s`   | 開啟系統設定值編輯器  | `xfce4-settings-editor`      |
| `Win + Shift + s`  | 開啟視窗管理器設定    | `xfwm4-settings`             |
| `Win + Ctrl + s`   | 開啟外觀設定          | `xfce4-appearance-settings`  |


| 按鍵組合      | 功能                | 執行指令                            |
| ------------- | ------------------- | ----------------------------------- |
| `Ctrl + Esc`  | 開啟程序管理器      | `xfce4-taskmanager`                 |
| `Win + p`     | 開啟螢幕解析度設定  | `xfce4-display-settings --minimal`  |




## 視窗操作

| 按鍵組合       | 功能                               | 設定項目               |
| -------------- | ---------------------------------- | ---------------------- |
| `Alt + Space`  | 顯示「視窗功能選單」               | `popup_menu_key`       |
| `Win + q`      | 關閉視窗                           | `close_window_key`     |
| `Win + f`      | 視窗全螢幕                         | `fullscreen_key`       |
| `Win + w`      | 視窗最大化                         | `maximize_window_key`  |
| `Win + x`      | 視窗最小化                         | `hide_window_key`      |
| `Win + d`      | 切換「顯示桌面」                   | `show_desktop_key`     |
| `Win + e`      | 開始「視窗移動」                   | `move_window_key`      |
| `Win + r`      | 開始「視窗更改大小」               | `resize_window_key`    |
| `Win + t`      | 視窗保持永遠在最上方               | `above_key`            |
| `Win + y`      | 視窗內容區塊收合                   | `shade_window_key`     |


> 一般預設「`Alt + F4`」綁定「`視窗關閉`」

> 一般預設「`F11`」綁定「`視窗全螢幕`」




## 切換

## 切換 / 視窗

| 按鍵組合     | 功能                        | 設定項目                     |
| ------------ | --------------------------- | ---------------------------- |
| `Win + a`    | 聚焦切換到「前面一個視窗」  | `cycle_reverse_windows_key`  |
| `Win + s`    | 聚焦切換到「後面一個視窗」  | `cycle_windows_key`          |


> 一般預設「`Alt + Tab`」綁定「`視窗聚焦切換`」




## 切換 / 工作空間

| 按鍵組合   | 功能                      | 設定項目              |
| ---------- | ------------------------- | --------------------- |
| `Alt + a`  | 切換到「上一個工作空間」  | `prev_workspace_key`  |
| `Alt + s`  | 切換到「下一個工作空間」  | `next_workspace_key`  |




## 切換 / 概覽

> 無。




## 相關連結

| 相關連結 |
| ------- |
| [鍵盤按鍵綁定](https://samwhelp.github.io/note-about-xfce/read/config/keybind.html) |
