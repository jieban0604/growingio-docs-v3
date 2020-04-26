# 应用场景

## 场景1：以提升新用户次周留存为目标的产品改版效果评估

某社交 App 想要提升新用户的次周留存率，并以此为业务目标进行了新版本产品迭代，想要评估改版的有效性。 在 GrowingIO 留存功能中，可以通过 **"维度对比"** 快速实现评估。

设置方案：选择了特定的 "起始行为"和 "留存行为"，目标用户设定为 "新访问用户"，维度对比设置如下：

```text
维度对比 > App 版本： 1 全部 2 2.1 3 2.2 4 2.3
```

![](https://assets.growingio.com/docs/retention/%E5%9B%BE15%EF%BC%9A%E7%BB%B4%E5%BA%A6%E5%AF%B9%E6%AF%94.png)

可以看出，2.3 版本的新用户次周留存率有明显提升。

## 场景2：评估产品内不同功能的表现 <a id="32-chang-jing-2"></a>

成功的产品功能应该具备 2 个特点：被更多的用户使用，该功能的用户黏度高。

| 特点 | 指标 |
| :--- | :--- |
| 更多用户使用 | 覆盖用户数量，覆盖用户占比 |
| 用户黏度高 | 该功能留存率 |

在 GrowingIO 留存功能中， 可以通过 **"行为对比 &gt; 对比不同行为的回访"** 来分析不同功能的这两个指标。 设置方法：

```text
对比不同行为的回访： 1 功能A 2 功能B 3 功能C 4 功能D
```

![](https://assets.growingio.com/docs/retention/%E5%9B%BE12%EF%BC%9A%E5%8A%9F%E8%83%BD%E5%AF%B9%E6%AF%94%E6%A1%88%E4%BE%8B%E5%9B%BE.png)

可以看出：功能 A 的表现是最好的：覆盖用户量和用户留存率都更高。

## 场景3：度量某个产品激活手段是否有效 <a id="33-chang-jing-3"></a>

某社区电商产品为了推广电商模块，采用了 "签到奖励"的激活手段，用户签到之后可以获得积分，可以用来抵扣电商购物时的部分金额，期望可以用这种激活手段来拉动电商模块的活跃度和购买转化。

由于用户签到奖励的积分长期有效，并未设置严格的有效期，因为用户可能在后续的任意时段使用。因此推荐使用留存功能来观测，用户签到领取积分之后的转化情况。同时，由于签到积分存在较低的 "薅羊毛"门槛，部分投机用户可能会坚持签到以获取积分，然后通过积分直接兑换商品。可以使用 GrowingIO **"行为对比 &gt; 对比留存行为"** 来分析。

设置方法：

```text
起始行为：签到奖励​对比留存行为： 1 签到奖励 2 购买商品
```

![](https://assets.growingio.com/docs/retention/%E5%9B%BE13%EF%BC%9A%E5%AF%B9%E6%AF%94%E7%95%99%E5%AD%98%E8%A1%8C%E4%B8%BA.png)

上线之后，使用 "签到奖励"功能的用户回来使用"签到奖励"的留存率很高，但到电商模块交易的比较少，说明签到奖励对于激活电商模块的效果不够好，需要进一步调整签到奖励策略或结合其他激活手段。

## 场景4：不同运营活动的效果衡量 <a id="34-chang-jing-4"></a>

电商、互联网金融理财、OTA 等等很多业务，发放优惠券刺激老用户服务复购是非常常见的场景。常见的优惠券有满减券、返现券、组合券等等。那么，哪种优惠券更加有效呢？对于选定的目标用户，同时对不同的用户发放不同优惠券做优惠券有效性测试。

推荐使用 GrowingIO 留存分析的 **"行为对比 &gt; 对比起始行为"**来分析。 设置方法：

```text
留存行为：投资/购买​对比起始行为： 1 A 类优惠券  2 B 类优惠券 3 C 类优惠券
```

![](https://assets.growingio.com/docs/retention/%E5%9B%BE14%EF%BC%9A%E5%AF%B9%E6%AF%94%E8%B5%B7%E5%A7%8B%E8%A1%8C%E4%B8%BA.png)

通过留存曲线可以看到，不同优惠券领取的用户量和后后续对刺激用户后续投资/购买的差异。
