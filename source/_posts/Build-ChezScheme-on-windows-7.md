---
title: Build ChezScheme on windows 7
date: 2017-04-20 12:29:39
tags:
---


## Install msys2


## Install visual studio 2015 and launch vs2015 x64 native tools command prompt, from this terminal, run 
``` bash
c:\msys64\msys2_shell.bat
```

## Install gcc and git

run 
``` bash
pacman -S gcc base-devel
pacman -S git
```



### Hello world 

``` bash
main :: IO ()
main = do
  putStrLn "Hello world"
```