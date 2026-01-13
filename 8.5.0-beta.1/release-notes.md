# CANN 8.5.0-beta 1
## 版本地址
[CANN 8.5.0-beta 1](https://ascend.devcloud.huaweicloud.com/cann/run/software/8.5.0-beta.1/)
```
版本目录说明如下：
├── aarch64                 # CPU为ARM类型
│   ├── ops                  # ops算子包目录，用于归档算子子包
│   ├── ...
├── x86_64                   # CPU为X86类型
│   ├── ops                  # ops算子包目录，用于归档算子子包
│   ├── ...
```

## 版本配套
**1、CANN与Ascend HDK版本配套关系**

|  CANN版本| 配套Ascend HDK版本 |昇腾扩展包  |
|--|--|--|
|CANN   8.5.0-beta.1  |Ascend   HDK 25.5.0 [A2](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+25.5.0)  [A3](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+25.5.0) |  [FrameworkPTAdapter 7.3.0](https://ascend.devcloud.huaweicloud.com/cann/run/thirdparty/8.5.0-beta.1/)|


**2、 CANN独立升级子包版本配套关系**


| CANN子包版本 |  配套CANN版本 | 
|--|--|
| cann-ops-math 8.5.0-beta.1  |CANN   8.5.0-beta.1  |
| cann-ops-nn 8.5.0-beta.1  |CANN   8.5.0-beta.1  |
| cann-ops-cv 8.5.0-beta.1  |CANN   8.5.0-beta.1  |
| cann-ops-transformer 8.5.0-beta.1  |CANN   8.5.0-beta.1  |
| cann-hccl 8.5.0-beta.1  |CANN   8.5.0-beta.1  |
| cann-hixl 8.5.0-beta.1  |CANN   8.5.0-beta.1  |
## 新特性
|No|Feature|Status|Sig|Owner|
|:----|:---|:---|:--|:----|
|1|[MC2算子支持更大通信域](https://gitcode.com/cann/ops-transformer/issues/60)|Accepted|sig-ops-transformer|YuZhengzhong|
|2|[MLA非量化场景泛化能力增强](https://gitcode.com/cann/ops-transformer/issues/65)|Accepted|sig-ops-transformer|mabing1118|
|3|集合通信支持拆分hcomm通信基础包和hccl通信算子包|Accepted|sig-hccl|yanyefeng|
|4|支持通信算子开发：hcomm基础包提供通信算子开发接口|Accepted|sig-hccl|yanyefeng|
|5|支持 PyPTO：一款面向 AI 加速器的高性能编程框架，旨在简化复杂融合算子开发流程|Accepted|sig-pto|linjiashu|
|6|aclGraph特性扩大捕获图的数量规格|Accepted|sig-runtime|zhangzijing|
|7|新增IPC Event功能|Accepted|sig-runtime|zhangzijing|
|8|驱动包瘦身，部分功能可通过兼容升级包加载|Accepted|sig-runtime|zhangzijing|
|9|新增A3芯片跨机内存映射和共享特性|Accepted|sig-runtime|zhangzijing|
|10|msprof支持设备侧str2id信息回传和mspti采集|Accepted|sig-tools|jinyingqi|
|11|ge支持拆分metadef子包、ge-compiler子包、ge-compiler子包|Accepted|sig-ge|wangtao|
|12|ge支持更加易用的全新ES构图能力，自定义融合pass增强能力|Accepted|sig-ge|wangtao|
|13|[支持ops-transformer算子独立组件包](https://ascend.devcloud.huaweicloud.com/artifactory/cann-run/software/8.5.0-beta.1/)|Accepted|sig-ops-transformer|liubo75|
|14|[支持ops-nn算子独立组件包](https://ascend.devcloud.huaweicloud.com/artifactory/cann-run/software/8.5.0-beta.1/)|Accepted|sig-ops-nn|liubo75|
|15|[支持ops-cv算子独立组件包](https://ascend.devcloud.huaweicloud.com/artifactory/cann-run/software/8.5.0-beta.1/)|Accepted|sig-ops-basic|liubo75|
|16|[支持ops-math算子独立组件包](https://ascend.devcloud.huaweicloud.com/artifactory/cann-run/software/8.5.0-beta.1/)|Accepted|sig-ops-basic|liubo75|
|17|[支持opbase独立组件包](https://ascend.devcloud.huaweicloud.com/artifactory/cann-run/software/8.5.0-beta.1/)|Accepted|sig-ops-basic|liubo75|
|18|[支持ops组合包](https://ascend.devcloud.huaweicloud.com/artifactory/cann-run/software/8.5.0-beta.1/)|Accepted|sig-ops-basic|liubo75|
