bsc (Btrfs snapshot cleanup）
===


#### 在 openSUSE 系统下使用 Btrfs 文件系统时，快照管理工具 snapper 会自动生成许多快照，而 snapper 自带的快照清理功能又不是很方便，因此便写了这个脚本，用以辅助 snapper 进行快照的清理。
---


###一、依赖

> awk

###二、安装

####1、[下载脚本](https://github.com/gmg137/bsc/archive/master.zip)

####2、解压后赋予 bsc 执行权限

    chmod a+x bsc


###三、使用

    sudo ./bsc
    或：
    sudo cp bsc /usr/bin
    sudo bsc
