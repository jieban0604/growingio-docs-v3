# 移动端转化归因

移动端转化归因是指由于移动端 App 从广告点击，到 App 下载安装过程的非连续，导致该环节数据无法直接追踪，所以需要一套机制来判断用户的App下载激活行为是由哪个推广活动带来的实际转化，该机制即为转化归因。

## 1 如何定义用户？用户唯一设备号？ <a id="1-ru-he-ding-yi-yong-hu-yong-hu-wei-yi-she-bei-hao"></a>

对于安卓应用，GIO 优先使用 IMEI 号进行精准激活匹配，没有 IMEI 的情况下采用 Android ID 匹配，如果也没有获取到 Android ID ，则采用 IP+UA 的方式模糊匹配。 对于 iOS 应用，GIO 优先使用 IDFA 进行精准激活匹配，没有 IDFA 则使用 IP+UA 的方式模糊匹配。

## 2 归因规则是？ <a id="2-gui-yin-gui-ze-shi"></a>

按照 Last Click（最近点击）规则，同时辅以反作弊规则进行归因。系统归因时间窗默认 15 天。

