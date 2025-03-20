---
title: "SPSS安装教程（Windows & Mac）"
description: "SPSS安装教程（Windows & Mac）"
lead: "SPSS安装教程（Windows & Mac）"
date: 2021-08-19T08:48:57+00:00
lastmod: 2021-08-19T08:48:57+00:00
draft: false
images: []
menu:
  docs:
    parent: "psychology"
weight: 10
toc: true
---

### SPSS 24 & 27 安装教程（Windows & Mac）

## 1. 下载SPSS安装包

你需要先下载适合你系统的 **SPSS Statistics** 安装包，并确保计算机满足安装要求。

- **Windows 版本（SPSS 24）**：[下载](https://git.ikxiuxin.com/https://github.com/SolitaryJune/apps/releases/download/v1.0.0/SPSS_Statistics_24_win64.zip)
- **Mac 版本（SPSS 27 for Sonoma+）**：[下载](https://git.ikxiuxin.com/https://github.com/SolitaryJune/apps/releases/download/v1.0.0/SPSS27.M.Sonoma.+.-.JuneOver24.dmg)

## Windows 版（SPSS 24）安装教程

### 2. 解压安装包

下载完成后，使用解压工具（如 360压缩、WinRAR）解压 `SPSS_Statistics_24_win64.zip`。

![解压安装包](images/win1.png)

### 3. 运行安装程序

解压后，找到 `SPSS_Statistics_24_win64.exe` 并双击运行。

安装向导启动后，点击 **下一步** 继续安装。

### 4. 选择安装目录

可以选择默认（ **建议** ）的安装目录 `C:\Program Files\IBM\SPSS\Statistics\24\`，或点击 **更改** 选择其他路径。

点击 **下一步** 继续。

![选择安装目录](images/win2.png)

### 5. 完成安装（但不要打开）

等待安装完成后，点击 **完成** 退出安装向导。

**注意：此时不要打开SPSS！**

![安装完成](images/win3.png)

### 6. 复制 `lservrc` 文件

安装完成后，在解压目录中找到 `lservrc` 文件，并将其拖入 `C:\Program Files\IBM\SPSS\Statistics\24\` 目录下。

> **📌 注意**
>
> - 可能需要 **管理员权限** 才能复制文件。
> - 如果系统提示 **替换文件**，请选择 **替换目标中的文件**。

![复制 lservrc](images/win4.png)

### 7. 运行SPSS 24并验证安装

复制 `lservrc` 后，运行 **IBM SPSS Statistics 24**。

如果出现 **IBM SPSS Statistics 已到期** 的提示，则说明安装完成,即可正常使用。

![安装完成](images/win5.png)

---

## Mac 版（SPSS 27 for Sonoma+）安装教程

### 1. 下载安装文件

下载 `SPSS27.M.Sonoma.+.-.JuneOver24.dmg` 后，双击打开，并运行 `SPSS Statistics 27.0` 安装程序。

![后，双击打开，并运行](images/image2.png)

### 2. 取消许可证管理向导

安装完成后，会自动运行许可证管理向导，点击 **取消**。

![取消许可证管理向导](images/image.png)

### 3. 替换 `lservrc` 文件

将 `lservrc` 文件拷贝到以下路径：

```code
/Applications/IBM SPSS Statistics 27/Resources/Activation
```

![lservrc](images/image copy.png)

![lservrc2](images/image copy2.png)

### 4. 复制 `IF026 Update` 文件

将 `IF026 Update` 文件拷贝到：

```code
/Applications/IBM SPSS Statistics 27/SPSS Statistics.app/Contents
```

![IF026 Update](images/image copy3.png)

### 5. 加入 Sonoma+ 补丁

将 `libplatdep.dylib` 文件拷贝到：

```code
/Applications/IBM SPSS Statistics 27/SPSS Statistics.app/Contents/lib/
```

![libplatdep](images/image copy4.png)

![libplatdep5](images/image copy5.png)

### 6. 运行SPSS 27

在 **启动台** 启动 `SPSS Statistics 27`，如果一切正常，则表示安装成功！

![运行SPSS](images/image copy6.png)

---

## 常见问题

### 如何打开 Mac 目录路径？

点击 **前往** → **前往文件夹**，然后复制以下路径并回车即可打开：

![前往文件夹](images/image copy7.png)

```code
/Applications/IBM SPSS Statistics 27/SPSS Statistics.app/Contents
```

![前往文件夹8](images/image copy8.png)
