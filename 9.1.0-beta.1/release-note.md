# CANN 9.1.0版本说明(开发中)

## 版本下载地址

<https://www.hiascend.com/cann/download>

## 版本配套

**1、CANN与Ascend HDK版本配套关系**

|CANN版本  |  配套Ascend HDK版本| 
|--|--|
| [CANN 9.0.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.0) | [Ascend HDK 26.0.RC1 ](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+26.0.RC1)<br> [Ascend HDK 25.5.2 ](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+25.5.2)  <br> [Ascend HDK 25.5.1](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+25.5.1) |
| [CANN 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) | [Ascend HDK 26.0.RC1 ](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+26.0.RC1) <br> [Ascend HDK 25.5.2 ](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+25.5.2) <br> [Ascend HDK 25.5.1 ](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+25.5.1)|


**2、 CANN组合包版本配套关系**

|ops版本  |配套toolkit版本  |  
|--|--|
| [ascend-cann-ops 9.0.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.0) | [ascend-cann-toolkit 9.0.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.0)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |
| [ascend-cann-ops 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2)  |  [ascend-cann-toolkit 9.0.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.0) <br> [ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |

**3、 CANN独立升级子包版本配套关系**

| CANN子包版本                                                 | 版本源码标签                                                 | 配套CANN版本      |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ----------------- |
| [cann-ops-math 9.0.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.0.0/) | [v9.0.0](https://gitcode.com/cann/ops-math/tags/v9.0.0)      | CANN 9.0.0<br>CANN 8.5.2 |
| [cann-ops-nn 9.0.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.0.0/) | [v9.0.0](https://gitcode.com/cann/ops-nn/tags/v9.0.0)        | CANN 9.0.0<br>CANN 8.5.2 |
| [cann-ops-cv 9.0.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.0.0/) | [v9.0.0](https://gitcode.com/cann/ops-cv/tags/v9.0.0)        | CANN 9.0.0<br>CANN 8.5.2 |
| [cann-ops-transformer 9.0.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.0.0/) | [v9.0.0](https://gitcode.com/cann/ops-transformer/tags/v9.0.0) | CANN 9.0.0<br>CANN 8.5.2 |
| [cann-hccl 9.0.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.0.0/) | [v9.0.0](https://gitcode.com/cann/hccl/tags/v9.0.0)          | CANN 9.0.0<br>CANN 8.5.2 |
| [cann-hixl 9.0.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.0.0/) | [v9.0.0](https://gitcode.com/cann/hixl/tags/v9.0.0)          | CANN 9.0.0<br>CANN 8.5.2 | 

**4、CANN开源子包版本配套关系**

| CANN子包版本                       | 版本源码标签                                                 | 配套CANN版本      |
| ---------------------------------- | ------------------------------------------------------------ | ----------------- |
| cann-opbase 9.0.0           | [v9.0.0](https://gitcode.com/cann/opbase/tags/v9.0.0)        | CANN 9.0.0   |
| cann-oam-tools 9.0.0        | [v9.0.0](https://gitcode.com/cann/oam-tools/tags/v9.0.0)     | CANN 9.0.0   |
| cann-asc-tools 9.0.0        | [v9.0.0](https://gitcode.com/cann/asc-tools/tags/v9.0.0)     | CANN 9.0.0   |
| cann-asc-devkit 9.0.0       | [v9.0.0](https://gitcode.com/cann/asc-devkit/tags/v9.0.0)    | CANN 9.0.0   |
| cann-pto-isa 9.0.0          | [v9.0.0](https://gitcode.com/cann/pto-isa/tags/v9.0.0)       | CANN 9.0.0   |
| cann-ge-compiler 9.0.0      | [v9.0.0](https://gitcode.com/cann/ge/tags/v9.0.0)            | CANN 9.0.0   |
| cann-ge-executor 9.0.0      | [v9.0.0](https://gitcode.com/cann/ge/tags/v9.0.0)            | CANN 9.0.0   |
| cann-graph-autofusion 9.0.0 | [v9.0.0](https://gitcode.com/cann/graph-autofusion/tags/v9.0.0) | CANN 9.0.0   |
| cann-metadef 9.0.0          | [v9.0.0](https://gitcode.com/cann/metadef/tags/v9.0.0)       | CANN 9.0.0   |
| cann-dflow-executor 9.0.0   | [v9.0.0](https://gitcode.com/cann/ge/tags/v9.0.0)            | CANN 9.0.0   |
| cann-hcomm 9.0.0            | [v9.0.0](https://gitcode.com/cann/hcomm/tags/v9.0.0)         | CANN 9.0.0   |
| cann-npu-runtime 9.0.0      | [v9.0.0](https://gitcode.com/cann/runtime/tags/v9.0.0)     | CANN 9.0.0   |

子包独立升级的具体操作请参考[子包独立升级](#子包独立升级)。

## 关键特性
### DS推理Decode阶段性能：npugraph_ex新增支持SuperKernel融合
在Atlas A3系列产品上，基于Aclgraph路径，提供了SuperKernel算子融合技术，在已编译的二进制代码基础上融合创建一个超级Kernel函数（简称SuperKernel），以调用子函数的方式调用多个其它内核函数，达到缩减调度开销、优化计算任务的目的，可大幅提升DS推理Decode阶段性能。
### aclgraph算子性能提升：支持非连续静态算子执行
在Atlas A2系列产品和Atlas A3系列产品上，新增支持非连续输入的静态算子执行。支持将存在非连续输入的动态算子落盘编译为静态算子后执行。该机制可以提升aclgraph整网/Superkernel算子执行效率。
     
## 新增特性

### 公共模块
不涉及。

### 算子库

#### ops-nn库

- lstm系列算子开源（样例）:
  - [ThnnFusedLstmCellGrad算子]（[!793](https://gitcode.com/cann/ops-nn/pull/793)）。
  - [SingleLayerLstmGrad算子]（[!796](https://gitcode.com/cann/ops-nn/pull/796)）。
  - [ThnnFusedLstmCell算子]（[!1999](https://gitcode.com/cann/ops-nn/pull/1999)）。
#### ops-transformer库

- transformer相关算子在Atlas A3系列产品上能力完善(样例)：
  - [MC2 dispatch和combine算子支撑Aiv直驱Roce能力:moe_distribute_dispatch](https://gitcode.com/cann/ops-transformer/blob/9.0.0-beta.1/mc2/moe_distribute_dispatch_v2/README.md)。
  - [Rope 支持算子泛化mrope_section](https://gitcode.com/cann/ops-transformer/blob/9.0.0-beta.2/posembedding/rope_with_sin_cos_cache/README.md)。
  - [BlockSparseAttention算子能力增强](https://gitcode.com/cann/ops-transformer/blob/9.0.0-beta.2/attention/block_sparse_attention/README.md)。
  - [GroupedMatmulSwigluQuantV2算子能力增强支持A4W4动态分块优化](https://gitcode.com/cann/ops-transformer/blob/9.0.0-beta.2/gmm/grouped_matmul_swiglu_quant_v2/README.md)。
  - [GroupedMatmul算子能力增强A4W4支持NZ转置动态分块优化](https://gitcode.com/cann/ops-transformer/blob/9.0.0-beta.2/gmm/grouped_matmul/README.md)。

#### ops-cv库
不涉及。
#### ops-math库

不涉及。

#### opbase库
不涉及。
### 通信库

#### 集合通信

- （样例）通信算子支持Ascend 950PR，覆盖 `Allgather`、`AllgatherV`、`Allreduce`、`AlltoAll`、`AlltoAllV`、`Broadcast`、`Reduce`、`ReduceScatter`、`ReduceScatterV`、`Scatter`、`SendRecv` 等([\#106](https://gitcode.com/cann/hccl/pull/106))。
#### 单边通信

- (样例)单边通信： Atlas A3 训练系列产品/Atlas A3 推理系列产品 支持自动建链模式，无需显式调用connect接口([\#106](https://gitcode.com/cann/hixl/issues/106))。

### 领域加速库
不涉及。
### 图引擎

- （样例）ES构图提供多种场景的sample ([!72](https://gitcode.com/cann/ge/pull/72) 、[!123](https://gitcode.com/cann/ge/pull/123)) 。

### 算子编程

- (样例)Ascend 950PR支持SIMD编程模式，提供[200+ API 接口](https://gitcode.com/cann/asc-devkit/tree/9.0.0/impl/basic_api/dav_c310)跨代兼容能力，可实现Atlas A2系列产品和Atlas A3系列产品算子平滑迁移。

### 虚拟指令集

- (样例)支持[昇腾Ascend 950PR指令集](https://gitcode.com/cann/pto-isa/tree/master/include/pto/npu/a5)（含Element-Wise、TileScalar、固定管线、访存操作、复杂操作、卷积指令、量化指令等）及对应指令的[CPU-SIM实现](https://gitcode.com/cann/pto-isa/tree/master/include/pto/cpu)
### 运行时

- 运行时Runtime支持Ascend 950PR。
- 易用性增强：
  - （样例）提供包版本号查询接口，根据包名查询返回数值版本号和字符串版本号，接口如下： 
    - [aclError aclsysGetVersionStr(char *pkgName, char * versionStr)](https://gitcode.com/cann/runtime/blob/9.0.0/docs/api_docs/aclsysGetVersionStr.md) 
    - [aclError aclsysGetVersionNum(char *pkgName，int32_t * versionNum)](https://gitcode.com/cann/runtime/blob/9.0.0/docs/api_docs/aclsysGetVersionNum.md) 
### 开发与维测工具

#### 性能调优工具

- (样例)msprof支持aicore-metrics选项采集自定义PMU指标能力（[\#136](https://gitcode.com/cann/oam-tools/pull/136)）。

#### AMCT模型压缩工具

- （样例）支持HIF8/FP8/FP4/MXFP8/MXFP4量化数据类型，支持HIF8 OFMR量化算法（[\#20](https://gitcode.com/cann/amct/pull/20)）。

## 删除和废弃特性

### 算子库

**transformer库以下接口在CANN 9.0.0中被标记为废弃，将在2027年3月30日之后的版本删除**
- （样例）aclnnGroupedMatMulAllReduce接口废弃，替换为：aclnnMatmulAllReduce。

### 模型压缩工具

（样例）模型压缩工具以下特性标记为废弃，废弃的特性将在cann 9.0.0之后的版本删除。
- 非均匀量化
- 自动混合精度
- 近似校准
- int4量化感知训练
- amct_mindspore所有特性

## 已知问题

（样例）问题一：在通信域使用int64算子的模型中，发生断链时，快恢耗时有分钟级增加到十几分钟级，影响MTTR
【引入版本】CANN 9.0.0
【缺陷影响】int64算子不支持重执行流程，无法走STEP快恢，影响断联场景下任务重执行 
【规避方案】不使用int64类型的集合通信算子，使用其他类型的算子临时替代

## 已修复问题

- （样例）修复了catlass算子编译报错“ld.lld: error: undefined symbol: CheckLogLevel”的问题。

## 文档变更说明

### 环境准备

《CANN 快速开始》调整至“环境准备”节点下，并变更为《CANN 快速安装》。

### 编程指南

#### Ascend C算子开发

- （样例）快速入门新增SIMD、SIMT简介，新增基于SIMT编程的快速入门章节。
- 编程指南中编程模型新增“AI Core SIMT编程”、“SIMD与SIMT混合编程”章节。

#### 通信算子开发

- （样例）《通信算子开发》从《HCCL集合通信库》中独立出来，作为单本手册发布至“编程指南”节点下。

#### 应用开发

（样例）《应用开发》文档大纲调整，按功能特性调整一级目录，调整点如下：
- 将“运行时管理”章节下的内容提升一个级别。

#### 图开发

- （样例）手册大纲调整：内容进行整合与重构，开发态内容移入“编程指南”章节。

### API参考

#### GE图引擎 API

- （样例）接口参考按照语言进行分类，分为C++语言、Python语言、C语言接口，其中Python语言接口为新增接口。

#### HCCL集合通信库

- （样例）《HCCL集合通信库》的“相关参考>集群信息配置”章节下，新增“rank table配置资源信息（Atlas 350 加速卡）”章节。

### 开发工具

（样例）《msLeaks内存泄漏检测工具》命名变更为《内存分析工具》。

## 漏洞修补列表

版本开源及第三方软件漏洞修复情况详见[漏洞修补列表](https://www.hiascend.com/document/detail/zh/CANNCommunityEdition/850/releasenote/releasenote_0025.html)。

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