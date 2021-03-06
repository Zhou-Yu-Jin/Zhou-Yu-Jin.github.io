---
layout: default
title:  "信息可视化"
date:   2018-1-4 21:00:30 +0800
excerpt: 信息可视化作品练习
tags:
  - CN
  - 学习
---
## 信息可视化作品之地图
- 这次我主要使用高德地图抓取全国数据，在Tableau上绘制地图，对比分析结果。四个关键词分别为：游乐场，海洋馆，慈善机构，红十字会。数据量为3000+
### 目的: 
- 看游乐场和海洋馆两种休闲娱乐场所哪一种更多。
- 观察慈善机构以及红十字会的全国分布情况，以及两种社会机构的数量对比和性质分析。
- 分析出省份之间的差别，我的猜想是越发达的省份，娱乐措施越多，同样地社会机构也会更加完善
### 这是按照省份粗略的分布图
![](https://raw.githubusercontent.com/Zhou-Yu-Jin/Zhou-Yu-Jin.github.io/master/assets/images/%E5%85%A8%E5%9B%BD%E5%88%86%E7%9C%81%E5%88%86%E5%B8%83%E5%9B%BE.png)

### 分析步骤
##### 准备工作：
用python语法在anacoda上抓取关键词数据，其中要用到高德地图key。
##### Tableau 步骤
- 首先将所有数据连接进去，修改经纬度。绘制一张粗略的地图
- 我根据type划分，把最主要的两个type抓取出来，绘制了两份图表。可以发现：<br>1.游乐场和海洋馆打性质大部分都是风景名胜，慈善机构以及红十字会大部分都是社会机构。<br>2.基本都分布在东南沿海地区（较为发达地区）
[仪表板分析](https://public.tableau.com/shared/N37T85452?:display_count=yes)
- 单独比较娱乐休闲场所数据
![](https://github.com/Zhou-Yu-Jin/Zhou-Yu-Jin.github.io/blob/master/assets/images/%E6%B8%B8%E4%B9%90%E5%9C%BA%E5%92%8C%E6%B5%B7%E6%B4%8B%E9%A6%86%E7%9A%84%E5%88%86%E5%B8%83.png?raw=true)
- 单独比较社会机构数据
![](https://raw.githubusercontent.com/Zhou-Yu-Jin/Zhou-Yu-Jin.github.io/master/assets/images/%E7%BA%A2%E5%8D%81%E5%AD%97%E4%BC%9A%E5%92%8C%E6%85%88%E5%96%84%E6%9C%BA%E6%9E%84%E7%9A%84%E5%88%86%E5%B8%83.png)
## 结论：
- 游乐场所比海洋馆更多，二者大多分布于东南沿海等发达地区，与猜想一致，越发达，休闲娱乐场所越多
- 慈善机构和红十字会作为社会措施，分布相对均匀，除了西部地区较为稀少。
- 纵观四个关键词数据，我们发现西部地区落后较多，确实要加强西部大开发措施。
