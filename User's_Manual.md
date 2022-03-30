*说明：该文档对 VSCode 环境下 MarkDown 笔记的编写及云端管理做出详细使用说明*

---
&emsp;&emsp;VSCode 的安装和汉化在此不再赘述，为了实现 VSCode 环境下 MarkDown 笔记的丝滑编写，首先建议安装以下几款插件：
* Markdown Preview Enhanced（MPE，YYDS！）
* Markdown All in One
* Better Markdown & Latex Shortcuts
* Paste Image

&emsp;&emsp;新建文件夹作为你以后记笔记的库，并在 VSCode 环境中打开该文件夹作为你的工作区。在该工作区下可以新建 ***.md 笔记文件或者子文件夹对你的笔记进行分类。

> &emsp;&emsp;关于 MarkDown 笔记的编写语法请阅读 [MarkDown语法规则](MarkDown_Rules.md)，关于 VSCode 使用过程中的快捷键请阅读 [VSCode常用快捷键大全](HotKeys_Record.md) 。

&emsp;&emsp;笔记编写过程中可以通过 `ctrl + shift + v` 预览渲染效果，安装了MPE插件以后可以通过 `ctrl + k , v` 调出类似于 Typora 的实时渲染窗口，注意按 v 的时候应释放 ctrl 键。首次出现的渲染效果窗体是白色的，可以通过 `ctrl + ,` 调出设置窗体，搜索 Preview Theme，里面有各种颜色背景的选项可供调整。在渲染窗体中右击选择 “open in browser” 可以将当前的笔记通过浏览器打印为 PDF 文件。

&emsp;&emsp;在VSCode环境下编写的笔记，通过其自带的源代码管理功能通过Git实现版本控制，Git教程请阅读[Git教程](LearnGit.md)。