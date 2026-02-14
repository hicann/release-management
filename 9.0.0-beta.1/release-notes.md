# CANN 9.0.0-beta.1
## 版本下载地址
https://www.hiascend.com/cann/download

## 版本配套（待刷新）

- HDK：Ascend HDK 25.5.0 [A2](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+25.5.0)  [A3](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+25.5.0)
- Ascend Extension for Pytorch: [FrameworkPTAdapter 7.3.0](https://ascend.devcloud.huaweicloud.com/cann/run/thirdparty/8.5.0/)


##   新增特性

###  软件安装

### 算子库

### 通信库

### 领域加速库

###  图引擎

- （示例）支持离线编译场景下的自动融合功能，通过配置[--input\_hint\_shape](https://www.hiascend.com/document/detail/zh/canncommercial/850/devaids/atctool/atlasatcparam_16_0099.html)参数，可在编译过程中启动自动融合符号化推导功能，提升模型性能（[\#12345](https://issue)）。
- 其他新增特性...。


### 算子编程
- （示例）易用性增强：在分离式架构芯片下，提供Async异步调用接口，将AIC和AIV操作统一放到回调函数中，简化MIX融合算子编程逻辑（[\#446](https://gitcode.com/cann/ops-nn/issues/446)）。
- 其他新增特性...。

### 编译器

### 运行时

### 开发与维测工具

#### 性能调优工具

#### 算子开发工具



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

  （示例）如下路径计划在2026年12月30日之后的版本删除（[\#3456](https://issue)）。

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