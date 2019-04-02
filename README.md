# iCloud-noSync
让macOS中的iCloud云盘可以不同步指定的文件

## 系统要求

- macOS 10.14.4 测试通过
- 其他版本未进行测试

## 安装

下载本项目后，双击安装其中的 `noSync.workflow`。

## 使用

在iCloud云盘的任一文件夹中，在不需要同步的项目上右键->快捷操作->noSync。

## 原理

如果文件或文件夹的后缀为 `.nosync`，iCloud云盘不会为其同步。  
假设文件或文件夹 `foo` 不需要iCloud同步：

- 将 `foo` 重命名为 `foo.nosync`
- 为 `foo.nosync` 建立名为 `foo` 的替身

## 参考的项目

https://alvaropinot.github.io/nocloud/  

https://github.com/tsdexter/iCloud-NoSync
