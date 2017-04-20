---
title: Build ChezScheme on windows 7
date: 2017-04-20 12:29:39
tags:
---


## 1,Install msys2


## 2,Install visual studio 2015 and launch "vs2015 x64 native tools command prompt", from this terminal, run 
``` bash
c:\msys64\msys2_shell.bat
```

## 3,Install gcc and git

run 
``` bash
pacman -S gcc base-devel
pacman -S git
```

## 4,configure and make

``` bash
 ./configure -m=i3nt
make
```


## 5,In  ChezScheme\i3nt\bin\i3nt\ dir, you should see petite.exe and scheme.exe.