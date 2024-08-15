我写的一个框架，有需要的可以参考

# 有关windows server作为nas的相关内容

## 1.系统安装

1). 前往[msdn](https://next.itellyou.cn/Original/#cbp=Product?ID=ff70d59a-8e02-ec11-a9e5-95b21d9a899a)下载系统镜像

2). 将系统镜像写入U盘，并将它插在设备的USB接口上。打开设备，快速点击F11进入引导选择界面，选择U盘启动

3). 成功进入系统安装界面，完成系统安装流程

## 2.首次配置

1). oobe

2). 网络

3). rdp

4). **windows admin center(微软出品的一个用来管理的web UI，功能挺全面，这里面也有powershell和rdp功能)**

## 3.安装驱动以及常用软件

1). 驱动

2). 运行库（可选）

3). 第三方应用程序（可选）

## 4.文件共享

1). SMB（服务器管理设置或文件管理器盘符右键

2). webdav（alist

3). iscsi（服务器管理器

## 5.下载工具--qBittorent

1). gui

2). web UI

3). 更加易用的第三方web UI（vue

## 6.相册管理--[MT Photos](https://mtmt.tech/)

1). 服务端

2). 客户端

## 7.影音库

### 1.音乐服务--[音流](https://aqzscn.cn/archives/stream-music-versions)+Navidrome

客户端音流是全平台的，48买断

### 2.影片管理--jellyfin/emby

一个开源免费，一个闭源收费

### 3.进阶操作--nastools（mp）

自己去GitHub查看作者的新项目

## 8.hyper-v

1). 虚拟硬盘

建议使用vhdx

2). 虚拟交换机

外部优先，sriov

3). 虚拟机

需支持scsi控制器

## 9.其它进阶用法

### 
