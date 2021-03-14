

## theme-package

* [numix-blue-gtk-theme](https://packages.ubuntu.com/focal/numix-blue-gtk-theme)

``` sh
$ sudo apt-get install numix-blue-gtk-theme
```

* [/usr/share/themes/NumixBlue/](file:///usr/share/themes/NumixBlue/)

## set

``` sh
$ xfconf-query -c 'xfwm4' -p '/general/theme' -s 'NumixBlue'
```

## get

run

``` sh
$ xfconf-query -c 'xfwm4' -p '/general/theme'
```

show

```
NumixBlue
```

## config file

* ~/.config/xfce4/xfconf/xfce-perchannel-xml/xfwm4.xml

run

``` sh
$ grep name=\"theme\" ~/.config/xfce4/xfconf/xfce-perchannel-xml/xfwm4.xml
```

show

```
    <property name="theme" type="string" value="NumixBlue"/>
```

## tool

* [style-ctrl-xfce](https://github.com/samwhelp/play-ubuntu-20.04-plan/blob/master/project/style-xfce/style-ctrl/style-ctrl-xfce#L311)
