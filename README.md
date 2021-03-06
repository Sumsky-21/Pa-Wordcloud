# Pa-Wordcloud:基于网络爬虫生成词云的网络内容可视化工具
## Background 背景
这是在某高校2019年秋季学期选修课《Python编程与智能车技术》上我与另一名同学合作完成的课程大作业，也算是我首次做这种由想法到实践的程序开发。这个程序可以从六种搜索引擎搜索关键词得到的内容分别制作词云，从而直观的展示这个关键词关键词在网上内容中的面貌。为了方便操作，还给程序加上了图形化的交互界面，提供了许多自定义的选项。  

放到github上面，也是作为对这个大作业的一种纪念。
## Code 代码
程序的源代码是用python写成的。一共有两个源代码文件，其中`pa.py`主要实现的是对六种搜索引擎（包括百度、必应、谷歌、搜狗微信（公众平台）搜索、搜狗知乎搜索以及微博内置的搜索）的内容爬取；`pic.py`则承担了图形化界面、词云生成以及词云图片处理的功能。`pa.py`作为`pic.py`的引用库来起作用。  

程序使用了python计算生态中大量的第三方库，同时在开发程序的过程中也借鉴了网上的一些思路。   

如果想要了解更多关于这个项目的细节，可以阅读仓库中上传的实验报告。
## Thanks 致谢
感谢<b>林佬</b>作为这个大作业的合作者，完成了`pic.py`中的大部分内容；

同时也感谢徐老师对我们这个作业的指导和帮助。
## Use&Copy 使用或借鉴
如果想要体验这个程序，在任何安装了python的环境下，将两个源代码文件放在一起，运行`pic.py`即可（前提是要安装程序运行必须的第三方库）。

[CC BY-NC-SA 4.0 协议](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.zh-Hans)适用于这个项目。您可以借鉴代码中任何的片段或idea，但是也必须对这样的借鉴可能引起的后果负全部责任。
