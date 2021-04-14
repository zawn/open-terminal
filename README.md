# Open Terminal
~~The Finder extension~~ for macOS Big Sur can add the "open terminal" function to the Finder context menu. Similar to Windows shift-right-click.

After studying the Finder extension, and looking at the effect of the code actually written, this simple function is not suitable for using the Finder extension to achieve the following reasons:

1. The purpose of Finder extension design is mainly for third-party network disks like OneDrive.
2. The Finder extension needs to specify a specific monitoring directory, this directory is specified too much and it is easy to conflict with other plug-ins
3. Although the Finder extension can add a menu to the right-click menu, it needs to be adapted in advance to the specific application to be opened
4. Directly use automatic operation to achieve, does not conflict with other plug-ins, is easy to extend, and is simple to implement

There are also disadvantages to using automatic operation:

1. In many cases, the menu will be collapsed.
2. It is impossible to determine whether the menu is displayed based on the specific directory content like the Finder extension (for example, the SmartGIT menu implemented with the Finder extension can determine whether the subdirectory has a .git directory to determine whether the menu is displayed)

## installation:

1. Clone the current repo.
2. Double-click the specific automatic operation item you want to install.

## modify:

1. You can modify it according to your needs, this is very simple without additional learning. Only need to use automatic operation to open the specific workflow.

## to sum up

The menu based on automatic operation is simple enough, stable enough, will not bring additional performance loss, will not cause conflicts.


经过对Finder扩展的研究，并实际编写的代码效果来看，这种简单的功能并不是使用Finder扩展来实现，理由如下：

1. Finder扩展设计的目的主要为了给像OneDrive之类第三方网盘使用的
2. Finder扩展需要指定具体的监测目录，这个目录指定的多了容易和其他插件冲突
3. Finder扩展虽然可以实现在又见菜单中添加菜单，但扩展麻烦
4. 直接使用自动操作实现，不与其他插件冲突，容易扩展，实现简单

使用自动操作实现也有缺点：

1. 好多情况下菜单会被折叠起来。
2. 无法像Finder扩展一样可以根据具体的目录内容来决定菜单是否显示（比如，用Finder扩展实现的SmartGIT菜单可以判断子目录是否具有.git目录从而决定菜单是否显示）

## 安装方法：

1. Clone当前仓库。
2. 双击你要安装的具体的自动操作项目。

## 修改添加：

1. 你可以根据你的需要修改，这个很简单不需要额外的学习。仅仅需要用自动操作打开具体的workflow。

## 总结

基于自动操作实现的菜单足够简单，足够稳定，不会带来额外的性能损失，不会造成冲突。

<img width="1007" alt="截屏2021-04-14 上午10 01 38" src="https://user-images.githubusercontent.com/5005199/114643623-9cbf1600-9d08-11eb-90c2-ee8836490cd4.png">

