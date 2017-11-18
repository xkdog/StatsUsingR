
# 2017年11月18日 广州 R 语言工作坊

本文档用于第4界大数据传播论坛的 R 语言工作坊的相关说明。

# 软件安装

## 安装基础软件

安装 R ，安装 RStudio，安装 Rtools （Windows）或 XQuartz （Mac）。

软件及相关数据见以下链接：

链接：<http://pan.baidu.com/s/1sl2ZqB7>

密码：ctyr


## 安装 R 包

```
install.packages("tidyverse")
```

安装完成后，加载该包。

```
library(tidyverse)
```

# 基本任务

- R 中的数据结构
- R 中的数据导入
- R 的基础操作
- 利用 **dplyr** 包进行数据管理
    - 新增变量
    - 选择变量
    - 筛选观测
    - 数据排序
    - 随机抽样
    - 分组统计
    - 管道操作
- 利用 **stringr** 包进行文本数据分析
    - 基本字符串函数
    - 正则表达式基础


# 在线教程

- 《定量群学》微信公众号的系列推文
- 本人微信朋友圈的系列转载（微信号：nkluxk）
- 详细内容点击此处的 [GitHub 库](https://github.com/xkdog/DAUR)

# 参考教材

- 卡巴科夫：[《R 语言实战》](https://www.amazon.cn/gp/product/B01FSXCBMS/ref=pd_cp_14_1?ie=UTF8&psc=1&refRID=53CV03RWGW12KYZQYJJX)(2016)。 
- 任坤：[《R 语言编程指南》](https://www.amazon.cn/s/ref=nb_sb_noss?__mk_zh_CN=%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BD%91%E7%AB%99&url=search-alias%3Daps&field-keywords=%E4%BB%BB%E5%9D%A4)（2017）。初学者阅读前7章即可。
- [吕小康](https://xkdog.github.io/)：[《R 语言统计学基础》](https://www.amazon.cn/%E6%95%B0%E9%87%8F%E7%BB%8F%E6%B5%8E%E5%AD%A6%E7%B3%BB%E5%88%97%E4%B8%9B%E4%B9%A6-R%E8%AF%AD%E8%A8%80%E7%BB%9F%E8%AE%A1%E5%AD%A6%E5%9F%BA%E7%A1%80-%E5%90%95%E5%B0%8F%E5%BA%B7/dp/B06XGR6LJZ/ref=sr_1_1?s=books&ie=UTF8&qid=1505149742&sr=1-1&keywords=%E5%90%95%E5%B0%8F%E5%BA%B7)（2017）。
- 薛毅：[《R 语言实用教程》](https://www.amazon.cn/R%E8%AF%AD%E8%A8%80%E5%AE%9E%E7%94%A8%E6%95%99%E7%A8%8B-%E8%96%9B%E6%AF%85/dp/B00ODRG9EC/ref=sr_1_1?s=books&ie=UTF8&qid=1510975378&sr=1-1&keywords=%E8%96%9B%E6%AF%85)（2014）。
- Hadley: [《高级 R 语言编程指南》](https://www.amazon.cn/%E9%AB%98%E7%BA%A7R%E8%AF%AD%E8%A8%80%E7%BC%96%E7%A8%8B%E6%8C%87%E5%8D%97-%E5%93%88%E5%BE%B7%E5%88%A9%C2%B7%E5%A8%81%E5%85%8B%E6%B1%89%E5%A7%86/dp/B01HEVCA6O/ref=sr_1_1?s=books&ie=UTF8&qid=1510975168&sr=1-1&keywords=%E9%AB%98%E7%BA%A7R%E8%AF%AD%E8%A8%80%E7%BC%96%E7%A8%8B%E6%8C%87%E5%8D%97)（2016），有[英文在线版](http://adv-r.had.co.nz/)。初学者阅读1-5章即可。
- Hadley: [*R for Data Science*](http://r4ds.had.co.nz/)，国内有纸质影印版[《数据科学：R 语言实现》](https://www.amazon.cn/%E6%95%B0%E6%8D%AE%E7%A7%91%E5%AD%A6-R%E8%AF%AD%E8%A8%80%E5%AE%9E%E7%8E%B0-R-for-Data-Science-Hadley-Wickham-Garrett-Grolemund/dp/B075TN1XZS/ref=sr_1_1?s=books&ie=UTF8&qid=1510975098&sr=1-1&keywords=r+for+data+science)（2017）。
- [Bookdwon官网](https://bookdown.org/)上的若干公开电子书籍。








