---
title: 開啟應用程式 (Rofi)
nav_order: 2011
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 開啟應用程式 (Rofi)

* [設定片段](https://github.com/samwhelp/note-about-xfce/blob/gh-pages/_demo/config/xfce-config/main/config/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml#L66-L68)


```xml
<property name="&lt;Shift&gt;&lt;Alt&gt;r" type="string" value="rofi -show run"/>
<property name="&lt;Shift&gt;&lt;Alt&gt;w" type="string" value="rofi -show window -show-icons"/>
<property name="&lt;Shift&gt;&lt;Alt&gt;d" type="string" value="rofi -show drun -show-icons"/>
```


| 按鍵組合          | 功能                           | 執行指令                        |
| ----------------- | ------------------------------ | ------------------------------- |
| `Alt + Shift + d` | 開啟 Rofi (可用應用程式列表)   | `rofi -show drun -show-icons`   |
| `Alt + Shift + w` | 開啟 Rofi (已經開啟的視窗列表) | `rofi -show window -show-icons` |
| `Alt + Shift + r` | 開啟 Rofi (可用指令列表)       | `rofi -show run`                |
