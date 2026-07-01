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

#### ops-transformer库

**注意力（Attention/MLA）类**
- 新增SparseFlashMla（稀疏FlashMLA）算子，并支持稀疏注意力KV合并，提升长序列稀疏注意力场景的计算与访存效率([!6526](https://gitcode.com/cann/ops-transformer/pull/6526)、[!6429](https://gitcode.com/cann/ops-transformer/pull/6429))。
- 新增LightningIndexerV2算子([!5635](https://gitcode.com/cann/ops-transformer/pull/5635))。
- 新增aclnnBlockSparseAttentionV2接口，适配FP8量化的BlockSparseAttention算子；BlockSparseAttention在A5上支持FP8场景性能改进与BSND输入排布，950正向/推理的量化与非量化kernel支持LSE输出，并新增BlockSparseAttentionGrad反向算子([!4820](https://gitcode.com/cann/ops-transformer/pull/4820)、[!6620](https://gitcode.com/cann/ops-transformer/pull/6620)、[!6264](https://gitcode.com/cann/ops-transformer/pull/6264)、[!6565](https://gitcode.com/cann/ops-transformer/pull/6565)、[!6186](https://gitcode.com/cann/ops-transformer/pull/6186))。
- FusedInferAttentionScore支持LSE输出，AttentionUpdate在A2/A3支持sp128([!5505](https://gitcode.com/cann/ops-transformer/pull/5505)、[!5709](https://gitcode.com/cann/ops-transformer/pull/5709))。
- ScatterPaKvCache/GatherPaKvCache新增cache首轴非连续tensor支持，MlaProlog支持KVCache非连续输入([!6214](https://gitcode.com/cann/ops-transformer/pull/6214)、[!6442](https://gitcode.com/cann/ops-transformer/pull/6442))。
- RecurrentGatedDeltaRule支持state前两轴非连续，SMLAG新增torch适配及新特性支持([!6288](https://gitcode.com/cann/ops-transformer/pull/6288)、[!5916](https://gitcode.com/cann/ops-transformer/pull/5916))。

**MoE类**
- MoeInitRoutingV3非量化场景支持DropPad，UnpermuteWithRoutingMap新增N规格non-topk支持([!5826](https://gitcode.com/cann/ops-transformer/pull/5826)、[!5353](https://gitcode.com/cann/ops-transformer/pull/5353))。
- MegaMoe新增A2/A3 Tiling、静态tensor及syncfunc功能，并补充A2/A3 kernel([!6574](https://gitcode.com/cann/ops-transformer/pull/6574)、[!3608](https://gitcode.com/cann/ops-transformer/pull/3608))。

**GMM（GroupedMatmul）量化类**
- GroupedMatmulFinalizeRouting在A5上新增W8A8场景的确定性支持([!6289](https://gitcode.com/cann/ops-transformer/pull/6289))。
- GroupedMatmulSwigluQuantV2新增WeightNz MxA8W4数据流及MXFP4权重NZ格式支持([!5267](https://gitcode.com/cann/ops-transformer/pull/5267)、[!5419](https://gitcode.com/cann/ops-transformer/pull/5419)、[!5272](https://gitcode.com/cann/ops-transformer/pull/5272))。

**MC2（通信-计算融合）类**
- 新增AllToAllMatmulV2算子([!6062](https://gitcode.com/cann/ops-transformer/pull/6062))。
- AllGatherMatmulV2、AllToAllVGroupedMatmul/GroupedMatmulAllToAllV增加comm_mode通信引擎参数，支持选择通信引擎([!5340](https://gitcode.com/cann/ops-transformer/pull/5340)、[!6103](https://gitcode.com/cann/ops-transformer/pull/6103))。
- MatmulReduceScatterV2适配AICPU通信([!5515](https://gitcode.com/cann/ops-transformer/pull/5515))。

### 通信库

#### 集合通信
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


- Ascend 950PR 支持CCU场景的allGatherV/reduceScatterV算子([\#303](https://gitcode.com/cann/hccl/pull/303) [\#207](https://gitcode.com/cann/hccl/pull/207))
- Ascend 950PR 支持GE图模式&aclGraph模式下的通信算子入图([\#183](https://gitcode.com/cann/hccl/pull/183) [\#164](https://gitcode.com/cann/hccl/pull/164) [\#296](https://gitcode.com/cann/hccl/pull/296))
- Ascend 950PR 支持N秒快恢能力，提升集合通信运行可靠性([\#1126](https://gitcode.com/cann/hcomm/pull/1126) [\#1609](https://gitcode.com/cann/hcomm/pull/1609) [\#421](https://gitcode.com/cann/hccl/pull/421))
- Ascend 950PR 支持taskexception&profiling等维测能力，提升问题定位易用性([\#937](https://gitcode.com/cann/hcomm/pull/937) [\#1472](https://gitcode.com/cann/hcomm/pull/1472) [\#267](https://gitcode.com/cann/hccl/pull/267) [\#332](https://gitcode.com/cann/hccl/pull/332))
- Ascend 950PR HcclChannelAcquire接口支持AIV直驱RoCE和URMA能力，支撑通算融合算子的自定义开发([\#2032](https://gitcode.com/cann/hcomm/pull/2032))
- Atlas A3 的allreduce&reducescatter算子在AIV展开模式下支持batch一致性([\#1029](https://gitcode.com/cann/hcomm/pull/1029) [\#1032](https://gitcode.com/cann/hccl/pull/1032))

### 图框架
- 支持950DT形态图框架能力恢复

### 运行时
- 支持950DT AclGraph场景stream规格扩充至64K，解决大模型资源不足等问题([\#32976](https://gitcode.com/cann/runtime/pull/2976))

###  算子编程

#### 关键特性
- 维测能力：
  - AscendC框架基础API支持NPU Check（[PR#1557](https://gitcode.com/cann/asc-devkit/pull/1557) [PR#1467](https://gitcode.com/cann/asc-devkit/pull/1467)），增强算子运行时校验能力。
  - SIMD VF内支持printf和reg dump打印（[PR#1605](https://gitcode.com/cann/asc-devkit/pull/1605)），提供调试打印和寄存器数据dump能力。
  - Ascend 950PR/DT支持L1 Tensor数据的DumpTensor（[PR#2175](https://gitcode.com/cann/asc-devkit/pull/2175)），扩展L1层数据调试支持。
  - 新增optype_collector工具，支持检查optype重名（[PR#285](https://gitcode.com/cann/asc-tools/pull/285)）。
- 编译工程
  - 编译工程CMakeModule支持CMAKE_\<LANG\>编译选项（[PR#2055](https://gitcode.com/cann/asc-devkit/pull/2055)）；
- 基础API
  - 支持设置ctrl寄存器的饱和溢出管理（[PR#2077](https://gitcode.com/cann/asc-devkit/pull/2077)）。
- SIMT编程
  - 新增ld/st接口（[PR#2058](https://gitcode.com/cann/asc-devkit/pull/2058)）和AddrSpace类接口（[PR#1597](https://gitcode.com/cann/asc-devkit/pull/1597)），丰富SIMT内存访问编程能力。

#### 样例更新
- SIMD样例：
  - 新增最佳实践样例：matmul+gelu融合、datacopy优化、bank冲突优化、group_matmul量化组矩阵乘、simt&simd高性能编程（[PR#1814](https://gitcode.com/cann/asc-devkit/pull/1814) [PR#2137](https://gitcode.com/cann/asc-devkit/pull/2137) [PR#2141](https://gitcode.com/cann/asc-devkit/pull/2141) [PR#2166](https://gitcode.com/cann/asc-devkit/pull/2166) [PR#2363](https://gitcode.com/cann/asc-devkit/pull/2363)）。
  - 新增Ascend 950新特性样例及兼容性样例整改：loopmode数据搬运、interleave矢量计算、datacopy_gm2l1、loadmx（Load2DMX）、mmad_mx、data_copy_pad等（[PR#2336](https://gitcode.com/cann/asc-devkit/pull/2336) [PR#1899](https://gitcode.com/cann/asc-devkit/pull/1899) [PR#2124](https://gitcode.com/cann/asc-devkit/pull/2124)）。
  - 新增RegBase基础样例：基础算术、数据类型转换、归约、比较、索引等样例（[PR#1459](https://gitcode.com/cann/asc-devkit/pull/1459) [PR#1575](https://gitcode.com/cann/asc-devkit/pull/1575) [PR#2024](https://gitcode.com/cann/asc-devkit/pull/2024)）。
  - 新增SIMD VF print样例和dump样例（[PR#2558](https://gitcode.com/cann/asc-devkit/pull/2558)）。
  - 新增Tensor API入门及最佳实践样例：Matmul入门、数据搬入搬出、搬出随路量化、MX FP4最佳实践（[PR#2553](https://gitcode.com/cann/asc-devkit/pull/2553)）。
- SIMT样例：
  - 新增SIMT优化特性样例：DCache访问优化样例（[PR#2453](https://gitcode.com/cann/asc-devkit/pull/2453)）、基于transpose的仿存合并和bank冲突样例（[PR#1753](https://gitcode.com/cann/asc-devkit/pull/1753)）、最佳实践样例：通过类型对齐提升搬运效率（[PR#2297](https://gitcode.com/cann/asc-devkit/pull/2297)）。
  - 新增SIMT功能特性样例：pytorch注册自定义算子（[PR#2769](https://gitcode.com/cann/asc-devkit/pull/2769)）、编译相关样例（动态、静态、分离编译等）（[PR#2356](https://gitcode.com/cann/asc-devkit/pull/2356)）、profiling样例（[PR#1989](https://gitcode.com/cann/asc-devkit/pull/1989)）、内存屏障特性样例（[PR#1923](https://gitcode.com/cann/asc-devkit/pull/1923)）、Warp类特性样例（[PR#2876](https://gitcode.com/cann/asc-devkit/pull/2876)）、simulator样例（[PR#2692](https://gitcode.com/cann/asc-devkit/pull/2692)）、kernel log样例（[PR#2131](https://gitcode.com/cann/asc-devkit/pull/2131)）。

#### 资料文档
- 新增矩阵计算概述和计算分形介绍的文档（[PR#2533](https://gitcode.com/cann/asc-devkit/pull/2533)）。
- 优化矢量计算API文档，补充指令约束等（[PR#2676](https://gitcode.com/cann/asc-devkit/pull/2676)）。
- 增加SIMD与SIMT混合编程性能优化概述（[PR#2736](https://gitcode.com/cann/asc-devkit/pull/2736)）。
- 搭建VitePress文档站点，提供AscendC资料预览功能（[PR#2547](https://gitcode.com/cann/asc-devkit/pull/2547)）。

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