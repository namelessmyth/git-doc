# git-doc

## 介绍
此目录主要存放个人经验总结和学习笔记，内容包含：Java，英语，软件工具使用，其他编程语言等。

格式主要以文档格式为主，例如：markdown，docx，xlsx等。

使用Git管理文档的原因：

- 跨设备文件同步。例如：在家里电脑编辑完后，可能需要在公司电脑继续编辑。
- Git会自动记录每个文件的修改历史。这样就不需要单独记录每个文档的修改历史了。万一误删还能还原。
- 本地和服务器都有备份。发博客，如果博客网站关停，写的内容可能就丢失了。或者还得花时间从网站上一个个导出来。



## 使用说明

1.  由于Git空间有限，最大3G，超出收费。请尽量不要提交非文档格式内容。尤其是视频格式。
2.  推荐使用Markdown格式，优点如下
    1.  markdown更关注文档内容而不是文档排版样式等。自带各种语言的语法着色。对程序员比较友好。
    2.  自带mermaid语法，可以直接用文本，编写流程图，脑图，类图等。不需要在其他工具里画好在黏贴过来。
    3.  支持导出Word，PDF，html文件等。同时markdown格式的文件，天然支持在线预览，不需要任何插件。
    4.  很多博客网站支持markdown语法，写好后可以直接发博客。例如：CSDN。




## 参与贡献

1.  文档创建者：namelessmyth（Gem）



## 目录说明

~~~mermaid
flowchart LR
root-->English
root-->Java
root-->Shell
root-->Job
root-->Template[文件模板]

Java-->mashibing[mashibing-马士兵学习笔记]
Java-->gupao[gupao-咕泡学习笔记]
~~~

