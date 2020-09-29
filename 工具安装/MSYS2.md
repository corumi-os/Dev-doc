# MSYS2

MSYS2是一个Windows上的软件分发和构建平台。集合了许多用于软件构建的库和工具。

## 下载

- https://www.msys2.org/

安装完成后，打开MSYS2的终端，以下命令均需要在MSYS2的终端中使用。

首先，更新package库：
`pacman -Syu`

如果主体需要更新，会要求关闭终端再重新打开，然后才能更新package：
`pacman -Su`

> 静态库的路径为:
> `msys2\usr\lib`
> `msys2\mingw64\lib`
> 头文件的路径为:
> `msys2\usr\include`
> `msys2\mingw64\include`

**注意：**在`MSYS2`中安装的工具链，最好在`MSYS2`的`MINGW`终端中使用，否则可能发生意料之外的错误。

## 安装package

### GCC

`pacman -S gcc `

### make

`pacman -S make`

### ARM-GCC

`pacman -S mingw-w64-x86_64-arm-none-eabi-gcc`

### OpenOCD

`pacman -S mingw-w64-x86_64-openocd `

