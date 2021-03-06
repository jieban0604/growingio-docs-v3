# 微信应用用户分析

## 基本功能介绍 <a id="ji-ben-gong-neng-jie-shao"></a>

微信公众平台基本提供给了以下开放能力给企业开发者、运营者以及营销人员，根据不同端的定位和能力，越来越多的客户基于不同端提供给用户不同的产品和服务体验，并且基于全端提供完整的用户体验路径。

![](https://docs.growingio.com/.gitbook/assets/-LGNxeGABUADKiTWTaEM-LmIKQLfD1p1VKUmMw2R-LmITksJ8N1WT-u5gPr5image.png)

GrowingIO 微信应用用户分析，基于目前企业多微信场景应用的情况，帮助客户清晰的了解不同端的用户流量、转化以及留存的情况。帮助您更好的分析微信多应用运营的策略。

## 查看数据 <a id="jin-hang-wei-xin-gong-zhong-hao-she-zhi-shou-quan-shu-ju-ji-cheng"></a>

### 前提条件

已完成[微信公众号数据集成](../../data-center/data_source_integration/wx-account.md)，集成成功后，等待一段时间（一般是1~2个小时左右）即可查看数据。

### 操作步骤

一. 在顶部导航栏选择“**用户分析 &gt; 微信应用用户分析”**，进入微信应用用户分析界面。

二. 在**公众号数据概览**页签查看公众号数据概览。

![](https://github.com/growingio/growingio-docs-v3/tree/d520f4a494f6c0635c83422f55c665597e79ee96/.gitbook/assets/image%20%2856%29.png)

| 参数 | 说明 |
| :--- | :--- |
| 时间 | 设置时间范围，按日、周、月的区间展示。 |
| 净增人数趋势图 | 展示周期内所有微信公众号的核心指标的数据和一段时间的变化趋势。包括新增人数、取消关注人数、净增人数、积累人数的趋势及数值。 |
| 新增人数来源维度堆积图 | 展示周期内单个微信公众号的**新增用户来源人数**。 |
| 新增人数来源维度百分比占比图 | 展示周期内单个微信公众号的**新增人数来源维度占比**。 |

三. 在**用户重复度分析**页签查看用户重合度。

左侧选择小程序，右侧选择待比较的小程序或公众号。

![](https://github.com/growingio/growingio-docs-v3/tree/d520f4a494f6c0635c83422f55c665597e79ee96/.gitbook/assets/image%20%28216%29.png)

| 项 | 说明 |
| :--- | :--- |


| 用户重复数据概览 | 了解选择的两个应用在周期内的用户数据，并查看重合用户的周期变化趋势。 |
| :--- | :--- |


<table>
  <thead>
    <tr>
      <th style="text-align:left">&#x7528;&#x6237;&#x6570;&#x636E;&amp;&#x91CD;&#x5408;&#x7528;&#x6237;&#x8D8B;&#x52BF;&#x56FE;</th>
      <th
      style="text-align:left">
        <p>&#x5C55;&#x793A;&#x5404;&#x4E2A;&#x5E94;&#x7528;&#x7684;&#x7528;&#x6237;&#x4E0E;&#x91CD;&#x5408;&#x7528;&#x6237;&#x91CF;&#x7684;&#x8D8B;&#x52BF;&#x56FE;&#x3002;</p>
        <p>&#x91CD;&#x5408;&#x7528;&#x6237;&#x91CF;&#xFF1A;&#x9879;&#x76EE;&#x4E0B;&#x6240;&#x6709;&#x7528;&#x6237;&#x4E0E;&#x6240;&#x9009;&#x4E24;&#x4E2A;&#x5E94;&#x7528;&#x7684;&#x91CD;&#x5408;&#x7528;&#x6237;&#x6570;&#x91CF;&#x3002;</p>
        <p>&#x4EC5;&#x4F7F;&#x7528;&#x5355;&#x4E2A;&#x5E94;&#x7528;&#x7684;&#x7528;&#x6237;&#x91CF;&#xFF1A;&#x5E94;&#x7528;&#x7684;&#x7528;&#x6237;&#x91CF;-&#x91CD;&#x5408;&#x7528;&#x6237;&#x91CF;</p>
        </th>
    </tr>
  </thead>
  <tbody></tbody>
</table>

<table>
  <thead>
    <tr>
      <th style="text-align:left">&#x8F6C;&#x5316;</th>
      <th style="text-align:left">
        <p>&#x8BBE;&#x7F6E;&#x8F6C;&#x5316;&#x76EE;&#x6807;&#x53EF;&#x67E5;&#x770B;&#x8F6C;&#x5316;&#x5B8C;&#x6210;&#x4EBA;&#x6570;&#x3002;</p>
        <p>&#x91CD;&#x5408;&#x7528;&#x6237;&#x7FA4;&#xFF1A;&#x6240;&#x9009;&#x4E24;&#x4E2A;&#x5E94;&#x7528;&#x7684;&#x91CD;&#x5408;&#x7528;&#x6237;&#x6570;&#x91CF;&#x3002;</p>
        <p>&#x4EC5;&#x4F7F;&#x7528;&#x5C0F;&#x7A0B;&#x5E8F;&#x7528;&#x6237;&#x7FA4;&#xFF1A;&#x5C0F;&#x7A0B;&#x5E8F;&#x7528;&#x6237;&#x91CF;-&#x91CD;&#x5408;&#x7528;&#x6237;&#x7FA4;</p>
      </th>
    </tr>
  </thead>
  <tbody></tbody>
</table>

| 留存 | 展示各应用次日、7日、30日留存率。 |
| :--- | :--- |


**1. 公众号的数据同步频次是怎样的？**

答：授权成功后会同步一次，之后每天晚上进行一次同步。

