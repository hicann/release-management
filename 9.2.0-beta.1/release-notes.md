# CANN 9.2.0-beta.1版本说明（开发中）

## 版本下载地址

<https://www.hiascend.com/cann/download>

## 版本配套说明

CANN软件版本配套表
<table style="text-align:center;">
  <tr>
    <th>CANN</th>
    <th>驱动版本（Ascend HDK）</th>
  </tr>
  <tr>
    <td>9.2.0-beta.1</td>
    <td>26.1.0</td>
  </tr>
</table>

## 版本兼容性说明

CANN与Ascend HDK版本兼容
<table style="table-layout: fixed; width: 750px; text-align:center;">
  <colgroup>
    <col style="width: 150px">
    <col style="width: 150px">
    <col style="width: 150px">
    <col style="width: 150px">
    <col style="width: 150px">
  </colgroup>
  <thead>
    <tr>
      <th rowspan="2">CANN</th>
      <th colspan="3">驱动版本（Ascend HDK）</th>
    </tr>
    <tr>
      <th>25.5.X</th>
      <th>26.0.RC1/25.7.RC1</th>
      <th>26.1.0</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>8.5.2</td>
      <td>Y</td>
      <td>Y</td>
      <td>Y</td>
    </tr>
    <tr>
      <td>9.0.X</td>
      <td>Y</td>
      <td>Y</td>
      <td>Y</td>
    </tr>
    <tr>
      <td>9.1.X</td>
      <td>Y</td>
      <td>Y</td>
      <td>Y</td>
    </tr>
    <tr>
      <td>9.2.0-beta.1</td>
      <td>Y</td>
      <td>Y</td>
      <td>Y</td>
    </tr>    
  </tbody>
</table>

## CANN软件包内部配套关系

### CANN组合配套关系

CANN 9.1.0包含Toolkit包、算子包（ops）、加速库（NNAL）3个组合包，CANN组合包与子包的配套关系如下。其中6个子包支持独立升级，用户可根据需求灵活安装。

<table>
  <thead>
    <tr>
      <th>CANN组合包</th>
      <th>子包名称</th>
      <th>子包版本号</th>
      <th>架构</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="22">Toolkit</td>
      <td>ascendnpu-ir</td>
      <td>1.2.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-acl-extend</td>
      <td>9.2.0-beta.1</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-aoe</td>
      <td>9.2.0-beta.1</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-asc-devkit</td>
      <td><a href="https://gitcode.com/cann/asc-devkit/tags/v9.2.0-beta.1">9.2.0-beta.1</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-asc-tools</td>
      <td><a href="https://gitcode.com/cann/asc-tools/tags/v9.2.0-beta.1">9.2.0-beta.1</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-bisheng-compiler</td>
      <td>9.2.0-beta.1</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-dflow-executor</td>
      <td><a href="https://gitcode.com/cann/ge/tags/v9.2.0-beta.1">9.2.0-beta.1</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-ge-compiler</td>
      <td><a href="https://gitcode.com/cann/ge/tags/v9.2.0-beta.1">9.2.0-beta.1</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-ge-executor</td>
      <td><a href="https://gitcode.com/cann/ge/tags/v9.2.0-beta.1">9.2.0-beta.1</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-graph-autofusion</td>
      <td><a href="https://gitcode.com/cann/graph-autofusion/tags/v9.2.0-beta.1">9.2.0-beta.1</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-hcomm</td>
      <td><a href="https://gitcode.com/cann/hcomm/tags/v9.2.0-beta.1">9.2.0-beta.1</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-metadef</td>
      <td><a href="https://gitcode.com/cann/metadef/tags/v9.2.0-beta.1">9.2.0-beta.1</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-ncs</td>
      <td>9.2.0-beta.1</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-npu-runtime</td>
      <td><a href="https://gitcode.com/cann/runtime/tags/v9.2.0-beta.1">9.2.0-beta.1</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-oam-tools</td>
      <td><a href="https://gitcode.com/cann/oam-tools/tags/v9.2.0-beta.1">9.2.0-beta.1</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-opbase</td>
      <td><a href="https://gitcode.com/cann/opbase/tags/v9.2.0-beta.1">9.2.0-beta.1</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-tbe-tik</td>
      <td>9.2.0-beta.1</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-simulator</td>
      <td>9.2.0-beta.1</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-pto-isa</td>
      <td><a href="https://gitcode.com/cann/pto-isa/tags/v9.2.0-beta.1">9.2.0-beta.1</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>mindstudio-toolkit</td>
      <td>26.1.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>pyACL</td>
      <td>9.2.0-beta.1</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>test-ops</td>
      <td>9.2.0-beta.1</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td rowspan="10">算子包（ops）</td>
      <td>cann-dvpp</td>
      <td>9.2.0-beta.1</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-opbase</td>
      <td><a href="https://gitcode.com/cann/opbase/tags/v9.2.0-beta.1">9.2.0-beta.1</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-legacy</td>
      <td>9.2.0-beta.1</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-hccl</td>
      <td><a href="https://gitcode.com/cann/hccl/tags/v9.2.0-beta.1">9.2.0-beta.1</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-hixl</td>
      <td><a href="https://gitcode.com/cann/hixl/tags/v9.2.0-beta.1">9.2.0-beta.1</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-cv</td>
      <td><a href="https://gitcode.com/cann/ops-cv/tags/v9.2.0-beta.1">9.2.0-beta.1</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-math</td>
      <td><a href="https://gitcode.com/cann/ops-math/tags/v9.2.0-beta.1">9.2.0-beta.1</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-nn</td>
      <td><a href="https://gitcode.com/cann/ops-nn/tags/v9.2.0-beta.1">9.2.0-beta.1</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-transformer</td>
      <td><a href="https://gitcode.com/cann/ops-transformer/tags/v9.2.0-beta.1">9.2.0-beta.1</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-ras</td>
      <td><a href="https://gitcode.com/cann/ops-ras/tags/v9.2.0-beta.1">9.2.0-beta.1</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td rowspan="2">加速库（NNAL）</td>
      <td><a href="https://gitcode.com/cann/ascend-transformer-boost">atb</a></td>
      <td>9.2.0-beta.1</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td><a href="https://gitcode.com/cann/sip">sip</a></td>
      <td>9.2.0-beta.1</td>
      <td>arm/x86</td>
    </tr>
  </tbody>
</table>

### CANN ops与Toolkit配套关系
CANN ops包已与Toolkit解耦，支持独立升级，用户可根据使用需求灵活安装。

|ops版本  |配套toolkit版本  |
|--|--|
| [ascend-cann-ops 9.2.0-beta.1](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.2.0-beta.1) |[ascend-cann-toolkit 9.2.0-beta.1](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.2.0-beta.1)<br> [ascend-cann-toolkit 9.1.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.1.0)<br> [ascend-cann-toolkit 9.0.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.0) <br> [ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |
| [ascend-cann-ops 9.1.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.1.0) | [ascend-cann-toolkit 9.1.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.1.0)<br> [ascend-cann-toolkit 9.0.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.0)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |
| [ascend-cann-ops 9.0.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.0) | [ascend-cann-toolkit 9.1.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.1.0)<br> [ascend-cann-toolkit 9.0.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.0)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |
| [ascend-cann-ops 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) | [ascend-cann-toolkit 9.1.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.1.0)<br> [ascend-cann-toolkit 9.0.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.0) <br> [ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |


### CANN ops子包内可独立升级子包配套关系

| CANN子包版本                                                 | 版本源码标签                                                 | 配套CANN版本                           |
| ------------------------------------------------------------ | ------------------------------------------------------------ | -------------------------------------- |
| [cann-ops-math 9.2.0-beta.1](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.0-beta.1/) | [v9.2.0-beta.1](https://gitcode.com/cann/ops-math/tags/v9.2.0-beta.1)      | CANN 9.2.0-beta.1<br>CANN 9.1.0<br>CANN 9.0.0<br>CANN 8.5.2 |
| [cann-ops-nn 9.2.0-beta.1](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.0-beta.1/) | [v9.2.0-beta.1](https://gitcode.com/cann/ops-nn/tags/v9.2.0-beta.1)        | CANN 9.2.0-beta.1<br>CANN 9.1.0<br>CANN 9.0.0<br>CANN 8.5.2 |
| [cann-ops-cv 9.2.0-beta.1](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.0-beta.1/) | [v9.2.0-beta.1](https://gitcode.com/cann/ops-cv/tags/v9.2.0-beta.1)        | CANN 9.2.0-beta.1<br>CANN 9.1.0<br>CANN 9.0.0<br>CANN 8.5.2 |
| [cann-ops-transformer 9.2.0-beta.1](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.0-beta.1/) | [v9.2.0-beta.1](https://gitcode.com/cann/ops-transformer/tags/v9.2.0-beta.1) | CANN 9.2.0-beta.1<br>CANN 9.1.0<br>CANN 9.0.0<br>CANN 8.5.2 |
| [cann-hccl 9.2.0-beta.1](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.0-beta.1/) | [v9.2.0-beta.1](https://gitcode.com/cann/hccl/tags/v9.2.0-beta.1)          | CANN 9.2.0-beta.1<br>CANN 9.1.0<br>CANN 9.0.0<br>CANN 8.5.2 |
| [cann-hixl 9.2.0-beta.1](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.0-beta.1/) | [v9.2.0-beta.1](https://gitcode.com/cann/hixl/tags/v9.2.0-beta.1)          | CANN 9.2.0-beta.1<br>CANN 9.1.0<br>CANN 9.0.0<br>CANN 8.5.2 |

子包独立升级的具体操作请参考[子包独立升级](https://www.hiascend.com/document/detail/zh/CANNCommunityEdition/910/softwareinst/instg/instg_0030.html)。

## 关键特性

- **昇腾社区新增版本配套查询助手，帮忙开发者快速获取上下游软件配套关系，通过产品型号自动匹配软件包，提升环境部署效率。[点击查看详情](https://www.hiascend.com/developer/download/compatibility)**

## 新增特性

### ops-nn库

- Atlas A2 训练系列产品/Atlas A2 推理系列产品 和 Atlas A3 训练系列产品/Atlas A3 推理系列产品适配与场景支持：
  - 新增适配以下算子
    - FusedSgd（[!6220](https://gitcode.com/cann/ops-nn/pull/6220)）。

## 删除和废弃特性

### 运行时

include/driver目录头文件已迁移到pkg_inc/driver目录，include/driver目录将在2027年06月30日下线，请尽快切换至pkg_inc/driver目录。

### 图引擎

自<term>Ascend 950 系列产品</term>开始，aclblas和aclop接口不推荐使用，后续版本将逐步废弃，建议迁移至对应的aclnn算子接口。

### 算子库

- **不兼容变更**：控制类算子Identity、IdentityN、Rank、Shape和ShapeN从ops-nn迁移至ops-math。这些算子从`ops_proto_nn.h`和`es_nn`目录迁移到`ops_proto_math.h`和`es_math`目录，用户需更新相关头文件引用（[!2333](https://gitcode.com/cann/ops-math/pull/2333)、[!3995](https://gitcode.com/cann/ops-nn/pull/3995)）。

**transformer库以下接口在CANN 9.0.0中被标记为废弃，将在2027年3月30日之后的版本删除**

- aclnnGroupedMatMulAllReduce接口废弃，替换为：aclnnMatmulAllReduce。
- aclnnGroupedMatmul/aclnnGroupedMatmulV2/aclnnGroupedMatmulV3/aclnnGroupedMatmulV4接口废弃，替换为：aclnnGroupedMatmulV5。
- aclnnFusedInferAttentionScore/aclnnFusedInferAttentionScoreV2/aclnnFusedInferAttentionScoreV3接口废弃，替换为：aclnnFusedInferAttentionScoreV4。
- aclnnIncreFlashAttention/aclnnIncreFlashAttentionV2/aclnnIncreFlashAttentionV3接口废弃，替换为：aclnnIncreFlashAttentionV4。
- aclnnPromptFlashAttention/aclnnPromptFlashAttentionV2接口废弃，替换为：aclnnPromptFlashAttentionV3。
- aclnnMlaProlog/aclnnMlaPrologV2WeightNz接口废弃，替换为：aclnnMlaPrologV3WeightNz。
- aclnnMatmulAllReduceAddRmsNorm接口废弃，替换为：aclnnMatmulAllReduce和aclnnAddRmsNorm。
- aclnnQuantMatmulAllReduceAddRmsNorm接口废弃，替换为：aclnnQuantMatmulAllReduceV2和aclnnAddRmsNorm。
- aclnnWeightQuantMatmulAllReduceAddRmsNorm接口废弃，替换为：aclnnWeightQuantMatmulAllReduce和aclnnAddRmsNorm。
- aclnnInplaceQuantMatmulAllReduceAddRmsNorm接口废弃，替换为：aclnnQuantMatmulAllReduceV2和aclnnAddRmsNorm。
- aclnnInplaceMatmulAllReduceAddRmsNorm接口废弃，替换为：aclnnMatmulAllReduce和aclnnAddRmsNorm。
- aclnnInplaceWeightQuantMatmulAllReduceAddRmsNorm接口废弃，替换为：aclnnWeightQuantMatmulAllReduce和aclnnAddRmsNorm。

## 文档变更说明

### 编程指南

#### Ascend C算子开发

- 优化“入门教程”章节：
  - 更新Ascend C学习路径。
  - 新增异构系统和编程模型概括性描述。
- “编程指南”中SIMD编程模型章节进行优化调整，按照基于语言扩展层C API编程、基于Tensor的C++编程、基于Tpipe和TQue编程的维度进行分类。
- “编程指南”新增高级编程 > SuperKernel、高级编程 > SIMT协作组章节。
- 对《Ascend C API》进行了大规模重构，变更点如下：
  - 对数据搬运API和矩阵计算API等进行了目录结构调整：相关性强的API放置在临近位置，比如将矩阵计算相关的搬运接口放置在矩阵计算目录下。
  - 按照场景进行API的目录结构组织：比如矩阵计算分为矩阵计算的搬入、Mmad计算、矩阵计算的搬出。
  - 针对一类API增加必要的背景知识、概念原理介绍、通用的约束、关键特性等说明。
  - 针对每一个API补充约束说明、参数特殊值相关说明。
  - 新增API附录，附录中包含API流水类型汇总、理论性能汇总、接口边界值汇总等。
- 新增Tensor API参考文档。Tensor API接口为试验接口，在后续版本中可能会调整或改进，不保证后续兼容性。请开发者在使用过程中关注后续版本更新。
- 新增矩阵计算概述和计算分形介绍的文档（[!2533](https://gitcode.com/cann/asc-devkit/pull/2533)）。
- 优化矢量计算API文档，补充指令约束等（[!2676](https://gitcode.com/cann/asc-devkit/pull/2676)）。
- 增加SIMD与SIMT混合编程性能优化概述（[!2736](https://gitcode.com/cann/asc-devkit/pull/2736)）。
- 搭建VitePress文档站点，提供AscendC资料预览功能（[!2547](https://gitcode.com/cann/asc-devkit/pull/2547)）。

## 漏洞修补列表

版本开源及第三方软件漏洞修复情况详见[漏洞修补列表](https://www.hiascend.com/document/detail/zh/CANNCommunityEdition/910/maintenref/refdoc/refer002.html)。
