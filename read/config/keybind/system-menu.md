---
title: 系統選單
nav_order: 2002
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 系統選單


## 顯示「視窗操作選單」

* [設定片段](https://github.com/samwhelp/note-about-xfce/blob/gh-pages/_demo/config/xfce-config/main/config/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml#L166)


``` xml
<property name="&lt;Alt&gt;space" type="string" value="popup_menu_key"/>
```

| 按鍵組合           | 功能        | 執行指令             |
| ----------------- | ------------ | -------------------- |
| `Alt + Space`  | 顯示「視窗操作選單」 | `popup_menu_key` (Xfce 內建) |

> 也可以在「視窗標題列」使用「滑鼠右鍵」，就會顯示「視窗操作選單」。


## 顯示「開始功能表」

* [設定片段](https://github.com/samwhelp/note-about-xfce/blob/gh-pages/_demo/config/xfce-config/main/config/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml#L64)


``` xml
<property name="&lt;Super&gt;space" type="string" value="xfdesktop --menu"/>
```

| 按鍵組合           | 功能        | 執行指令             |
| ----------------- | ------------ | -------------------- |
| `Win + Space`  | 顯示「桌面操作選單」 | `xfdesktop --menu` |


## 顯示「顯示所有開啟視窗」

* [設定片段](https://github.com/samwhelp/note-about-xfce/blob/gh-pages/_demo/config/xfce-config/main/config/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml#L65)


``` xml
<property name="&lt;Super&gt;c" type="string" value="xfdesktop --windowlist"/>
```

| 按鍵組合           | 功能        | 執行指令             |
| ----------------- | ------------ | -------------------- |
| `Win + c`  | Toggle Present Windows (All desktops) | `xfdesktop --windowlist` |



## 顯示「開始功能表 (whiskermenu)」

* [設定片段](https://github.com/samwhelp/note-about-xfce/blob/gh-pages/_demo/config/xfce-config/main/config/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml#L43)


``` xml
<property name="&lt;Alt&gt;F1" type="string" value="xfce4-popup-whiskermenu"/>
```

| 按鍵組合           | 功能        | 執行指令             |
| ----------------- | ------------ | -------------------- |
| `Alt + F1`  | 顯示「whisker menu」 | `xfce4-popup-whiskermenu` |


## Runner

* [設定片段](https://github.com/samwhelp/note-about-xfce/blob/gh-pages/_demo/config/xfce-config/main/config/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml#L44-L46)

``` xml
<property name="&lt;Alt&gt;F2" type="string" value="xfce4-appfinder">
	<property name="startup-notify" type="bool" value="true"/>
</property>
```

| 按鍵組合           | 功能        | 執行指令             |
| ----------------- | ------------ | -------------------- |
| `Alt + F2`  | 執行 Runner | `xfce4-appfinder` |


* [設定片段](https://github.com/samwhelp/note-about-xfce/blob/gh-pages/_demo/config/xfce-config/main/config/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml#L47-L49)

``` xml
<property name="&lt;Alt&gt;F3" type="string" value="xfce4-appfinder --collapsed">
	<property name="startup-notify" type="bool" value="true"/>
</property>
```

| 按鍵組合           | 功能        | 執行指令             |
| ----------------- | ------------ | -------------------- |
| `Alt + F3`  | 執行 Runner | `xfce4-appfinder --collapsed` |


## Task Manager

* [設定片段](https://github.com/samwhelp/note-about-xfce/blob/gh-pages/_demo/config/xfce-config/main/config/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml#L59)

``` xml
<property name="&lt;Primary&gt;Escape" type="string" value="xfce4-taskmanager"/>
```

| 按鍵組合           | 功能        | 執行指令             |
| ----------------- | ------------ | -------------------- |
| `Ctrl + Esc`  | Show Task Manager | `xfce4-taskmanager` |


