## CANN 9.0.0-beta.2(开发中)

### 版本下载地址

<https://www.hiascend.com/cann/download>

### 版本配套
1、CANN与Ascend HDK版本配套关系
|CANN版本  |  配套Ascend HDK版本| 
|--|--|
|  CANN 9.0.0-beta.2|  [Ascend HDK ](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+25.5.1)|

2、 CANN组合包版本配套关系
|CANN组合包版本  |配套CANN版本  |  
|--|--|
|  [ascend-cann-ops 9.0.0-beta.2](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.0.0-beta.1/)|CANN 9.0.0-beta.2  |
|  [ascend-cann-toolkit 9.0.0-beta.2](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.0.0-beta.1/)|CANN 9.0.0-beta.2  |


**3、 CANN独立升级子包版本配套关系**
| CANN子包版本                                                 | 版本源码标签                                                 | 配套CANN版本      |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ----------------- |
| [cann-ops-math 9.0.0-beta.2](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.0.0-beta.1/) | [v9.0.0-beta.2](https://gitcode.com/cann/ops-math/tags/v9.0.0-beta.1) | CANN 9.0.0-beta.1 |
| [cann-ops-nn 9.0.0-beta.2](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.0.0-beta.1/) | [v9.0.0-beta.2](https://gitcode.com/cann/ops-nn/tags/v9.0.0-beta.1) | CANN 9.0.0-beta.1 |
| [cann-ops-cv 9.0.0-beta.2](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.0.0-beta.1/) | [v9.0.0-beta.2](https://gitcode.com/cann/ops-cv/tags/v9.0.0-beta.1) | CANN 9.0.0-beta.1 |
| [cann-ops-transformer 9.0.0-beta.2](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.0.0-beta.1/) | [v9.0.0-beta.2](https://gitcode.com/cann/ops-transformer/tags/v9.0.0-beta.1) | CANN 9.0.0-beta.1 |
| [cann-hccl 9.0.0-beta.1](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.0.0-beta.1/) | [v9.0.0-beta.1](https://gitcode.com/cann/hccl/tags/v9.0.0-beta.1) | CANN 9.0.0-beta.1 |
| [cann-hixl 9.0.0-beta.1](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.0.0-beta.1/) | [v9.0.0-beta.1](https://gitcode.com/cann/hixl/tags/v9.0.0-beta.1) | CANN 9.0.0-beta.1 |

**4、CANN开源子包版本配套关系**
| CANN子包版本                       | 版本源码标签                                                 | 配套CANN版本      |
| ---------------------------------- | ------------------------------------------------------------ | ----------------- |
| cann-opbase 9.0.0-beta.1           | [v9.0.0-beta.1](https://gitcode.com/cann/opbase/tags/v9.0.0-beta.1) | CANN 9.0.0-beta.1 |
| cann-oam-tools 9.0.0-beta.1        | [v9.0.0-beta.1](https://gitcode.com/cann/oam-tools/tags/v9.0.0-beta.1) | CANN 9.0.0-beta.1 |
| cann-asc-tools 9.0.0-beta.1        | [v9.0.0-beta.1](https://gitcode.com/cann/asc-tools/tags/v9.0.0-beta.1) | CANN 9.0.0-beta.1 |
| cann-asc-devkit 9.0.0-beta.1       | [v9.0.0-beta.1](https://gitcode.com/cann/asc-devkit/tags/v9.0.0-beta.1) | CANN 9.0.0-beta.1 |
| cann-pto-isa 9.0.0-beta.1          | [v9.0.0-beta.1](https://gitcode.com/cann/pto-isa/tags/v9.0.0-beta.1) | CANN 9.0.0-beta.1 |
| cann-ge-compiler 9.0.0-beta.1      | [v9.0.0-beta.1](https://gitcode.com/cann/ge/tags/v9.0.0-beta.1) | CANN 9.0.0-beta.1 |
| cann-ge-executor 9.0.0-beta.1      | [v9.0.0-beta.1](https://gitcode.com/cann/ge/tags/v9.0.0-beta.1) | CANN 9.0.0-beta.1 |
| cann-graph-autofusion 9.0.0-beta.1 | [v9.0.0-beta.1](https://gitcode.com/cann/graph-autofusion/tags/v9.0.0-beta.1) | CANN 9.0.0-beta.1 |
| cann-metadef 9.0.0-beta.1          | [v9.0.0-beta.1](https://gitcode.com/cann/metadef/tags/v9.0.0-beta.1) | CANN 9.0.0-beta.1 |
| cann-dflow-executor 9.0.0-beta.1   | [v9.0.0-beta.1](https://gitcode.com/cann/ge/tags/v9.0.0-beta.1) | CANN 9.0.0-beta.1 |
| cann-hcomm 9.0.0-beta.1            | [v9.0.0-beta.1](https://gitcode.com/cann/hcomm/tags/v9.0.0-beta.1) | CANN 9.0.0-beta.1 |
| cann-npu-runtime 9.0.0-beta.1      | [v9.0.0-beta.1](https://gitcode.com/cann/runtime/tags/v9.0.0-beta.1) | CANN 9.0.0-beta.1 |

##   新增特性



###  软件安装

<!--没有新增特性的组件，则删除对应组件；所有组件都不涉及新增，则写“不涉及”。-->

### 算子库

<!--新增特性仅为示例，请根据实际情况进行替换-->

#### ops-nn库

- 低bit类算子和融合算子支持更多数据类型：fp8/mxfp8/hifp8/mxfp4等，并支持pertensor/perchannel/pertoken/pergroup/perblock等不同量化和组合方式：
  - [全量化融合算子:quant_batch_matmul_v4](https://gitcode.com/cann/ops-nn/blob/9.0.0-beta.1/matmul/quant_batch_matmul_v4/README.md)。
  - [伪量化融合算子:weight_quant_batch_matmul_v2](https://gitcode.com/cann/ops-nn/blob/9.0.0-beta.1/matmul/weight_quant_batch_matmul_v2/README.md)。
- 提供matmul、卷积、norm和hash类算子编程的优秀实践：
  - [MatMul算子VCV性能优化实践与效果分析](https://gitcode.com/cann/ops-nn/wiki/MatMul%25E7%25AE%2597%25E5%25AD%2590VCV%25E6%2580%25A7%25E8%2583%25BD%25E4%25BC%2598%25E5%258C%2596%25E5%25AE%259E%25E8%25B7%25B5%25E4%25B8%258E%25E6%2595%2588%25E6%259E%259C%25E5%2588%2586%25E6%259E%2590.md)。
  - [MatMul算子性能优化实践与效果分析](https://gitcode.com/cann/ops-nn/wiki/MatMul%25E7%25AE%2597%25E5%25AD%2590%25E6%2580%25A7%25E8%2583%25BD%25E4%25BC%2598%25E5%258C%2596%25E5%25AE%259E%25E8%25B7%25B5%25E4%25B8%258E%25E6%2595%2588%25E6%259E%259C%25E5%2588%2586%25E6%259E%2590.md)。

#### ops-transformer库

- transformer相关算子在Atlas A3系列产品上能力完善：
  - [MC2 dispatch和combine算子支撑性能维测能力、类deepep接口和扩展泛化能力:moe_distribute_dispatch](https://gitcode.com/cann/ops-transformer/blob/9.0.0-beta.1/mc2/moe_distribute_dispatch_v2/README.md)。
  - [SparseFlashAttentionGrad算子能力强化，支持确定性计算等:sparse_flash_attention_grad](https://gitcode.com/cann/ops-transformer/blob/9.0.0-beta.1/attention/sparse_flash_attention_grad/docs/aclnnSparseFlashAttentionGrad.md)。
- transformer相关算子在Atlas A2系列产品上能力完善：
  - [新增AllToAllMatmul和MatmulAllToAll算子](https://gitcode.com/cann/ops-transformer/blob/9.0.0-beta.1/mc2/allto_all_matmul/README.md)。
  - [支持QuantMatmulAllToAll算子A8W8](https://gitcode.com/cann/ops-transformer/blob/9.0.0-beta.1/mc2/matmul_allto_all/README.md)。

#### ops-cv库
- image类算子支持Ascend950，覆盖 `ResizeNearestNeighborV2`、`ResizeNearestNeighborV2Grad`、`UpsampleNearest`、`UpsampleNearest3d` 等（[!284](https://gitcode.com/cann/ops-cv/pull/284) [#97](https://gitcode.com/cann/ops-cv/issues/97) [#93](https://gitcode.com/cann/ops-cv/issues/93)）。
- CI对Ascend950的编译与 UT 识别能力增强（ [!281](https://gitcode.com/cann/ops-cv/pull/281)、[!368](https://gitcode.com/cann/ops-cv/pull/368)、[#105](https://gitcode.com/cann/ops-cv/issues/105)）。
- 算子的example支持在仿真（simulator）上执行，可在不依赖真实硬件的场景下进行样例编译与执行验证，便于Ascend950适配前置联调与回归（[!567](https://gitcode.com/cann/ops-cv/pull/567) [!397](https://gitcode.com/cann/ops-cv/pull/397)）。

#### ops-math库
- 数学运算、张量变换及随机数生成支持Ascend950，覆盖`Erfc`、`Sinh`、`Asin`、`Atanh`、`BitwiseXor`、`Asinh`、`Cosh`、`Scale`、`Tan`、`Acos`、`Acosh`等（[#599](https://gitcode.com/cann/ops-math/issues/599)）。
- aclnnMul/aclnnMuls/aclnnAdd/aclnnAdds/aclnnSum等API支持非连续输入，似的相关接口性能得到提升、内存占用有优化（[!874](https://gitcode.com/cann/ops-math/pull/874)）。
- Sort算子支持数据类型补齐UINT16/UINT32/UINT64类型补齐，性能相对A2，平均提升1.5+倍（[#557](https://gitcode.com/cann/ops-math/pull/557) [#632](https://gitcode.com/cann/ops-math/pull/632)）。
- 离散类张量变换类算子性能优化，覆盖`Pad`、`Transpose`、`AsStrided` （[#569](https://gitcode.com/cann/ops-math/issues/569) [#539](https://gitcode.com/cann/ops-math/pull/539) [#495](https://gitcode.com/cann/ops-math/pull/495)）。
- 算子的example支持在仿真（simulator）上执行，可在不依赖真实硬件的场景下进行样例编译与执行验证，便于 Ascend950 适配前置联调与回归（[!563](https://gitcode.com/cann/ops-math/pull/563) [!1215](https://gitcode.com/cann/ops-math/pull/1215)）。

#### opbase库
- 基础框架库支持Ascend950平台（[#65](https://gitcode.com/cann/opbase/issues/65)）。

### 通信库



### 领域加速库



###  图引擎

- 支持离线编译场景下的自动融合功能，通过配置[--input\_hint\_shape](https://www.hiascend.com/document/detail/zh/canncommercial/850/devaids/atctool/atlasatcparam_16_0099.html)参数，可在编译过程中启动自动融合符号化推导功能，提升模型性能（[\#12345](https://issue)）。
- 其他新增特性...。


### 算子编程
- 易用性增强：在分离式架构芯片下，提供Async异步调用接口，将AIC和AIV操作统一放到回调函数中，简化MIX融合算子编程逻辑（[\#446](https://gitcode.com/cann/ops-nn/issues/446)）。
- 其他新增特性...。

### 编译器



### 运行时



### 开发与维测工具

#### 性能调优工具

#### 算子开发工具



## 删除和废弃特性

<!--没有删除特性的，则删除对应组件；所有组件都不涉及，则写“不涉及”。-->

### 软件安装

- 删除特性
- 废弃特性

### 算子库

<!--废弃特性内容仅为示例，请根据实际情况进行替换-->

#### ops-transformer库废弃特性：

如下接口在CANN 8.5.0中被标记为废弃，将在2026年12月30日之后的版本删除（[\#12345](https://issue)）。

- aclnnWeightQuantBatchMatmul接口废弃，替换为：aclnnWeightQuantBatchMatmulV3。
- aclnnQuantMatmul/aclnnQuantMatmulV2/aclnnQuantMatmulV3/aclnnQuantMatmulV4接口废弃，替换为：aclnnQuantMatmulV5。
- aclnnGroupedMatmul/aclnnGroupedMatmulV2/aclnnGroupedMatmulV3/aclnnGroupedMatmulV4接口废弃，替换为：aclnnGroupedMatmulV5。

### 通信库

- 删除特性
- 废弃特性

### 领域加速库

- 删除特性
- 废弃特性

### 图引擎

- 删除特性（示例一，删除的接口给出接口名）

  从CANN 8.5.0版本开始，不再提供DataFlow大模型切分特性，如下相关接口下线（[\#2345](https://issue)）：

  - GetModelDistributeDesc
  - xxx

- 删除特性（示例二，如果某个接口有多个原型，**需要删除其中某几个原型的**，需要给出原型定义）

  从CANN 8.5.0版本开始，不再提供DataFlow大模型切分特性，如下相关接口原型下线（[\#2345](https://issue)）：

  - Status LoadGraph\(const uint32\_t graph\_id, const std::map<std::string, std::string\> &options, const std::string &om\_file\_path\) const
  - graphStatus aclgrphBuildModel\(const std::vector\<ge::Graph\> &graphs,const std::map<std::string, std::string\> &build\_options, ModelBufferData &model\)
  - graphStatus aclgrphBuildModel\(const std::vector\<ge::Graph\>&graphs, const std::map<AscendString, AscendString\> &build\_options, ModelBufferData &model\)

- 废弃特性

  如下路径计划在2026年12月30日之后的版本删除（[\#3456](https://issue)）。

  - $\{install\_path\}/latest/runtime/include/graph目录将下线，替换目录为：$\{install\_path\}/cann/include/graph。
  - $\{install\_path\}/latest/compiler/python/func2graph目录将下线，替换为：$\{install\_path\}/cann/x86\_64-linux\(其他OS相同\)/python目录下的func2graph。

### 算子编程

- 删除特性
- 废弃特性

### 编译器

- 删除特性
- 废弃特性

### 运行时

- 删除特性
- 废弃特性

### 开发与维测工具

#### 性能调优工具

- 删除特性
- 废弃特性

#### 算子开发工具

- 删除特性
- 废弃特性

##  已知问题

<!--问题仅为示例，请根据实际情况进行替换-->

### Atlas A3系列产品上，三机PD分离Qwen 235B分布式dp+adxl，跑精度数据集到第二个数据集（math500），P节点报错

  【引入版本】CANN 8.5.0

  【缺陷影响】HCCL展开模式（HCCL\_OP\_EXPANSION\_MODE）配置为AIV且执行broadcast算子时会偶现超时（[\#123](https://issue)）。

  【规避方案】不开启AIV展开模式。

  ### LinearParallelOperation算子部分用例精度不达标

  【引入版本】CANN 8.2.RC1

  【缺陷影响】matmul多核切K特性为性能优化特性，在算子中总体呈现正向性能收益（966个泛化shape中90%性能有提升，平均优化40%）。当前测试case主要劣化shape为内轴16以及一些非256对齐的场景（此场景技术评估为泛化边界场景），评估影响较小（[\#456](https://issue)）。

  【规避方案】修改知识库中的配置文件，将matmul多核切K的切分方式调整回之前的切分方式。



## 已修复问题

<!--问题仅为示例，请根据实际情况进行替换-->

-   修复了“torch\_npu.fused\_linear\_cross\_entropy\_loss\_with\_max\_sum\_grad存在部分用例精度不达标的问题”（[\#12345](https://issue)）。
-   修复了“aclnnInplaceNanToNum算子精度测试不通过，当输入tensor为nan时，输出结果与标杆不符的问题”（[\#12356](https://issue)）。



##  文档变更说明

<!--内容仅为示例，请根据实际情况进行替换-->

### 算子编程

优化《Ascend C算子开发指南》文档结构，统一相关文档入口。该文档修改以下几方面：

- **[入门教程](https://www.hiascend.com/document/detail/zh/canncommercial/850/opdevg/Ascendcopdevg/atlas_ascendc_map_10_0002.html)**：提供快速入门教程，帮助开发者快速上手。
- **[编程指南](https://www.hiascend.com/document/detail/zh/canncommercial/850/opdevg/Ascendcopdevg/atlas_ascendc_10_00028.html)**：介绍Ascend C编程模型和编程范式、语言拓展、硬件实现等内容。
- **[算子实践参考](https://www.hiascend.com/document/detail/zh/canncommercial/850/opdevg/Ascendcopdevg/atlas_ascendc_best_practices_10_0001.html)**：整合原有的《Ascend C最佳实践》和典型模式的算子实现介绍为算子实践参考，提供算子开发、调试、性能优化全流程的实践参考。

### 图引擎

- 新增章节：构建Graph\>[使用ES极简构图构建Graph](https://www.hiascend.com/document/detail/zh/canncommercial/83RC1/graph/graphdevg/atlasag_25_0081.html)。
- 新增[推荐网络推理优秀实践](https://www.hiascend.com/document/detail/zh/canncommercial/850/graph/graphdevg/atlasag_25_0101.html)。
- 自定义Pass开发：[基于Pattern匹配实现自定义Pass修改Graph](https://www.hiascend.com/document/detail/zh/canncommercial/850/graph/graphdevg/atlasag_25_0093.html)。
- 接口参考：“构图接口”修改为“GE图引擎接口”。
- 新增[GESession API](https://www.hiascend.com/document/detail/zh/canncommercial/850/API/ascendgraphapi/atlasgeapi_07_0281.html)，后续推荐使用该目录下的接口，原有Session接口逐步废弃。

### 通信库

- 节点变更：“集合通信”变更成“通信库”，并在该节点下新增“HIXL单边通信库”。

  | 变更前                   | 变更后                   |
  | ------------------------ | ------------------------ |
  | ![](./figures/Snap1.png) | ![](./figures/Snap0.png) |

- 手册结构变更：根据业务使用场景，将《LLM Datadist开发指南》拆分成《HIXL单边通信库》和《LLM Datadist开发指南》，《HIXL单边通信库》归属“通信库”节点，《LLM Datadist开发指南》位置保持不变。

- 《HCCL集合通信库》手册架构调整，并新增“[通信算子开发](https://www.hiascend.com/document/detail/zh/canncommercial/850/commlib/hcclug/hcclopdev_000001.html)”章节。



## 漏洞修补列表

<!--表格仅为示例，请根据实际情况进行替换-->

版本开源及第三方软件漏洞修复情况详见《[CANN 8.3.RC1 漏洞修补列表.xlsx](resource/CANN 8.3.RC1 漏洞修补列表.xlsx)》。