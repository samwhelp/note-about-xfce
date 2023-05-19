---
title: 開啟應用程式 (Terminal)
nav_order: 2010
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 開啟應用程式 (Terminal)

* [設定片段](https://github.com/samwhelp/note-about-xfce/blob/gh-pages/_demo/config/xfce-config/main/config/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml#L69-L74)

``` xml
<property name="&lt;Alt&gt;Return" type="string" value="sakura -m"/>
<property name="&lt;Shift&gt;&lt;Alt&gt;a" type="string" value="sakura -m"/>
<property name="&lt;Primary&gt;&lt;Alt&gt;a" type="string" value="xfce4-terminal --maximize"/>
<property name="&lt;Shift&gt;&lt;Alt&gt;y" type="string" value="xfce4-terminal --drop-down"/>
<property name="&lt;Shift&gt;&lt;Alt&gt;t" type="string" value="xterm"/>
<property name="&lt;Primary&gt;&lt;Alt&gt;t" type="string" value="urxvt"/>
```


| 按鍵組合           | 功能         | 執行指令         |
| ----------------- | ------------- | ---------------- |
| `Alt + Enter`     | 開啟 Terminal | `sakura -m`         |
| `Alt + Shift + a` | 開啟 Terminal | `sakura -m`         |
| `Alt + Ctrl + a`  | 開啟 Terminal | `xfce4-terminal --maximize` |
| `Alt + Shift + y`  | 開啟 Terminal | `xfce4-terminal --drop-down` |
| `Alt + Shift + t` | 開啟 Terminal | `xterm`          |
| `Alt + Ctrl + t`  | 開啟 Terminal | `urxvt`          |
