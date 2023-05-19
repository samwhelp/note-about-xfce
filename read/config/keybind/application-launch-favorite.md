---
title: 開啟應用程式 (常用的)
nav_order: 2013
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 開啟應用程式 (常用的)


## 常用的

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
