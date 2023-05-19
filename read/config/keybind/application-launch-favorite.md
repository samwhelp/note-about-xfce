---
title: 開啟應用程式 (常用的)
nav_order: 2013
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 開啟應用程式 (常用的)


## 常用的應用程式

* [設定片段](https://github.com/samwhelp/note-about-xfce/blob/gh-pages/_demo/config/xfce-config/main/config/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml#L75-L78)

``` xml
<property name="&lt;Shift&gt;&lt;Alt&gt;f" type="string" value="pcmanfm-qt"/>
<property name="&lt;Shift&gt;&lt;Alt&gt;g" type="string" value="thunar"/>
<property name="&lt;Shift&gt;&lt;Alt&gt;e" type="string" value="mousepad"/>
<property name="&lt;Shift&gt;&lt;Alt&gt;b" type="string" value="firefox"/>
```

| 按鍵組合          | 功能           | 執行指令     |
| ----------------- | -------------- | ------------ |
| `Alt + Shift + f` | 開啟檔案管理器 | `pcmanfm-qt` |
| `Alt + Shift + g` | 開啟檔案管理器 | `thunar`     |
| `Alt + Shift + e` | 開啟文字編輯器 | `mousepad`   |
| `Alt + Shift + b` | 開啟網頁瀏覽器 | `firefox`    |



## 常用的系統設定程式

* [設定片段](https://github.com/samwhelp/note-about-xfce/blob/gh-pages/_demo/config/xfce-config/main/config/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml#L55-L59)

``` xml
<property name="&lt;Shift&gt;&lt;Alt&gt;s" type="string" value="xfce4-settings-manager"/>
<property name="&lt;Primary&gt;&lt;Alt&gt;s" type="string" value="xfce4-settings-editor"/>
<property name="&lt;Shift&gt;&lt;Super&gt;s" type="string" value="xfwm4-settings"/>
<property name="&lt;Primary&gt;&lt;Super&gt;s" type="string" value="xfce4-appearance-settings"/>
<property name="&lt;Primary&gt;Escape" type="string" value="xfce4-taskmanager"/>
```

| 按鍵組合          | 功能           | 執行指令     |
| ----------------- | -------------- | ------------ |
| `Alt + Shift + s` | 開啟系統設定程式 | `xfce4-settings-manager` |
| `Alt + Ctrl + s`  | 開啟系統設定程式 | `xfce4-settings-editor`     |
| `Win + Shift + s` | 開啟系統設定程式 | `xfwm4-settings`   |
| `Win + Ctrl + s`  | 開啟系統設定程式 | `xfce4-appearance-settings`    |
