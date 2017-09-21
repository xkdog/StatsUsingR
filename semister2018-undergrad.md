
# 第一周（9月12日）：课程说明

本说明适用于南开大学周恩来政府管理学院2017-2018秋季学期的《R语言统计应用入门》本科课程。课程需自备电脑。

## 基本说明

- 真正的零基础。当然，有基础更好。
  - 无须R软件基础。
  - 无须推论性统计学基础。不过多涉及，但会介绍*t*检验、方差分析、线性回归的基本命令操作与结果解读。
- 主要内容
  - 数据导入
  - 数据管理
  - 描述统计
  - 基本绘图


## 软件准备

仅限windows平台进行说明。Mac系统请参照此说明自行探索相关细节。

- 安装[R](https://www.r-project.org/)，安装[RStudio](https://www.rstudio.com/)，安装[Rtool](https://cran.r-project.org/bin/windows/Rtools/)。
-  **所有软件请保证安装在系统盘，且所有安装路径（包括Windows登陆账户名称）无任何中文及特殊字符**。一般选择默认安装方式即可保证这一点。
- 注册[GitHub](https://github.com/)账户，不妨顺便找到这个[链接](https://github.com/xkdog/StatsUsingR)。

## 语法准备

请系统学习 `Markdown`语言。

`Markdown`是一种可以使用普通文本编辑器编写的标记语言。关于Markdown的简洁说明可参考相关网页，以下是一些推荐。
  
- [简书：Markdown入门指南](http://www.jianshu.com/p/1e402922ee32/)
- [阳志平：Markdown写作浅谈](http://www.yangzhiping.com/tech/r-markdown-knitr.html)
- [Markdwon在线学习课程](http://www.markdowntutorial.com/)
  
以上三个链接请大家自行仔细阅读，第三个文档请花10分钟左右的时间完成在线学习。`Markdown`语法不是课程本身的内容，但对于了解本课程文档的最基本格式具有根本性的作用。

上述每一个软件或语言环境都需要较长时间的学习和训练，课程中会以尽量清晰简洁的方式进行介绍，仍请做好一定的心理准备。

## 相关教材

课程所有内容均可在网上找到免费公开的版本。为阅读方便，推荐（但不强求）以下书目：

- 卡巴科夫：[《R语言实战》](https://www.amazon.cn/gp/product/B01FSXCBMS/ref=pd_cp_14_1?ie=UTF8&psc=1&refRID=53CV03RWGW12KYZQYJJX)(2016版)。 
- Hadley: [*R for Data Science*](http://r4ds.had.co.nz/)
- 吕小康：[《R语言统计学基础》](https://www.amazon.cn/%E6%95%B0%E9%87%8F%E7%BB%8F%E6%B5%8E%E5%AD%A6%E7%B3%BB%E5%88%97%E4%B8%9B%E4%B9%A6-R%E8%AF%AD%E8%A8%80%E7%BB%9F%E8%AE%A1%E5%AD%A6%E5%9F%BA%E7%A1%80-%E5%90%95%E5%B0%8F%E5%BA%B7/dp/B06XGR6LJZ/ref=sr_1_1?s=books&ie=UTF8&qid=1505149742&sr=1-1&keywords=%E5%90%95%E5%B0%8F%E5%BA%B7)(2017)。
- [Bookdwon官网](https://bookdown.org/)上的若干公开电子书籍。

## 考核方式

以**论文**形式结课。

### 平时作业（40%）

- 执行一定量的问卷调查，完成数据录入的工作，然后基于汇总数据完成指定任务的分析。
- 完成平时布置的各种习题任务。
- 协助完善教学资料与练习题。
- 其他，待丰富。

最后集中到一个大作业中，在2018年1月8日晚上6：00之前提交到本人学院二楼的邮箱。

### 期末作业（60%）

论文形式提交，一般不少于5000字（不计空格），学院规定格式下A4纸不少于4页。字数无上限。word版打印出来提交教科办，同时还需要提交我markdown文档，发布成github页面，最后整合到某页面中（待定）。

**可选方式**：

- 寻找一篇提供原始数据、但不是用R做分析的量化文章，使用R重新完成数据分析流程。
- 使用CGSS、CFPS等公开数据，自选主题，完成一篇研究报告。
- 完成某一数据可视化任务。
- 翻译某常用R包的操作说明文档。
- 翻译某数据分析类的英文文章。
- 其他，待丰富。

与平时作业一起（期末论文与期中作业分开装订），在2018年1月8日晚上6：00之前提交到本人学院二楼的邮箱。

附：本课程自开课伊始，尚未出现选课而未及格的同学。

## 本周作业

下周上课前要完成的工作：
 
- 完成昨天的问卷链接，并尽量转发扩散一下，让学过统计学的、从事定量研究的研究生或博士生或老师/科研人员填写。链接如下：
 
https://github.com/xkdog/PCI/blob/master/README.md
 
 
- 从学校的软件正版化平台安装Office 2016版本。
 
- 安装R、Rstudio，Windows平台同学安装Rtools。一律安装在C盘（系统盘）。
 
- 联网状态下，打开R，尝试如下命令：`install.packages(“rmarkdown”)`。
 
- 打开Rstudio，尝试新建一个Rmarkdown。
 
- 使用教育网邮箱注册GitHub账户，关注我指定的文件夹。
 
- 自己了解一下R、Rstudio，Markdown与Rmardown的关系。可百度、Bing、Google。谷歌需要翻墙，可推荐[蓝灯（lantern）](https://github.com/getlantern/lantern/releases/tag/latest)，每月500M免费流量，稳定性尚可。付费vpn有风险，钱还没用完可能vpn就挂了，除非确有需求，否则暂不推荐。

## 本周录屏

请及时查看群内链接。录屏暂不主动公开，因为课堂上的某些“只言片语”显然不足为外人道也。




