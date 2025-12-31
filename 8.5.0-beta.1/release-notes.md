# CANN 8.0.5-beta 1
## 版本配套
XXXXXXXXXXXXXXXX

- HDK：XXXXX
- Ascend Extension for Pytorch:XXXXX


## 新特性
|No|Feature|Status|Sig|Owner|
|:----|:---|:---|:--|:----|
|1|[支持通信故障快恢相关算子](https://gitcode.com/cann/ops-transformer/issues/59)|Accepted|sig-ops-transformer|YuZhengzhong|
|2|[MC2算子支持更大通信域](https://gitcode.com/cann/ops-transformer/issues/60)|Accepted|sig-ops-transformer|YuZhengzhong|
|3|[MLA非量化场景泛化能力增强](https://gitcode.com/cann/ops-transformer/issues/65)|Accepted|sig-ops-transformer|mabing1118|
|4|集合通信支持拆分hcomm通信基础包和hccl通信算子包|Accepted|sig-hccl|yanyefeng|
|5|支持通信算子开发：hcomm基础包提供通信算子开发接口|Accepted|sig-hccl|yanyefeng|
|6|支持 PyPTO：一款面向 AI 加速器的高性能编程框架，旨在简化复杂融合算子开发流程|Accepted|sig-pto|linjiashu|
|7|aclGraph特性扩大捕获图的数量规格|Accepted|sig-runtime|zhangzijing|
|8|新增IPC Event功能|Accepted|sig-runtime|zhangzijing|
|9|驱动包瘦身，部分功能可通过兼容升级包加载|Accepted|sig-runtime|zhangzijing|
|10|新增A3芯片跨机内存映射和共享特性|Accepted|sig-runtime|zhangzijing|
|11|msprof支持设备侧str2id信息回传和mspti采集|Accepted|sig-tools|jinyingqi|

## 废弃特性
本版本下车的特性，或即将下车的特性和接口
描述、下线版本、类别（特性、接口、环境变量）
|No|Desc|Ver.|Sig|Type|
|:----|:---|:---|:--|:--|
|1|[支持通信故障快恢相关算子](https://gitcode.com/cann/ops-transformer/issues/59)|8.5.0-beta1|sig-ops-transformer|特性/接口/环境变量|


## 不兼容变更
接口变化给用户原使用方法造成变化，在issue中描述前后对比，使用itemlist样式

- ops-nn仓编译构建能力增强和代码结构优化。[ops-nn#44](https://gitcode.com/cann/ops-nn/issues/44)
- opbase代码结构优化。[opbase#5](https://gitcode.com/cann/opsbase/issues/5)


## 已知问题
客户能感知的尚未解决的问题，需要在issue里描述规避方案

- ops-nn仓编译构建能力增强和代码结构优化。[ops-nn#44](https://gitcode.com/cann/ops-nn/issues/44)
- opbase代码结构优化。[opbase#5](https://gitcode.com/cann/opsbase/issues/5)

