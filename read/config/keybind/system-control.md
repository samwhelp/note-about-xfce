---
title: 系統操作
nav_order: 2001
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 系統操作


## 切換「顯示桌面」

* [設定片段](https://github.com/samwhelp/note-about-xfce/blob/gh-pages/_demo/config/xfce-config/main/config/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml#L215)

``` xml
<property name="&lt;Super&gt;d" type="string" value="show_desktop_key"/>
```

| 按鍵組合           | 功能        | 執行指令             |
| ----------------- | ------------ | -------------------- |
| `Win + d`  | 顯示「桌面操作選單」 | `show_desktop_key` (xfwm4 內建) |

> 也可以使用「滑鼠左鍵」，在「Panel」的「顯示桌面按鈕」，切換「顯示桌面」，可反覆按下做切換。


## 登出

* [設定片段](https://github.com/samwhelp/note-about-xfce/blob/gh-pages/_demo/config/xfce-config/main/config/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml#L69)

``` xml
<property name="&lt;Primary&gt;&lt;Alt&gt;Delete" type="string" value="xfce4-session-logout"/>
```

| 按鍵組合           | 功能        | 執行指令             |
| ----------------- | ------------ | -------------------- |
| `Alt + Shift + x`  | 顯示「離開操作對話框」 | `xfce4-session-logout` |

* [設定片段](https://github.com/samwhelp/note-about-xfce/blob/gh-pages/_demo/config/xfce-config/main/config/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml#L61)

``` xml
<property name="&lt;Shift&gt;&lt;Alt&gt;x" type="string" value="xfce4-session-logout"/>
```

| 按鍵組合           | 功能        | 執行指令             |
| ----------------- | ------------ | -------------------- |
| `Ctrl + Alt + Delete`  | 顯示「離開操作對話框」 | `xfce4-session-logout` |


## 休眠

* [設定片段](https://github.com/samwhelp/note-about-xfce/blob/gh-pages/_demo/config/xfce-config/main/config/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml#L215)

``` xml
<property name="&lt;Shift&gt;&lt;Alt&gt;z" type="string" value="xflock4"/>
```

| 按鍵組合           | 功能        | 執行指令             |
| ----------------- | ------------ | -------------------- |
| `Alt + Shift + z` | 休眠 | `xflock4` |
