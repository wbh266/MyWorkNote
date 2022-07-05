# MAC使用相关
1、中文输入法失效：
现象：可以正常切换中英文输入方式，中文输入方式下显示拼音下划线，但不显示选词框。
Boom：Lanuchpad(活动监视器)搜索中文输入法，双击选择退出即可。

# VSCode相关
1、macOS中 vscode终端快速打开出现：
error：`command not found: code`

Boom：VSCode命令面板查找`shell command`;如果继续报错：`VS Code Denied Permission unlink 'usr/local/bin/code'`,在本地终端输入`sudo chown -R yourUsername /usr/local/bin`

# Git使用相关
1、add但未commit情况下，执行了版本回退“git reset --hard HEAD^”，导致暂存区数据全部丢失。
Boom：执行`git fsck --lost-found`，然后到.git/lost-found目录下找找看有没有你丢失的文件，丢失的文件名是以uuid的命名，所以需要每个文件单独点开看一下是不是你要的内容。