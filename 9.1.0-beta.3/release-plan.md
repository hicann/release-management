# Release plan
|Stange name|Begin time|End time|
|:----------|:---------|:-------|
|Collect feature|2026/04/01|2026/04/30|
|Develop|2026/05/06|2026/05/22|
|Build|2026/05/23|2026/05/23|
|Test round 1|2026/05/24|2026/05/31|
|Test round 2|2026/06/01|2026/06/07|
|Test round 3|2026/06/08|2026/06/14|
|QA report|2026/06/23|2026/06/23|
|Release|2026/06/24|2026/06/24|

# Feture list
## 状态说明：discussion(方案讨论，需求未接受)，developing(开发中)，Testing(测试中)，Accepted(已验收)
|no|feature|status|sig|owner|
|:----|:---|:---|:--|:----|
|1|[卷积算子dX支持stride=kernel和fmap=kernel场景转MatMul]()|Accepted|ops-nn|tangweiwei2|
|2|[针对Atlas A2系列产品，AIV模式下搬运类算子支持int64、uint64、float64]()|Accepted|hccl|yanyefeng|
|3|[针对Atlas A3系列产品，单卡支持创建SIO和HCCS并发channel，通过支持卡内2Die之间多条可用的通信链路，提升通信效率和性能]()|Accepted|hccl|yanyefeng|