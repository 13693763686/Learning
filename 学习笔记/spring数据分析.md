# Spring数据分析课堂

## 数据分析流程

* 明确问题
* 搭建框架
* 数据提取
* 数据处理
* 数据分析
* 数据展现
* 撰写报告
* 报告演讲
* 报告闭环

## 常见问题

* Max函数
  * 注意字符串和数字的区别
* 日期处理
  * 日期处理函数
  * datediff，timediff，timestampdiff
  * 时间戳到字符串
* 先聚合再计数
  * 分组函数的应用
* 一列变多行
  * 行转列，case when和group by语句
  * 列转行，union all 
* 取TOP的操作
  * 主要是利用窗口函数确定顺序后
  * 然后再做一次筛选即可
  * 特别要注意表的连接的简化
* 避免数据倾斜
  * 小表在左
    * 考虑到join的方式，左表一定会被全部的遍历
    * 因此，使左表足够的小即可

## 数据异常排除

* 数据异常原因
  * 当数据出现异常，必须去排查它，分析要有思路
  * 从最容易判断和成本最小的地方出手
  * 常识判断，节假日
  * 外部事件 --- 突然爆火的热点，社会事件
  * 产品变化
    * 产品的换版，功能问题
  * 下面准备需要复杂的操作的部分
  * 系统故障
    * 数据传输和存储出了问题
  * 数据问题
    * 业务逻辑的更改，导致指标计算的口径出现错误
  * 渠道运营
    * 渠道宣传结束
  * 用户行为
    * 业务分析用户行为
  * 流量作弊
  * 政策影响

## 常问问题

* 流量波动
* 常用的三个APP
  * 考察我们对产品的认识和落地的了解
* 商业化变现

## 四大行业数据分析

* 电商数据分析
  * 漏斗模型的使用是关键
* 金融行业
* 游戏行业
  * 流量分析和商业分析
  * 深入体验游戏和分析最后一步
* 传统销售行业
  * 传统的销售行业的目标是什么
    * 北极星指标为销售完成度
    * 根据销售完成度逐级的分解
    * 在逐级的分解中细化分解的粒度，从数据中发现并且验证结论

## 数据分析方法论

* 指标体系搭建
  * 理清业务，构建核心指标之后就是指标的分解
    * 初期
      * 盘子的大小，流量数，用户数
    * 上升期
      * 用户留存，日活
    * 后期
      * 收入市场分额
* 流量分析
  * 一个成熟的数据分析师的工作就是对数据的变化的把握
  * 渠道分析
    * 从哪里来的问题
    * 内部渠道--免费
      * 产品矩阵
      * 搜索引擎优化
    * 付费渠道
      * 社交媒体
      * APP广告
      * 软件商店
    * 渠道分类
      * 量和质的区别
      * 量代表着可曝光的用户量
      * 质代表转换率
      * 外部渠道，文案，落地页，下载，打开，浏览，注册和退出
    * 渠道的关键指标和分析方法
      * 渠道的转化率是重中之中
      * 结构分析
        * 分为多级的渠道
      * 趋势分析
        * 观察渠道的效果的变化趋势
      * 对比分析
        * 不同渠道的对比
      * 作弊分析
        * 分析是否存在不合理的行为
        * 用户行为分析和机器学习
  * 转化分析
    * 漏斗模型的过程，如何转化
  * 价值分析
    * 商业分析，用户带来的价值是什么
    * 通常是用户行为分析来精确营销，分析功能的作用 
  * 波动分析
    * 流量为什么波动的问题
    * 日活
      * 内部因素
        * 产品
        * 数据的采集
        * 用户的行为画像分析
          * 回到最初的流量分析来检验合理度
      * 外部影响
        * 节假日，热点
        * 竞品信息
    * 留存
      * 新用户留存和老用户留存
  * 路径分析
    * 通过app数据挖掘出用户的行为路径
    * 路径分析要有目的性，从问题业务发现到路径分析验证
    * 然后从APP的操作顺序一步一步地分解，观察转化率
  * 竞品分析
    * 竞品分析的关键点在于确定分析的目的
    * 挑选1-2家竞品，进行对比分析
    * 给出初步分析结论
  * 可行性报告
    * 市场的容量，盈利潜力，行业也趋势
  * 功能分析
    * 学习对手的玩法从而更好地强大自己
  * 竞争激烈情况下
    * 深刻洞察它们的版本迭代，功能变化，预防大动作
  * 爱奇艺和优酷的案例对比
    * 首先确定爱奇艺的用户群体，如果用户群体一致，优点才可用
    * 因此，首先用户群体的年龄分布的画像
    * 功能对比要从用户的需求入手，用户的需求才是分析的方向
      * 选择困难，价格，退货，功能价值

## 营销活动分析

* 活动前
  * 指标体系和报表搭建
  * 每日战报输出，活动复盘
  * 短期效果分析和长期效果分析

## 用户增长分析

* 北极星坐标的拆解和做事的目的，这样才是有意义的



## 专题分析标准化流程

* 问题的定义求解，找到根源，然后逐级下降求解，分级解决问题
* 一定要直击自己的问题，从最根本的问题，走出自己的comfort zone
* 二八定律
  * 问题罗列之后的
* 分析方法
  * 结构分析
  * 对比分析
  * 时间序列分析
  * 相关性分析
* 分析的思路
  * who
  * where
  * when
  * what 行为分析
  * why 心理分析
  * how 怎么做的
* 报告撰写
  * 结论和闭环先行
    * 先指出结论然后提数据验证
    * 报告简单，尽量少提公式

## 数据分析师的个人素养

* 行业分析
  * 波特无力和tows
* 宏观环境分析
  * PESTEL
* 产品矩阵
  * boston矩阵
* 电商行业分析
  * 范围界定
    * 网上卖东西？范围是不是太大，要不要细分
    * 确定电商的完整产业链的图，然后进行范围筛选
  * 市场规模
    * 现有市场和分布
    * 市场的潜力
    * 给出市场可以进入的理由---拼多多的成功
  * 市场规模潜力分析
    * 用中国的人口作为基数，不过最好是网络覆盖区域
    * 利用权威数据可以看到中国移动电商用户的人数
    * 然后与整体的人口做对比即可以得出潜力
    * 然后更贴切的方式是通过网民作为基数
      * 权威数据也可以得到
    * 然后发现并不是所有的网民都使用网络购物
      * 突破点
  * 分析拼多多的成功
    * 人货场的角度
    * 人即用户，低端用户需要低价
    * 货保证低价，直销无中间商
    * 场即app，操作简单快捷，各种logo都是强调秒杀的气氛，迅速操作，迅速带回家
    * 低价的原因
      * 移动支付很火，社交很火，病毒传播正常

## 数据仓库研究

* 大数据体系真的很大，关键不是要全部了解，而是要宽泛的涉猎，了解一些即可
* 大数据体系
  * 数据仓库
    * 日志采集和传输
      * kafka，feeds流和日志传输等等
    * 数据建模
      * 表的设计很重要
    * 数据管理
      * 在建模的基础上输入切片等结果
    * 数据应用
      * 利用数据得出分析结论

## 用户研究

* 用户研究是一种职业意识，任何商务人员都应该有研究思维
* 用户研究就是消费者心理学的研究
  * 有研究的背景和目的然后对症下药
* 



