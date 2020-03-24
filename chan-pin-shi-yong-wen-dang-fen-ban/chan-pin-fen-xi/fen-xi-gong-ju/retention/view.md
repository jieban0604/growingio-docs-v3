# 视图介绍

{% tabs %}
{% tab title="用户留存视图" %}
用户留存视图给出的是一段时间内获取的用户后续留存情况；

![&#x65E5;&#x7559;&#x5B58;](https://assets.growingio.com/docs/retention/%E5%9B%BE5%EF%BC%9A%E7%94%A8%E6%88%B7%E7%95%99%E5%AD%98%E8%A7%86%E5%9B%BE_%E6%8C%89%E6%97%A5%E7%95%99%E5%AD%98.png)

* 横坐标：相对日期；日留存颗粒度下，给出的是当日、次日、2日后...n 日后；留存率曲线会随着相对日期的推移而衰减，理想情况下会稳定在一定的留存率不再衰减。如果留存率一直衰减下去接近0，说明这个产品/功能本身没有被用户认可，没有给用户带来价值。
* 次日/周/月留存：是指一段时间内获取的用户，在接下来的一个周期的留存情况；留存率越高，说明留下来的用户越多；留存率越低，说明留下来的用户越少。
* 留存曲线长期趋势：
  * **曲线稳定**：推着时间的推移，我们期望留存率会稳定在某个值。留存率曲线平滑稳定下来，说明有一部分用户稳定地留下来使用对应的产品/功能，对应地反映了产品/功能的价值；
  * **曲线一直衰减**：如果留存曲线随着时间的推移一直衰减而不能平滑稳定下来，说明我们度量的这个产品/功能没有得到用户的认可，基本上没有人在使用这个产品。
{% endtab %}

{% tab title="留存率趋势视图" %}
用户留存率趋势给出特定留存率（比如：次周留存率）随时间（绝对日期坐标）的变化。

比如，新用户次周留存率趋势可以辅助判断获客策略，好的获客策略会带来新用户次周留存率的稳定或提升。

另外我们在留存趋势视线图下，提供转置table的形式展示留存率。根据您选择的时间周期和显示留存率的时间粒度，显示留存率。表格的每列为具体每天或者某个时间区间下的留存率，每行为具体周期内的留存率。

**例：**下图为在选择了周期为过去 14 天，显示粒度为日留存下的留存率具形式展现。

![](https://docs.growingio.com/.gitbook/assets/liu-cun-qu-shi-table-zhuan-zhi.jpg)

日/周/月颗粒度下，我们提供如下的留存率趋势：

| 颗粒度 | 留存率 |
| :--- | :--- |
| 日 | 次日留存率、7日留存率、14日留存率、30日留存率 |
| 周 | 次周留存率、2周留存率、3周留存率、4周留存率 |
| 月 | 次月留存率、2月留存率、3月留存率 |

* 以 "日留存"颗粒度为例，留存图中的横坐标和留存率趋势曲线和留存表的对应关系如下图。

![](https://assets.growingio.com/docs/retention/%E5%9B%BE7%EF%BC%9A%E7%95%99%E5%AD%98%E7%8E%87%E8%B6%8B%E5%8A%BF%E8%A7%A3%E6%9E%90.png)

* 以“周留存”颗粒度为例，过去90天的留存率变化趋势图，不同颜色代表不同的不同的阶段留存率。

![](https://docs.growingio.com/.gitbook/assets/zhe-xian.png)

新增的「留存率」视图下留存表与在「用户留存」下的留存表\(除去表中的第一行“全部访问用户”的数据\)对应关系如下：

![](https://docs.growingio.com/.gitbook/assets/liu-cun-biao-yu-zhuan-zhi-hou-de-dui-ying-guan-xi.png)

同样地，您可以根据具体业务需求灵活的切换时间与显示粒度。
{% endtab %}
{% endtabs %}
