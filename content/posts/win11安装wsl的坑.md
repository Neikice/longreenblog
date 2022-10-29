+++
title = "Win11安装wsl的坑"
publishDate = 2022-10-29T17:00:00+08:00
lastmod = 2022-10-29T23:20:54+08:00
draft = false
author = "长问长青"
+++

## 安装Debian {#安装debian}

```powershell
wsl --install --distribution Debian
```


## 显示报错0x800701bc {#显示报错0x800701bc}


### 问题的原因 {#问题的原因}

WSL版本由原来的WSL1升级到WSL2后，内核没有升级


### 解决方案 {#解决方案}

[官方下载连接](https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi)
