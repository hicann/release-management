# CANN 9.0.0-beta.1
## 版本下载地址
https://www.hiascend.com/cann/download

## 版本配套（待刷新）

- HDK：Ascend HDK 25.5.0 [A2](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+25.5.0)  [A3](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+25.5.0)
- Ascend Extension for Pytorch: [FrameworkPTAdapter 7.3.0](https://ascend.devcloud.huaweicloud.com/cann/run/thirdparty/8.5.0/)


##   新增特性

###  软件安装

### 算子库

- 低bit类算子和融合算子支持更多数据类型：fp8/mxfp8/hifp8/mxfp4等,并支持pertensor/perchannel/pertoken/pergroup/perblock等不同量化和组合方式
  - [全量化融合算子:quant_batch_matmul_v4](https://gitcode.com/cann/ops-nn/blob/master/matmul/quant_batch_matmul_v4/README.md)
  - [伪量化融合算子:weight_quant_batch_matmul_v2](https://gitcode.com/cann/ops-nn/blob/master/matmul/weight_quant_batch_matmul_v2/README.md)
  - [mx动态量化算子:dynamic_mx_quant](https://gitcode.com/cann/ops-nn/blob/master/quant/dynamic_mx_quant/README.md)
  - [非mx动态量化算子:dynamic_quant_v2](https://gitcode.com/cann/ops-nn/blob/master/quant/dynamic_quant_v2/README.md)
  - [mx动态量化算子:grouped_dynamic_mx_quant](https://gitcode.com/cann/ops-nn/blob/master/quant/grouped_dynamic_mx_quant/README.md)
  - [非mx动态量化算子:grouped_dynamic_block_quant](https://gitcode.com/cann/ops-nn/blob/master/quant/grouped_dynamic_block_quant/README.md)
- 提供matmul、卷积、norm和hash类算子编程的优秀实践 
  - [MatMul算子VCV性能优化实践与效果分析](https://gitcode.com/cann/ops-nn/wiki/MatMul%E7%AE%97%E5%AD%90VCV%E6%80%A7%E8%83%BD%E4%BC%98%E5%8C%96%E5%AE%9E%E8%B7%B5%E4%B8%8E%E6%95%88%E6%9E%9C%E5%88%86%E6%9E%90.md)
  - [MatMul算子性能优化实践与效果分析](https://gitcode.com/cann/ops-nn/wiki/MatMul%E7%AE%97%E5%AD%90%E6%80%A7%E8%83%BD%E4%BC%98%E5%8C%96%E5%AE%9E%E8%B7%B5%E4%B8%8E%E6%95%88%E6%9E%9C%E5%88%86%E6%9E%90.md)
- 新增<<<>>>的算子开发样例（[!620](https://gitcode.com/cann/ops-nn/pull/620)）。
- 支持编译生成静态库，发布的nn独立组件包携带静态库（[!391](https://gitcode.com/cann/ops-nn/pull/391)）。
- 算子工程支持kernel并行编译（[!779](https://gitcode.com/cann/ops-math/pull/779)）
- 算子工程日志优化（[#192](https://gitcode.com/cann/ops-math/issues/192)）
- 算子CI支持算子增量UT与冒烟（[!774](https://gitcode.com/cann/ops-math/pull/774) [!817](https://gitcode.com/cann/ops-math/pull/817)）
- 算子构建脚本支持导出预编译文件，降低算子问题定位难度（[#536](https://gitcode.com/cann/ops-math/issues/536)）
- 支持Docker部署（[!547](https://gitcode.com/cann/ops-math/pull/547)）


### 通信库

- 集合通信： 支持alltoallv算子aicpu展开模式通信task缓存功能([\#269](https://gitcode.com/cann/hcomm/pull/269))
- 集合通信： 支持单机多容器部署
- 集合通信： 支持通信域粒度的超平面QoS配置([\#283](https://gitcode.com/cann/hcomm/pull/283))
- 集合通信： A3 支持APCPU&HOST 自定义算子场景的profiling信息上报能力，提升自定义通信算子的维测能力([\#102](https://gitcode.com/cann/hccl/pull/102) [\#374](https://gitcode.com/cann/hccl/hcomm/374))
- 集合通信： A3 AICPU自定义算子场景支持host和aicpu间的kernel同步([\#90](https://gitcode.com/cann/hccl/pull/90))
- 单边通信： A3 超节点内HCCS场景下支持D2rH直传能力（本端device内存与远端host内存通信能力）([\#33](https://gitcode.com/cann/hixl/issues/33))

### 领域加速库

###  图引擎
- ES构图提供多种场景的sample ([!72](https://gitcode.com/cann/ge/pull/72) 、[!123](https://gitcode.com/cann/ge/pull/123)) 
- ES构图 Readable Dump支持子图的友好展示
- 自定义pass改图能力增强，新增原图优化之后改图的能力
- 图模式多流场景nopadding连续内存支持内存复用

### 算子编程
- 迁移高阶API样例[ascendc-api-adv](https://gitee.com/ascend/ascendc-api-adv)到[asc-devkit](https://gitcode.com/cann/asc-devkit)仓，并使用[<<<>>>调用方式](https://gitcode.com/cann/asc-devkit/tree/master/examples/03_libraries)。
- 联合毕昇编译器，优化融合编译性能。

### 编译器

### 运行时
  - 提供包版本号查询接口，根据包名查询返回字符串版本号[aclsysGetVersionStr](https://gitcode.com/cann/runtime/blob/master/docs/api_docs/aclsysGetVersionStr.md)和数值版本号[aclsysGetVersionNum](https://gitcode.com/cann/runtime/blob/master/docs/api_docs/aclsysGetVersionNum.md)。
  - 支持查询指定流（Stream）的优先级接口[aclrtStreamGetPriority](https://gitcode.com/cann/runtime/blob/master/docs/api_docs/aclrtStreamGetPriority.md)。
  - 支持查询创建Stream时设置的flag标志接口[aclrtStreamGetFlags](https://gitcode.com/cann/runtime/blob/master/docs/api_docs/aclrtStreamGetFlags.md)。
  - 支持获取Device的唯一标识UUID（Universally Unique Identifier），接口为[aclrtDeviceGetUuid](https://gitcode.com/cann/runtime/blob/master/docs/api_docs/aclrtDeviceGetUuid.md)。
  - 支持获取待查询地址所属内存块的起始地址以及内存块大小，接口为[aclrtMemGetAddressRange](https://gitcode.com/cann/runtime/blob/master/docs/api_docs/aclrtMemGetAddressRange.md)。
  - 支持设置和查询强一致性计算的参数，进程级接口为
  [aclrtSetSysParamOpt](https://gitcode.com/cann/runtime/blob/master/docs/api_docs/aclrtSetSysParamOpt.md)和[aclrtGetSysParamOpt](https://gitcode.com/cann/runtime/blob/master/docs/api_docs/aclrtGetSysParamOpt.md)，Context级接口为[aclrtCtxSetSysParamOpt](https://gitcode.com/cann/runtime/blob/master/docs/api_docs/aclrtCtxSetSysParamOpt.md)和[aclrtCtxGetSysParamOpt](https://gitcode.com/cann/runtime/blob/master/docs/api_docs/aclrtCtxGetSysParamOpt.md)。

### 开发与维测工具

#### 性能调优工具
- 多业务进程采集：msprof动态profiler支持一次性配置多个进程pid，支撑客户同时采集多个业务进程数据（[\#45](https://gitcode.com/cann/oam-tools/pull/45)）。
- 支持开启对称内存：新增-m 参数，支持开启对称内存（[\#44](https://gitcode.com/cann/oam-tools/pull/44)）。
- asys支持解析msnpureport导出的UB维测信息（[\#41](https://gitcode.com/cann/oam-tools/pull/41)）。

#### 算子开发工具

### 模型压缩工具
- 支持HIF8/MXFPx等低比特数据格式的量化能力：新增HIF8/FP8/FP4/MXFP8/MXFP4量化数据类型，新增HIF8匹配的OFMR量化算法（[\#20](https://gitcode.com/cann/amct/pull/20)）


## 删除和废弃特性

### 软件安装

- 删除特性
- 废弃特性

### 算子库

- 废弃特性（[CANN/ops-transformer](https://gitcode.com/cann/ops-transformer/G)）

  （示例）如下接口在CANN 8.5.0中被标记为废弃，将在2026年12月30日之后的版本删除（[\#12345](https://issue)）。

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

- 删除特性
- 废弃特性

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

### Atlas A3系列产品上，三机PD分离Qwen 235B分布式dp+adxl，跑精度数据集到第二个数据集（math500），P节点报错

  【引入版本】CANN 8.5.0

  【缺陷影响】HCCL展开模式（HCCL\_OP\_EXPANSION\_MODE）配置为AIV且执行broadcast算子时会偶现超时（[\#123](https://issue)）。

  【规避方案】不开启AIV展开模式。

  ### LinearParallelOperation算子部分用例精度不达标

  【引入版本】CANN 8.2.RC1

  【缺陷影响】matmul多核切K特性为性能优化特性，在算子中总体呈现正向性能收益（966个泛化shape中90%性能有提升，平均优化40%）。当前测试case主要劣化shape为内轴16以及一些非256对齐的场景（此场景技术评估为泛化边界场景），评估影响较小（[\#456](https://issue)）。

  【规避方案】修改知识库中的配置文件，将matmul多核切K的切分方式调整回之前的切分方式。



## 已修复问题

-   修复了“torch\_npu.fused\_linear\_cross\_entropy\_loss\_with\_max\_sum\_grad存在部分用例精度不达标的问题”（[\#12345](https://issue)）。
-   修复了“aclnnInplaceNanToNum算子精度测试不通过，当输入tensor为nan时，输出结果与标杆不符的问题”（[\#12356](https://issue)）。
- 集合通信：优化快恢时的状态迁移及超时机制，解决快恢失败的问题
- 集合通信：修复了大规模集群的通信域初始化失败问题（在rootinfo集群信息收集阶段）


##  文档变更说明

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

版本开源及第三方软件漏洞修复情况详见《[CANN 8.3.RC1 漏洞修补列表.xlsx](resource/CANN 8.3.RC1 漏洞修补列表.xlsx)》。