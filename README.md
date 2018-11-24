# Codelab 开发环境安装部署指南

## Git 安装指南
如果 codelab 过程中需要使用 git，那就需要安装 Git

 * Linux：可以使用包管理软件（如 yum, apt）来安装 git
 * MacOSX：可以使用 brew 来安装 git
 * Windows：运行 Git 目录下的安装程序，根据操作系统选择相应的版本

## Python / TensorFlow 安装部署
### Windows
1. 安装 Anaconda3 至 D:\Anaconda3，安装程序位于 Python_TensorFlow 目录中
2. 打开 Anaconda Prompt 终端程序，运行以下命令：
```
conda create -n codelab
```
3. 解压 Python_TensorFlow 目录中的 anaconda3-env-codelab 压缩包，得到 codelab 目录
4. 将上一步骤解压的 codelab 目录覆盖 D:\Anaconda3\envs\codelab 目录
5.  Anaconda Prompt 终端程序，运行以下命令：
```
conda activate codelab
```

### MacOSX
1. 安装 Anaconda3 至用户目录下（如~/anaconda3），安装程序位于 Python_TensorFlow 目录中
2. 打开 Anaconda Prompt 终端程序，运行以下命令：
```
conda create -n codelab
```
3. 解压 Python_TensorFlow 目录中的 anaconda3-env-codelab 压缩包，得到 codelab 目录
4. 将上一步骤解压的 codelab 目录覆盖 ~/anaconda3/envs/codelab 目录
5.  Anaconda Prompt 终端程序，运行以下命令：
```
source activate codelab
```

## Android 开发环境安装部署指南

### Windows
1. 将 Android 目录复制到电脑 D 盘根目录下
2. 解压所有压缩文件得到如下目录：
 * android-studio
 * Sdk
 * .android
 * .AndroidStudio3.2
 * .gradle
 3. 运行 mklink.cmd 脚本。此脚本将会在用户目录下建立映射到 .android, .AndroidStudio3.2, .gradle 目录的链接
 4. 根据操作系统，运行 AndroidStudio64 或者 AndroidStudio 快捷方式

 ### MacOSX
 未制作运行镜像，请自行安装 AndroidStudio 并配置