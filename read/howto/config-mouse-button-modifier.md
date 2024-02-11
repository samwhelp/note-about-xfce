---
title: 設定 Mouse Button Modifier
nav_order: 7021
has_children: false
parent: 如何
---


# 設定 Mouse Button Modifier


## 相關設定指令


### Win

執行下面指令，將「Mouse Button Modifier」設定成「Super鍵」，也就是「Win鍵」。

``` sh
xfconf-query --channel xfwm4 --property "/general/easy_click" --set "Super" --type "string" --create
```

執行上面的指令後，就可以[在視窗操作下面兩個動作](https://samwhelp.github.io/note-about-xfce/read/config/mousebind.html#視窗內容區塊)，

| 滑鼠按鍵組合                |  功能                   |
| --------------------------- | ----------------------- |
| `Win + [滑鼠左鍵按住拖曳]`  | 視窗移動                |
| `Win + [滑鼠右鍵按住拖曳]`  | 視窗更改大小            |


上面的設定值，是保存在「`~/.config/xfce4/xfconf/xfce-perchannel-xml/xfwm4.xml`」這個檔案。

可以執行下面指令來檢查

``` sh
grep 'easy_click' ~/.config/xfce4/xfconf/xfce-perchannel-xml/xfwm4.xml
```

顯示

``` xml
   <property name="easy_click" type="string" value="Super"/>
```




### Alt

執行下面指令，則是將「Mouse Button Modifier」設定為「Alt鍵」。

``` sh
xfconf-query --channel xfwm4 --property "/general/easy_click" --set "Alt" --type "string" --create
```




## 圖形介面程式操作

也可以透過「`xfwm4-tweaks-settings` (Window Manager Tweaks)」這個「圖形介面程式」來操作，

在「Accessibility」這個「頁面」，

有一個選項「Key used to grab and move windows:」，

接著有一個「下拉選單」，可以選擇「Super」或「Alt」或是其他的按鍵。




## 相關議題

| 相關議題 |
| ------- |
| [滑鼠按鍵綁定](https://samwhelp.github.io/note-about-xfce/read/config/mousebind.html#視窗內容區塊) |


## 相關應用

* Menu Applet 開發筆記 / [demo-mouse-button-modifier](https://samwhelp.github.io/note-about-menu-applet/read/demo/demo-mouse-button-modifier.html#xfce)
