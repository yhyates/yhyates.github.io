---
layout: mypost
title: Cytoscape网络作图器
author: [17轮机-杨恒一]
categories: [工具]
---
> 介绍

Cytoscape 是一个专注于开源网络可视化和分析的软件，其核心是提供基础的功能布局和查询网络，并依据基本的数据结合成可视化网络。多用于生物信息学领域，但其强大的作图能力值得我们了解。
![endnote](https://ask.qcloudimg.com/http-save/developer-news/pckkg4lskv.jpeg?imageView2/2/w/1620)

>下载

- 地址：[https://cytoscape.org/download-platforms.html](https://cytoscape.org/download-platforms.html)
- 平台：Mac、Windows、Linux

>安装

- 点击Next即可，对于Windows和Mac，若未安装Java，将会自动安装。

>教程


- 简单粗暴型：

```
准备数据：
1.-.xlsx，A1输入Node1，B1输入Node2。自行填充A列和B列数据，Node1（A列）指向Node2（B列）
2.桌面创建excel表type.xlsx，A1输入Node，B1输入Type。自行填充A列和B列数据，A列是节点名字，B列是类型，方便分类上色和调整形状

导入数据：
打开Cytoscape，依次点击：File-Import-Network from File，选中network.xlsx文件后点击OK，完成导入
再依次点击：File-Import-Table from File，选中type.xlsx文件后点击OK，完成导入

美化：
- 颜色：点击左侧面板中的Style，选中Fill Color栏左数第二个方块，在Column中选中Type，在Mapping Type中选中Discrete Mapping，将会出现excel表type.xlsx中的Type列的数据，依次设置颜色即可

- 节点分布：中间面板中选中改变分布的节点，Ctrl键可批次选中，点击顶部面板中的Layout，其中Grid Layout是矩阵分布，Circular Layout是圆圈分布，Stacked Node Layout是直线分布，Hierarchical Layout是层次分布。选择Selected Nodes Only。

- 节点大小：点击左侧面板中的Style，选中Size，其后与颜色设置步骤相同

导出：依次点击File-Export-Network to Image，选择PDF格式，点击OK即可

若作为期刊配图，后期需导入Ai，进行调整，输出为TIF格式即可

```
![endnote](https://i.loli.net/2020/03/05/sSCj5ycF2W7eGuk.png)

```
这是我自建数据用Cytoscape为2020年美赛A题所作的EMD+BP预测模式图，你可以下载源数据，并动手实践。
```
**[点击下载数据](https://www.jianshu.com/p/aa92510d4f5e)**

---

- 深入细致型：

```
如果你有浓厚的兴趣并有毅力和时间，请自行浏览Cytoscape官网和论坛。
```
这篇文章可能会对您有所帮助，[点击跳转](https://www.jianshu.com/p/5a790c223dee)


> 参考

```
[1]Cytoscape 简介： https://www.jianshu.com/p/aa92510d4f5e
[2]Cytoscape做分类网络图： https://cloud.tencent.com/developer/news/230172
```


