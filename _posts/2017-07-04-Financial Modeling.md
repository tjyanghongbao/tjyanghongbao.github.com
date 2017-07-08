---
layout: post
title: Financial Modeling
---

{{ page.title }}
================

<p class="meta">03 July 2017 - HONG KONG</p>
1.1 介绍
建模一般分为两类 
1.财务建模，侧重对公司的估值（value），帮助我们找到被低估的股票买入，被高估的股票卖出，
及格雷厄姆所说的价值分析的理念，用基于未来现金流折现来估值，即DCF模型。
2.产品建模（编程eg.二叉树）


总结目标
1.DCF=》预测
2.Excel无影手


1.2Excel基本技巧介绍（基于win）

练无影手基本原理：凡事都问Alt键
在建模里千万不要用ctrl C/V （原则：相同的东西不要输入两次）
建模之前做一些基本设置
1）Excel选项->公式->除数据表外，其他自动重算（Automatic except for data tables）
因为在做敏感性测试时，运算量特别大，容易死机
2)Excel选项->公式->启用迭代运算(Enable iterative calculation)
3)颜色的设置
	①黑色：公式输入
	②蓝色：假设 or 手动输入的（eg。历史数据）
	③绿色：引用（不要Ctrl C/V）
	④红色：存疑

1.3估值基本原理
目标：找到价值
前提假设
	Price≠Value
原理：DCF（未来现金流折现）
Two-stage:
通常取三年的历史数据

历史（3年、5年）=> 找到驱动因素=>假设※=>预测（能够精准预测的一般5年）

假设很重要，不同功力的人所做假设不一样

重要的东西，要做精准估计
不重要的东西，可以做简单估计

求终值①GGM（D0(1=+g)/(r-g)） ②乘数法：P/E*EPS

CF=>FCFF=>WACC=>EV-Debt

FCFF=> BEIT(1-T)+DEP-WC(INV)-FC(INV)























