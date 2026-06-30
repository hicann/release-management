# CANN 9.1.0-beta.2版本说明（开发中）

## 版本下载地址

<https://www.hiascend.com/cann/download>

## 版本配套

**1、CANN与Ascend HDK版本配套关系**

|CANN版本  |  配套Ascend HDK版本| 
|--|--|
| [CANN 9.1.0-beta.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.1.0-beta.3) | [Ascend HDK 26.0.RC1 ](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+26.0.RC1)<br> [Ascend HDK 25.5.2 ](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+25.5.2) <br> [Ascend HDK 25.5.1](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+25.5.1) |

**2、 CANN组合包版本配套关系**

|ops版本  |配套toolkit版本  |  
|--|--|
|[ascend-cann-ops 9.1.0-beta.2](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0-beta.3/) | [ascend-cann-toolkit 9.1.0-beta.3](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0-beta.3/)|

**3、 CANN独立升级子包版本配套关系**
| CANN子包版本                                                 | 版本源码标签                                                 | 配套CANN版本      |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ----------------- |
| [cann-ops-math 9.1.0-beta.2](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0-beta.3/) | [v9.1.0-beta.2](https://gitcode.com/cann/ops-math/tags/v9.1.0-beta.3) | CANN 9.1.0-beta.3 |
| [cann-ops-nn 9.1.0-beta.2](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0-beta.3/) | [v9.1.0-beta.3](https://gitcode.com/cann/ops-nn/tags/v9.1.0-beta.3) | CANN 9.1.0-beta.3 |
| [cann-ops-cv 9.1.0-beta.2](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0-beta.3/) | [v9.1.0-beta.3](https://gitcode.com/cann/ops-cv/tags/v9.1.0-beta.3) | CANN 9.1.0-beta.3 |
| [cann-ops-transformer 9.1.0-beta.2](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0-beta.3/) | [v9.1.0-beta.3](https://gitcode.com/cann/ops-transformer/tags/v9.1.0-beta.3) | CANN 9.1.0-beta.3 |
| [cann-hccl 9.1.0-beta.2](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0-beta.3/) | [v9.1.0-beta.3](https://gitcode.com/cann/hccl/tags/v9.1.0-beta.3) | CANN 9.1.0-beta.3 |
| [cann-hixl 9.1.0-beta.2](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0-beta.3/) | [v9.1.0-beta.3](https://gitcode.com/cann/hixl/tags/v9.1.0-beta.3) | CANN 9.1.0-beta.3 |

**4、CANN开源子包版本配套关系**

| CANN子包版本                       | 版本源码标签                                                 | 配套CANN版本      |
| ---------------------------------- | ------------------------------------------------------------ | ----------------- |
| cann-opbase 9.1.0-beta.2           | [v9.1.0-beta.3](https://gitcode.com/cann/opbase/tags/v9.1.0-beta.3) | CANN 9.1.0-beta.3 |
| cann-oam-tools 9.1.0-beta.2        | [v9.1.0-beta.3](https://gitcode.com/cann/oam-tools/tags/v9.1.0-beta.3) | CANN 9.1.0-beta.3 |
| cann-asc-tools 9.1.0-beta.2        | [v9.1.0-beta.3](https://gitcode.com/cann/asc-tools/tags/v9.1.0-beta.3) | CANN 9.1.0-beta.3 |
| cann-asc-devkit 9.1.0-beta.2       | [v9.1.0-beta.3](https://gitcode.com/cann/asc-devkit/tags/v9.1.0-beta.3) | CANN 9.1.0-beta.3 |
| cann-pto-isa 9.1.0-beta.2          | [v9.1.0-beta.3](https://gitcode.com/cann/pto-isa/tags/v9.1.0-beta.3) | CANN 9.1.0-beta.3 |
| cann-ge-compiler 9.1.0-beta.2      | [v9.1.0-beta.3](https://gitcode.com/cann/ge/tags/v9.1.0-beta.3) | CANN 9.1.0-beta.3 |
| cann-ge-executor 9.1.0-beta.2      | [v9.1.0-beta.3](https://gitcode.com/cann/ge/tags/v9.1.0-beta.3) | CANN 9.1.0-beta.3 |
| cann-graph-autofusion 9.1.0-beta.2 | [v9.1.0-beta.3](https://gitcode.com/cann/graph-autofusion/tags/v9.1.0-beta.3) | CANN 9.1.0-beta.3 |
| cann-metadef 9.1.0-beta.2          | [v9.1.0-beta.3](https://gitcode.com/cann/metadef/tags/v9.1.0-beta.3) | CANN 9.1.0-beta.3 |
| cann-dflow-executor 9.1.0-beta.2   | [v9.1.0-beta.3](https://gitcode.com/cann/ge/tags/v9.1.0-beta.3) | CANN 9.1.0-beta.3 |
| cann-hcomm 9.1.0-beta.2            | [v9.1.0-beta.3](https://gitcode.com/cann/hcomm/tags/v9.1.0-beta.3) | CANN 9.1.0-beta.3 |
| cann-npu-runtime 9.1.0-beta.2      | [v9.1.0-beta.3](https://gitcode.com/cann/runtime/tags/v9.1.0-beta.3) | CANN 9.1.0-beta.3 |

子包独立升级的具体操作请参考[子包独立升级](#子包独立升级)。

## 新增特性

### 算子库

#### ops-nn库
- 卷积算子功能性能优化，优化多模态网络性能，内存占用不理恶化([!735](https://gitcode.com/cann/ops-nn/pull/735))。<br>
    1）dX支持超大W输入场景对W切分；<br>
    2）dW支持确定性场景下开启性能优化特性；<br>
    3）dX支持stride=kernel和fmap=kernel场景转MM，优化性能。<br>
- Ascend950新场景支持支持：<br>
    1）引入ops-tensor，基于分层结构优化Cube类算子，减少偏移量计算和代码重复率([!5036](https://gitcode.com/cann/ops-nn/pull/5036))<br>
    2）完善低bit类算子，支持精度补偿，优化整网精度RmsNormDynamicMxQuant([!2894](https://gitcode.com/cann/ops-nn/pull/2894))，DynamicBlockMxQuant([!1824](https://gitcode.com/cann/ops-nn/pull/1824))，DualLevelQuantBatchMatmul([!1141](https://gitcode.com/cann/ops-nn/pull/1141))<br>
    3）HardswishBackwardV2([!4817](https://gitcode.com/cann/ops-nn/pull/4817))、SyncBatchNormGatherStatsWithCounts([!5973](https://gitcode.com/cann/ops-nn/pull/5973))
- nn仓工程优化：<br>
    1）Ascend950支持静态库([!3623](https://gitcode.com/cann/ops-nn/pull/3623))<br>
    2）kernel配置脚本优化([!3330](https://gitcode.com/cann/ops-nn/pull/3330))
### 通信库
- 集合通信：PDCCL支持显存资源预留功能，显存资源预留相关需求功能CANN领域内部涉及组件统一由集合通信进行分解(NPU Driver/CANN/HCCL)，包含以下功能([!1593](https://gitcode.com/cann/hcomm/pull/1593))：
	1）集合通信支持根据HDK的npu-smi或HCCN_TOOL工具提供显存资源预留配置预留显存资源；
	2）集合通信支持提供预留显存资源的预留、分配等管理功能；
	3）集合通信支持识别PDCCL进程，并向内核态申请预留显存资源；
	
- 集合通信：AIV模式下搬运类算子支持int64/uint64，RL下某些场景可能数值超过int32，因此需要使用int64/uint64([!1973](https://gitcode.com/cann/hcomm/pull/1973))：
	A2: Broadcast/AlltoAll/AlltoAllV/AlltoAllVC/AllGather/AllGatherV算子支持int64/uint64；

- 集合通信：单卡支持创建SIO和HCCS并发channel：支持卡内2Die之间多条可用的通信链路，可以提升通信效率和性能([!2100](https://gitcode.com/cann/hcomm/pull/2100))：
	A3 NPU卡内2Die之间支持SIO和HCCS链路并行传输方案：HCCL（HcclChannelAcquire接口）根据指定的链路类型创建channel
    
- HIXL 底层通信接口开放：构建 Client-Server 模式单边通信能力，全面提升建链规格与建链性能。针对批量小 Buffer 传输场景深度优化，有效降低 HBM 占用与通信资源开销（[#138](https://gitcode.com/cann/hixl/issues/138)）
- HIXL 网络传输协议扩展：单边通信新增 UBC、UBoE、Host RoCE 协议支持，完整覆盖 D2D、D2rH、rH2D、H2H 全场景数据传输（[#37](https://gitcode.com/cann/hixl/issues/37)），不同产品形态的协议支持清单可查阅 [HIXL](https://gitcode.com/cann/hixl) 社区
- HIXL 智能链路管理升级：实现通信资源自动获取及智能路由选择（[#181](https://gitcode.com/cann/hixl/issues/181)），支持按需建链（[#245](https://gitcode.com/cann/hixl/issues/245)），简化使用流程，提升易用性
- HIXL 编程 API 能力增强：扩展异步链路管理（[#207](https://gitcode.com/cann/hixl/issues/207)）、传输状态批量查询（[#208](https://gitcode.com/cann/hixl/issues/208)）两类接口，丰富异步编程范式，提升上层业务开发效率


## 已修复问题
- ops-nn: 修复了QuantBatchMatmulV3算子在Atlas推理系列产品硬件上，编译时指定ATUO_SYNC=false导致算子读写冲突的问题。
- ops-transformer: 修复了MatmulReduceScatterV2算子在小M场景下，flag位清零过快导致其他卡check不到的问题。
## 漏洞修补列表

版本开源及第三方软件漏洞修复情况详见[漏洞修补列表](https://www.hiascend.com/document/detail/zh/CANNCommunityEdition/900/maintenref/refdoc/refer002.html)。

## 子包独立升级

### 使用场景

子包独立升级提供了灵活的按需升级功能。

使用场景举例：某用户已安装了a.b.c版本的组合包Ascend-cann-toolkit和Ascend-cann-ops，由于业务需要，要求将单边通信库能力更新至x.y.z版本，此时，可通过独立升级子包cann-hixl来实现。其中a.b.c和x.y.z请替换为实际版本号。

### 操作步骤

升级子包前，请确保已安装配套版本的组合包Ascend-cann-toolkit和Ascend-cann-ops。如未安装，请参考《[CANN 软件安装](https://hiascend.com/document/redirect/CannCommunityInstSoftware)》进行安装。

子包的升级路径应与组合包的安装路径保持一致。所有子包的升级操作相同，以下以升级 cann-hixl\_x.y.z\_linux-aarch64.run 为例进行说明。

**升级场景一：**

**组合包**Ascend-cann-toolkit和Ascend-cann-ops**安装在默认路径下**（即安装时未使用“--install-path”参数）

```bash
chmod +x cann-hixl_x.y.z_linux-aarch64.run 
./cann-hixl_x.y.z_linux-aarch64.run --upgrade
```

**升级场景二：**

**组合包**Ascend-cann-toolkit和Ascend-cann-ops**安装在指定路径**“/home/custom\_path”（即安装时指定“--install-path=/home/custom\_path”）

```bash
chmod +x cann-hixl_x.y.z_linux-aarch64.run
./cann-hixl_x.y.z_linux-aarch64.run --upgrade --install-path=/home/custom_path
```