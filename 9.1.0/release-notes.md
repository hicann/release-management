# CANN 9.1.0版本说明（开发中）

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
    <td>9.1.0</td>
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
      <td>9.1.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-aoe</td>
      <td>9.1.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-asc-devkit</td>
      <td><a href="https://gitcode.com/cann/asc-devkit/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-asc-tools</td>
      <td><a href="https://gitcode.com/cann/asc-tools/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-bisheng-compiler</td>
      <td>9.1.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-dflow-executor</td>
      <td><a href="https://gitcode.com/cann/ge/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-ge-compiler</td>
      <td><a href="https://gitcode.com/cann/ge/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-ge-executor</td>
      <td><a href="https://gitcode.com/cann/ge/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-graph-autofusion</td>
      <td><a href="https://gitcode.com/cann/graph-autofusion/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-hcomm</td>
      <td><a href="https://gitcode.com/cann/hcomm/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-metadef</td>
      <td><a href="https://gitcode.com/cann/metadef/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-ncs</td>
      <td>9.1.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-npu-runtime</td>
      <td><a href="https://gitcode.com/cann/runtime/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-oam-tools</td>
      <td><a href="https://gitcode.com/cann/oam-tools/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-opbase</td>
      <td><a href="https://gitcode.com/cann/opbase/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-tbe-tik</td>
      <td>9.1.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-simulator</td>
      <td>9.1.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-pto-isa</td>
      <td><a href="https://gitcode.com/cann/pto-isa/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>mindstudio-toolkit</td>
      <td>26.1.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>pyACL</td>
      <td>9.1.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>test-ops</td>
      <td>9.1.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td rowspan="10">算子包（ops）</td>
      <td>cann-dvpp</td>
      <td>9.1.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-opbase</td>
      <td><a href="https://gitcode.com/cann/opbase/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-legacy</td>
      <td>9.1.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-hccl</td>
      <td><a href="https://gitcode.com/cann/hccl/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-hixl</td>
      <td><a href="https://gitcode.com/cann/hixl/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-cv</td>
      <td><a href="https://gitcode.com/cann/ops-cv/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-math</td>
      <td><a href="https://gitcode.com/cann/ops-math/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-nn</td>
      <td><a href="https://gitcode.com/cann/ops-nn/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-transformer</td>
      <td><a href="https://gitcode.com/cann/ops-transformer/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-ras</td>
      <td><a href="https://gitcode.com/cann/ops-ras/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td rowspan="2">加速库（NNAL）</td>
      <td><a href="https://gitcode.com/cann/ascend-transformer-boost">atb</a></td>
      <td>9.1.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td><a href="https://gitcode.com/cann/sip">sip</a></td>
      <td>9.1.0</td>
      <td>arm/x86</td>
    </tr>
  </tbody>
</table>

### CANN ops与Toolkit配套关系
CANN ops包已与Toolkit解耦，支持独立升级，用户可根据使用需求灵活安装。

|ops版本  |配套toolkit版本  |
|--|--|
| [ascend-cann-ops 9.1.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.1.0) | [ascend-cann-toolkit 9.1.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.1.0)<br> [ascend-cann-toolkit 9.0.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.0)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |
| [ascend-cann-ops 9.0.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.0) | [ascend-cann-toolkit 9.1.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.1.0)<br> [ascend-cann-toolkit 9.0.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.0)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |
| [ascend-cann-ops 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) | [ascend-cann-toolkit 9.1.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.1.0)<br> [ascend-cann-toolkit 9.0.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.0) <br> [ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |


### CANN ops子包内可独立升级子包配套关系

| CANN子包版本                                                 | 版本源码标签                                                 | 配套CANN版本                           |
| ------------------------------------------------------------ | ------------------------------------------------------------ | -------------------------------------- |
| [cann-ops-math 9.1.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0/) | [v9.1.0](https://gitcode.com/cann/ops-math/tags/v9.1.0)      | CANN 9.1.0<br>CANN 9.0.0<br>CANN 8.5.2 |
| [cann-ops-nn 9.1.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0/) | [v9.1.0](https://gitcode.com/cann/ops-nn/tags/v9.1.0)        | CANN 9.1.0<br>CANN 9.0.0<br>CANN 8.5.2 |
| [cann-ops-cv 9.1.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0/) | [v9.1.0](https://gitcode.com/cann/ops-cv/tags/v9.1.0)        | CANN 9.1.0<br>CANN 9.0.0<br>CANN 8.5.2 |
| [cann-ops-transformer 9.1.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0/) | [v9.1.0](https://gitcode.com/cann/ops-transformer/tags/v9.1.0) | CANN 9.1.0<br>CANN 9.0.0<br>CANN 8.5.2 |
| [cann-hccl 9.1.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0/) | [v9.1.0](https://gitcode.com/cann/hccl/tags/v9.1.0)          | CANN 9.1.0<br>CANN 9.0.0<br>CANN 8.5.2 |
| [cann-hixl 9.1.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0/) | [v9.1.0](https://gitcode.com/cann/hixl/tags/v9.1.0)          | CANN 9.1.0<br>CANN 9.0.0<br>CANN 8.5.2 |

子包独立升级的具体操作请参考[子包独立升级](https://www.hiascend.com/document/detail/zh/CANNCommunityEdition/910/softwareinst/instg/instg_0030.html)。

## 关键特性

- **CANN新增支持Ascend 950DT产品，提供更完备的算子/通信/图等多维度能力，深度优化模型训练/Decode推理场景。**

- **在Ascend 950系列产品，SHMEM 首发支持 AICore 直驱 MTE/UDMA/RDMA，使能UB和RoCE通信，提供相应编程接口。**

- **在Ascend 950系列产品，Catlass新增Tile组件支持，提供丰富的MxFP8/MxFP4量化模板及样例库。**

- **新增支持DeepSeekV4相关结构融合算子SMLA/mHC，在Atlas A2 系列产品和Atlas A3 系列产品上，模型提升至1.3+以上([SMLA](https://gitcode.com/cann/ops-transformer/blob/9.1.0/attention/sparse_flash_mla/docs/aclnnSparseFlashMla.md),[SMLAG](https://gitcode.com/cann/ops-transformer/blob/9.1.0/attention/sparse_flash_mla_grad/docs/aclnnSparseFlashMlaGrad.md),[LI](https://gitcode.com/cann/ops-transformer/blob/9.1.0/attention/lightning_indexer_v2/docs/aclnnLightningIndexerV2.md),[SLIG](https://gitcode.com/cann/ops-transformer/blob/9.1.0/attention/sparse_lightning_indexer_kl_loss_grad/docs/aclnnSparseLightningIndexerKLLossGrad.md),[mhc](https://gitcode.com/cann/ops-transformer/tree/9.1.0/mhc))。**

- **新增支持[MegaMoe](https://gitcode.com/cann/ops-transformer/blob/9.1.0/mc2/mega_moe/README.md)通算融合算子，在Atlas A2 系列产品和Atlas A3 系列产品上，在Deepseek/Qwen/GLM系列模型提升至1.2+。**

- **发布Host CPU 亲和性绑核工具，支持Host CPU 亲和性绑核与资源隔离，实现性能调优([msboost](https://gitcode.com/Ascend/msboost))。**

## 新增特性

### 公共模块

- CPU性能调优：
  - Toolkit新增mindstudio-boost子包，面向HostBound业务场景，支持对关键线程自动化绑核与资源隔离，实现性能调优([!1](https://gitcode.com/Ascend/msboost/pull/1))。
- CANN适配不同昇腾硬件产品，新增OS兼容性支持。
  - Atlas 350 加速卡适配Tlinux 3.3、Tlinux 4.4、Anolis OS 8.9。
  - Atlas 950 SuperPoD、Atlas 850/850E 适配 openEuler 24.03 lts sp4。
- CANN支持Python 3.14.*版本，支持CANN在高版本Python下运行。
- 提供query_pkg_version.sh软件版本信息查询脚本，一键查询各组件的版本信息。

### 算子库

#### ops-math库
- Ascend 950PR/Ascend 950DT适配与场景支持：<br>
    1）Diag算子适配([!2185](https://gitcode.com/cann/ops-math/pull/2185))；<br>
    2）Asin算子适配([!2216](https://gitcode.com/cann/ops-math/pull/2216))；<br>
    3）PadV2算子适配([!1562](https://gitcode.com/cann/ops-math/pull/1562))；<br>
    4）BitwiseOr/BitwiseXor整型数据类型支持([!2384](https://gitcode.com/cann/ops-math/pull/2384))；<br>
    5）Cross算子适配([!2232](https://gitcode.com/cann/ops-math/pull/2232))；<br>
    6）AngleV2算子适配([!2674](https://gitcode.com/cann/ops-math/pull/2674));<br>
    7）CdistGrad（[!2981](https://gitcode.com/cann/ops-math/pull/2981)；<br>
    8）ReduceLogSum（[!2628](https://gitcode.com/cann/ops-math/pull/2628)）；<br>
    9）Complex（[!3742](https://gitcode.com/cann/ops-math/pull/3742)）；<br>
    10）AmpUpdataScale（[!3224](https://gitcode.com/cann/ops-math/pull/3224)）；<br>
    11）ReduceNansum（[!3153](https://gitcode.com/cann/ops-math/pull/3153)）；<br>
    12）Polar（[!2827](https://gitcode.com/cann/ops-math/pull/2827)）；<br>
    13）AngleV2（[!2674](https://gitcode.com/cann/ops-math/pull/2674)）；<br>
    14）Atan2（[!2315](https://gitcode.com/cann/ops-math/pull/2315)）；<br>
    15）LogAddExp（[!3150](https://gitcode.com/cann/ops-math/pull/3150)；<br>
    16）TopK算子NPU内存占用优化，模型场景shape(n, s), s > 100000000,  s/200 > topk > s/50，额外申请内存相比输入+输出不超过100%，其余场景不劣化（[!3183](https://gitcode.com/cann/ops-math/pull/3183)）；<br>
    17）AddN算子新增aclnn接口支持（[!2720](https://gitcode.com/cann/ops-math/pull/2720) [!3587](https://gitcode.com/cann/ops-math/pull/3587)）；<br>
    18）cholesky算子支持大尾轴场景输入（[!2255](https://gitcode.com/cann/ops-math/pull/2255)）；<br>
    19）ReduceSum算子支持bool输入（[!3014](https://gitcode.com/cann/ops-math/pull/3014)）

- 性能优化：<br>
    1）Sort算子小轴场景排序性能优化([!2985](https://gitcode.com/cann/ops-math/pull/2985))；<br>
    2）随机数算子生成性能优化([!3590](https://gitcode.com/cann/ops-math/pull/3590))；<br>
    3）TopkV2算子性能优化，提升int64索引场景计算效率([!2564](https://gitcode.com/cann/ops-math/pull/2564))；<br>
    4）AICPU算子性能优化，覆盖ClipByValueV2([!2460](https://gitcode.com/cann/ops-math/pull/2460))、ConcatV2([!2395](https://gitcode.com/cann/ops-math/pull/2395))、CumSum([!2262](https://gitcode.com/cann/ops-math/pull/2262))。<br>
- 工程优化：<br>
    1）并行解压编译加速([!2332](https://gitcode.com/cann/ops-math/pull/2332))；<br>
    2）统一引用CANN公共仓构建API，精简冗余构建脚本([!2372](https://gitcode.com/cann/ops-math/pull/2372))；<br>
    3）去除gawk外部依赖，采用纯bash实现时间戳格式化([!2407](https://gitcode.com/cann/ops-math/pull/2407))。<br>

#### ops-cv库
- Ascend 950PR/Ascend 950DT新增适配以下算子：<br>
  - 新增适配以下算子：<br>
    - GridSampler2DGrad算子([!847](https://gitcode.com/cann/ops-cv/pull/847))；<br>
    - UpsampleNearestExact2d/3d算子([!851](https://gitcode.com/cann/ops-cv/pull/851))；<br>
    - UpsampleNearestExactGrad算子([!798](https://gitcode.com/cann/ops-cv/pull/798))；<br>
    - UpsampleTrilinear3d算子([!927](https://gitcode.com/cann/ops-cv/pull/927))；<br>
    - CIoU算子([!833](https://gitcode.com/cann/ops-cv/pull/833))；<br>
    - BlendFaceBgPartTwo算子([!825](https://gitcode.com/cann/ops-cv/pull/825))；<br>
    - SpatialTransformer算子([!698](https://gitcode.com/cann/ops-cv/pull/698))；<br>
    - adjust_saturation算子([!696](https://gitcode.com/cann/ops-cv/pull/696))；<br>
    - scaleandtranslate算子([!693](https://gitcode.com/cann/ops-cv/pull/693))；<br>
    - BoundingBoxEncode算子([!1049](https://gitcode.com/cann/ops-cv/pull/1049))；<br>
    - NMSWithMask算子([!560](https://gitcode.com/cann/ops-cv/pull/560))；<br>
    - ExtractGlimpseV2、UpsampleBicubic2d算子([!1039](https://gitcode.com/cann/ops-cv/pull/1039))；<br>
    - UpsampleNearestExact1d及系列反向算子([!830](https://gitcode.com/cann/ops-cv/pull/830) [!798](https://gitcode.com/cann/ops-cv/pull/798))；<br>
  - 算子新增特性支持：<br>
    - AIPP新增CSC色域转换能力，支持YUV420SP/U8、RGB888/U8、BGR888/U8、XRGB8888/U8等多种格式之间的色域转换([!765](https://gitcode.com/cann/ops-cv/pull/765)），并新增动态AIPP通路支持（[!802](https://gitcode.com/cann/ops-cv/pull/802))；<br>
    - GridSample2D算子新增BF16数据类型支持([!715](https://gitcode.com/cann/ops-cv/pull/715) [!751](https://gitcode.com/cann/ops-cv/pull/751))；<br>
- 性能优化：<br>
    - ResizeNearestNeighborV2算子NCHW格式性能优化([!822](https://gitcode.com/cann/ops-cv/pull/822))；<br>
    - GridSamplerGrad算子性能优化([!946](https://gitcode.com/cann/ops-cv/pull/946))。<br>
- 工程优化：<br>
    - ops-cv安装优化改造，解压即安装。<br>
    - 新增cv常量折叠算子流程，支持CropAndResize等算子在编译期进行常量折叠优化([!690](https://gitcode.com/cann/ops-cv/pull/690))；<br>

#### opbase仓
- 新增特性：<br>
    1）支持float8/float6/float4数据类型及资料([!298](https://gitcode.com/cann/opbase/pull/298)、[!479](https://gitcode.com/cann/opbase/pull/479)、[!486](https://gitcode.com/cann/opbase/pull/486))；<br>
    2）reduce模板混合精度支持([!255](https://gitcode.com/cann/opbase/pull/255))；<br>
    3）新增非连续输入算子静态支持([!346](https://gitcode.com/cann/opbase/pull/346)、[!353](https://gitcode.com/cann/opbase/pull/353))；<br>
    4）日志接口DFX增强([!350](https://gitcode.com/cann/opbase/pull/350)、[!448](https://gitcode.com/cann/opbase/pull/448)、[!513](https://gitcode.com/cann/opbase/pull/513)、[!299](https://gitcode.com/cann/opbase/pull/299))。<br>
- 性能优化：<br>
    1）broadcast非连续tensor性能优化([!317](https://gitcode.com/cann/opbase/pull/317))；<br>
    2）优化build.sh增量编译性能，复用CMake缓存避免重复配置([!391](https://gitcode.com/cann/opbase/pull/391))。<br>
- 工程优化：<br>
    1）切换工程构建打包依赖至CANN公共仓([!361](https://gitcode.com/cann/opbase/pull/361))；<br>
    2）安装优化改造，解压即安装([!308](https://gitcode.com/cann/opbase/pull/308))。<br>

#### ops-nn库
- 卷积算子功能性能优化，优化多模态网络性能，内存占用不劣化([!735](https://gitcode.com/cann/ops-nn/pull/735))。<br>
    1）dX支持超大W输入场景对W切分；<br>
    2）dW支持确定性场景下开启性能优化特性；<br>
    3）dX支持stride=kernel和fmap=kernel场景转MM，优化性能。<br>
- Ascend 950PR/Ascend 950DT新场景支持：<br>
    1）引入ops-tensor，基于分层结构优化Cube类算子，减少偏移量计算和代码重复率([!5036](https://gitcode.com/cann/ops-nn/pull/5036))<br>
    2）完善低bit类算子，支持精度补偿，优化整网精度RmsNormDynamicMxQuant([!2894](https://gitcode.com/cann/ops-nn/pull/2894))，DynamicBlockMxQuant([!1824](https://gitcode.com/cann/ops-nn/pull/1824))，DualLevelQuantBatchMatmul([!1141](https://gitcode.com/cann/ops-nn/pull/1141))<br>
    3）HardswishBackwardV2([!4817](https://gitcode.com/cann/ops-nn/pull/4817))、SyncBatchNormGatherStatsWithCounts([!5973](https://gitcode.com/cann/ops-nn/pull/5973))
- nn仓工程优化：<br>
    1）Ascend 950PR/Ascend 950DT支持静态库([!3623](https://gitcode.com/cann/ops-nn/pull/3623))<br>
    2）kernel配置脚本优化([!3330](https://gitcode.com/cann/ops-nn/pull/3330))

- Atlas A2A3系列产品 Cube类算子能力增强，优化网络性能并减少部分场景的内存占用：<br>
    1）aclnnMatmulWeightNz性能优化([!5444](https://gitcode.com/cann/ops-nn/pull/5444))([!5105](https://gitcode.com/cann/ops-nn/pull/5105))<br>
    2）aclnnTransposeBatchMatmul放开B*K < 65536的限制([!4240](https://gitcode.com/cann/ops-nn/pull/4240))<br>
    3）aclnnBatchMatmul FP32数据类型下大Batch小MKN场景性能优化([!6103](https://gitcode.com/cann/ops-nn/pull/6103))([!7264](https://gitcode.com/cann/ops-nn/pull/7264))<br>
    4）Cube类算子支持配置out_dtype([!4823](https://gitcode.com/cann/ops-nn/pull/4823))([!5481](https://gitcode.com/cann/ops-nn/pull/5481))([!5602](https://gitcode.com/cann/ops-nn/pull/5602))<br>
    5）Cube类算子内存占用优化([!5356](https://gitcode.com/cann/ops-nn/pull/5356))([!5864](https://gitcode.com/cann/ops-nn/pull/5864))<br>

#### ops-transformer库

**注意力（Attention/MLA）类**
- 新增SparseFlashMla（稀疏FlashMLA）算子，并支持稀疏注意力KV合并，提升长序列稀疏注意力场景的计算与访存效率([!6526](https://gitcode.com/cann/ops-transformer/pull/6526)、[!6429](https://gitcode.com/cann/ops-transformer/pull/6429))。
- 新增LightningIndexerV2算子([!5635](https://gitcode.com/cann/ops-transformer/pull/5635))。
- 新增aclnnBlockSparseAttentionV2接口，适配FP8量化的BlockSparseAttention算子；BlockSparseAttention在A5上支持FP8场景性能改进与BSND输入排布，Ascend 950PR/Ascend 950DT正向/推理的量化与非量化kernel支持LSE输出，并新增BlockSparseAttentionGrad反向算子([!4820](https://gitcode.com/cann/ops-transformer/pull/4820)、[!6620](https://gitcode.com/cann/ops-transformer/pull/6620)、[!6264](https://gitcode.com/cann/ops-transformer/pull/6264)、[!6565](https://gitcode.com/cann/ops-transformer/pull/6565)、[!6186](https://gitcode.com/cann/ops-transformer/pull/6186))。
- FusedInferAttentionScore支持LSE输出，AttentionUpdate在A2/A3支持sp128([!5505](https://gitcode.com/cann/ops-transformer/pull/5505)、[!5709](https://gitcode.com/cann/ops-transformer/pull/5709))。
- ScatterPaKvCache/GatherPaKvCache新增cache首轴非连续tensor支持，MlaProlog支持KVCache非连续输入([!6214](https://gitcode.com/cann/ops-transformer/pull/6214)、[!6442](https://gitcode.com/cann/ops-transformer/pull/6442))。
- RecurrentGatedDeltaRule支持state前两轴非连续，SMLAG新增torch适配及新特性支持([!6288](https://gitcode.com/cann/ops-transformer/pull/6288)、[!5916](https://gitcode.com/cann/ops-transformer/pull/5916))。

**MoE类**
- MoeInitRoutingV3非量化场景支持DropPad，UnpermuteWithRoutingMap新增N规格non-topk支持([!5826](https://gitcode.com/cann/ops-transformer/pull/5826)、[!5353](https://gitcode.com/cann/ops-transformer/pull/5353))。
- MegaMoe新增A2/A3 Tiling、静态tensor及syncfunc功能，并补充A2/A3 kernel([!6574](https://gitcode.com/cann/ops-transformer/pull/6574)、[!3608](https://gitcode.com/cann/ops-transformer/pull/3608))。

**GMM（GroupedMatmul）量化类**
- GroupedMatmulFinalizeRouting在A5上新增W8A8场景的确定性支持([!6289](https://gitcode.com/cann/ops-transformer/pull/6289))。
- GroupedMatmulSwigluQuantV2新增WeightNz MxA8W4数据流及MXFP4权重NZ格式支持([!5267](https://gitcode.com/cann/ops-transformer/pull/5267)、[!5419](https://gitcode.com/cann/ops-transformer/pull/5419)、[!5272](https://gitcode.com/cann/ops-transformer/pull/5272))。
- GMM和GMMAdd GlistType规格增强([!4844](https://gitcode.com/cann/ops-transformer/pull/4844)、[!3725](https://gitcode.com/cann/ops-transformer/pull/3725))。

**MC2（通信-计算融合）类**
- 新增AllToAllMatmulV2算子([!6062](https://gitcode.com/cann/ops-transformer/pull/6062))。
- AllGatherMatmulV2、AllToAllVGroupedMatmul/GroupedMatmulAllToAllV增加comm_mode通信引擎参数，支持选择通信引擎([!5340](https://gitcode.com/cann/ops-transformer/pull/5340)、[!6103](https://gitcode.com/cann/ops-transformer/pull/6103))。
- MatmulReduceScatterV2适配AICPU通信([!5515](https://gitcode.com/cann/ops-transformer/pull/5515))。

**Mhc类**
- 【A2/A3】支持MhcPost算子([!3670](https://gitcode.com/cann/ops-transformer/pull/3670))。
- 【A2/A3】支持MhcPostBackward算子([!4377](https://gitcode.com/cann/ops-transformer/pull/4377))。
- 【A2/A3】支持MhcPreSinkhorn算子([!5033](https://gitcode.com/cann/ops-transformer/pull/5033))。
- 【A2/A3】支持MhcPreSinkhornBackward算子([!4760](https://gitcode.com/cann/ops-transformer/pull/4760))。

### 通信库

#### 集合通信
- 集合通信：PDCCL支持显存资源预留功能，显存资源预留相关需求功能CANN领域内部涉及组件统一由集合通信进行分解(NPU Driver/CANN/HCCL)，包含以下功能([!1593](https://gitcode.com/cann/hcomm/pull/1593))：
	1）集合通信支持根据HDK的npu-smi或HCCN_TOOL工具提供显存资源预留配置预留显存资源；
	2）集合通信支持提供预留显存资源的预留、分配等管理功能；
	3）集合通信支持识别PDCCL进程，并向内核态申请预留显存资源；

- HIXL 底层通信接口开放：构建 Client-Server 模式单边通信能力，全面提升建链规格与建链性能。针对批量小 Buffer 传输场景深度优化，有效降低 HBM 占用与通信资源开销（[!138](https://gitcode.com/cann/hixl/issues/138)）
- HIXL 网络传输协议扩展：单边通信新增 UBC、UBoE、Host RoCE 协议支持，完整覆盖 D2D、D2rH、rH2D、H2H 全场景数据传输（[!37](https://gitcode.com/cann/hixl/issues/37)），不同产品形态的协议支持清单可查阅 [HIXL](https://gitcode.com/cann/hixl) 社区
- HIXL 智能链路管理升级：实现通信资源自动获取及智能路由选择（[!181](https://gitcode.com/cann/hixl/issues/181)），支持按需建链（[!245](https://gitcode.com/cann/hixl/issues/245)），简化使用流程，提升易用性
- HIXL 编程 API 能力增强：扩展异步链路管理（[!207](https://gitcode.com/cann/hixl/issues/207)）、传输状态批量查询（[!208](https://gitcode.com/cann/hixl/issues/208)）两类接口，丰富异步编程范式，提升上层业务开发效率


- Ascend 950PR 支持CCU场景的allGatherV/reduceScatterV算子([!303](https://gitcode.com/cann/hccl/pull/303) [!207](https://gitcode.com/cann/hccl/pull/207))
- Ascend 950PR 支持GE图模式&aclGraph模式下的通信算子入图([!183](https://gitcode.com/cann/hccl/pull/183) [!164](https://gitcode.com/cann/hccl/pull/164) [!296](https://gitcode.com/cann/hccl/pull/296))
- Ascend 950PR 支持N秒快恢能力，提升集合通信运行可靠性([!1126](https://gitcode.com/cann/hcomm/pull/1126) [!1609](https://gitcode.com/cann/hcomm/pull/1609) [!421](https://gitcode.com/cann/hccl/pull/421))
- Ascend 950PR 支持taskexception&profiling等维测能力，提升问题定位易用性([!937](https://gitcode.com/cann/hcomm/pull/937) [!1472](https://gitcode.com/cann/hcomm/pull/1472) [!267](https://gitcode.com/cann/hccl/pull/267) [!332](https://gitcode.com/cann/hccl/pull/332))
- Ascend 950PR HcclChannelAcquire接口支持AIV直驱RoCE和URMA能力，支撑通算融合算子的自定义开发([!2032](https://gitcode.com/cann/hcomm/pull/2032))
- [A2/A3]单卡多进程能力新增支持MC2场景([!1880](https://gitcode.com/cann/hcomm/pull/1880))
- [A2/A3]aclGraph场景下资源管理优化，支撑通信资源增量刷新([!2405](https://gitcode.com/cann/hcomm/pull/2405) [!2502](https://gitcode.com/cann/hcomm/pull/2502))
- [A3]跨超节点场景性能优化，ReduceScatter/AllGather算子支持跨超pipeline算法([!2071](https://gitcode.com/cann/hcomm/pull/2071) [!1931](https://gitcode.com/cann/hcomm/pull/1931))
- [A3]新增支持双机背靠背RoCE直连机型通信([!2642](https://gitcode.com/cann/hcomm/pull/2642) [!3433](https://gitcode.com/cann/hcomm/pull/3433))
- [A5]标卡支持跨PCIE SW进行通信([!1997](https://gitcode.com/cann/hcomm/pull/1799) [!707](https://gitcode.com/cann/hccl/pull/707))
    AllReduce、ReduceScatter、AllGather、Reduce、Scatter、Alltoall、Alltoallv、Send、Recv等算子支持通信

### 图引擎
- 支持Ascend 950DT形态图引擎能力恢复。
- ge.autoMultistreamParallelMode新增MainStream和LoadBalance选项，基于最小路径覆盖算法将静态Shape模型的计算节点自动划分至最少逻辑流，实现多流并行加速。
- 新增PortableOp算子类型，面向离线推理场景提供自定义算子的序列化与反序列化能力。
- ATC和aclgrph接口支持集群配置文件路径设置，用于生成含有HCCL通信任务的离线OM模型，满足多卡离线推理场景下的通信域配置需求。

### 领域加速库

#### Ascend Transformer Boost加速库

- **Ascend 950PR/Ascend 950DT 核心算子接入**
批量落地 GELU、LayerNorm、MatmulEinSum、RmsNormQuant、SwiGluQuant（ACLNN V2）、Linear 反量化，以及 AllGather / AllReduce / ReduceScatter 等通信算子 A5 支持（[!1994](https://gitcode.com/cann/ascend-transformer-boost/pull/1994) [!2089](https://gitcode.com/cann/ascend-transformer-boost/pull/2089) [!2090](https://gitcode.com/cann/ascend-transformer-boost/pull/2090) [!2060](https://gitcode.com/cann/ascend-transformer-boost/pull/2060) [!2097](https://gitcode.com/cann/ascend-transformer-boost/pull/2097) [!2103](https://gitcode.com/cann/ascend-transformer-boost/pull/2103) [!2091](https://gitcode.com/cann/ascend-transformer-boost/pull/2091)）。

- **Attention / KV Cache 推理增强**
Paged Attention 950 升级 ACLNN FIA v5；Paged Attention / Flash Attention 新增 NORM_COMPRESS 掩码；MLA decode 支持 SWA 滑动窗口；950 ReshapeAndCache 单入单出能力落地（[!2069](https://gitcode.com/cann/ascend-transformer-boost/pull/2069) [!2114](https://gitcode.com/cann/ascend-transformer-boost/pull/2114) [!2116](https://gitcode.com/cann/ascend-transformer-boost/pull/2116) [!2078](https://gitcode.com/cann/ascend-transformer-boost/pull/2078) [!2065](https://gitcode.com/cann/ascend-transformer-boost/pull/2065)）。

- **torch_atb 独立编译与 ABI 体系**
torch*atb 从主库解耦独立编译，默认出包 ABI 切换 cxx*abi1；wheel 命名规范、安装脚本自动检测/安装 torch，安装部署链路打通（[!2021](https://gitcode.com/cann/ascend-transformer-boost/pull/2021) [!2086](https://gitcode.com/cann/ascend-transformer-boost/pull/2086) [!2118](https://gitcode.com/cann/ascend-transformer-boost/pull/2118)）。

- **开发者文档与测试框架**
新增测试框架指南，补齐 cxx_abi 判断、CANN 9.1 / PyTorch 26.0.0 版本配套说明（[!2120](https://gitcode.com/cann/ascend-transformer-boost/pull/2120) [!2121](https://gitcode.com/cann/ascend-transformer-boost/pull/2121) [!2126](https://gitcode.com/cann/ascend-transformer-boost/pull/2126) [!2136](https://gitcode.com/cann/ascend-transformer-boost/pull/2136)）。

#### Ascend Signal Processing Boost加速库

- FFT 1D C2C算子支持Ascend 950芯片（[!69](https://gitcode.com/cann/sip/pull/69)）。
- FFT 1D C2R算子支持Ascend 950芯片（[!73](https://gitcode.com/cann/sip/pull/73)）。
- FFT 1D R2C算子支持Ascend 950芯片（[!73](https://gitcode.com/cann/sip/pull/73)）。
- Hadamard算子支持Ascend 950芯片（[!76](https://gitcode.com/cann/sip/pull/76)）。

### 运行时
- 支持Ascend 950DT AclGraph场景stream规格扩充至64k，解决大模型资源不足等问题([\#2976](https://gitcode.com/cann/runtime/pull/2976))

###  算子编程

#### 关键特性
- 维测能力：
  - AscendC框架基础API支持NPU Check（[!1557](https://gitcode.com/cann/asc-devkit/pull/1557) [!1467](https://gitcode.com/cann/asc-devkit/pull/1467)），增强算子运行时校验能力。
  - SIMD VF内支持printf和reg dump打印（[!1605](https://gitcode.com/cann/asc-devkit/pull/1605)），提供调试打印和寄存器数据dump能力。
  - Ascend 950PR/Ascend 950DT支持L1 Tensor数据的DumpTensor（[!2175](https://gitcode.com/cann/asc-devkit/pull/2175)），扩展L1层数据调试支持。
  - 新增optype_collector工具，支持检查optype重名（[!285](https://gitcode.com/cann/asc-tools/pull/285)）。
- 编译工程
  - 编译工程CMakeModule支持CMAKE_\<LANG\>编译选项（[!2055](https://gitcode.com/cann/asc-devkit/pull/2055)）；
- 基础API
  - 支持设置ctrl寄存器的饱和溢出管理（[!2077](https://gitcode.com/cann/asc-devkit/pull/2077)）。
- SIMT编程
  - 新增ld/st接口（[!2058](https://gitcode.com/cann/asc-devkit/pull/2058)）和AddrSpace类接口（[!1597](https://gitcode.com/cann/asc-devkit/pull/1597)），丰富SIMT内存访问编程能力。

#### 样例更新
- SIMD样例：
  - 新增最佳实践样例：matmul+gelu融合、datacopy优化、bank冲突优化、group_matmul量化组矩阵乘、simt&simd高性能编程（[!1814](https://gitcode.com/cann/asc-devkit/pull/1814) [!2137](https://gitcode.com/cann/asc-devkit/pull/2137) [!2141](https://gitcode.com/cann/asc-devkit/pull/2141) [!2166](https://gitcode.com/cann/asc-devkit/pull/2166) [!2363](https://gitcode.com/cann/asc-devkit/pull/2363)）。
  - 新增Ascend 950PR/Ascend 950DT新特性样例及兼容性样例整改：loopmode数据搬运、interleave矢量计算、datacopy_gm2l1、loadmx（Load2DMX）、mmad_mx、data_copy_pad等（[!2336](https://gitcode.com/cann/asc-devkit/pull/2336) [!1899](https://gitcode.com/cann/asc-devkit/pull/1899) [!2124](https://gitcode.com/cann/asc-devkit/pull/2124)）。
  - 新增RegBase基础样例：基础算术、数据类型转换、归约、比较、索引等样例（[!1459](https://gitcode.com/cann/asc-devkit/pull/1459) [!1575](https://gitcode.com/cann/asc-devkit/pull/1575) [!2024](https://gitcode.com/cann/asc-devkit/pull/2024)）。
  - 新增SIMD VF print样例和dump样例（[!2558](https://gitcode.com/cann/asc-devkit/pull/2558)）。
  - 新增Tensor API入门及最佳实践样例：Matmul入门、数据搬入搬出、搬出随路量化、MX FP4最佳实践（[!2553](https://gitcode.com/cann/asc-devkit/pull/2553)）。
- SIMT样例：
  - 新增SIMT优化特性样例：DCache访问优化样例（[!2453](https://gitcode.com/cann/asc-devkit/pull/2453)）、基于transpose的仿存合并和bank冲突样例（[!1753](https://gitcode.com/cann/asc-devkit/pull/1753)）、最佳实践样例：通过类型对齐提升搬运效率（[!2297](https://gitcode.com/cann/asc-devkit/pull/2297)）。
  - 新增SIMT功能特性样例：pytorch注册自定义算子（[!2769](https://gitcode.com/cann/asc-devkit/pull/2769)）、编译相关样例（动态、静态、分离编译等）（[!2356](https://gitcode.com/cann/asc-devkit/pull/2356)）、profiling样例（[!1989](https://gitcode.com/cann/asc-devkit/pull/1989)）、内存屏障特性样例（[!1923](https://gitcode.com/cann/asc-devkit/pull/1923)）、Warp类特性样例（[!2876](https://gitcode.com/cann/asc-devkit/pull/2876)）、simulator样例（[!2692](https://gitcode.com/cann/asc-devkit/pull/2692)）、kernel log样例（[!2131](https://gitcode.com/cann/asc-devkit/pull/2131)）。

#### 资料文档
- 新增矩阵计算概述和计算分形介绍的文档（[!2533](https://gitcode.com/cann/asc-devkit/pull/2533)）。
- 优化矢量计算API文档，补充指令约束等（[!2676](https://gitcode.com/cann/asc-devkit/pull/2676)）。
- 增加SIMD与SIMT混合编程性能优化概述（[!2736](https://gitcode.com/cann/asc-devkit/pull/2736)）。
- 搭建VitePress文档站点，提供AscendC资料预览功能（[!2547](https://gitcode.com/cann/asc-devkit/pull/2547)）。

### PTO虚拟指令集

基础Vector&Cube指令：
  - 支持Vector类指令的高精度版本（[!896](https://gitcode.com/cann/pto-isa/pull/896), [!782](https://gitcode.com/cann/pto-isa/pull/782), [!815](https://gitcode.com/cann/pto-isa/pull/815), [!717](https://gitcode.com/cann/pto-isa/pull/717), [!648](https://gitcode.com/cann/pto-isa/pull/648), [!695](https://gitcode.com/cann/pto-isa/pull/695)）。
  - 新增transdata场景支持（[!950](https://gitcode.com/cann/pto-isa/pull/950), [!977](https://gitcode.com/cann/pto-isa/pull/977)）。
  - TSTORE、TLOAD支持卷积3D（[!904](https://gitcode.com/cann/pto-isa/pull/904), [!912](https://gitcode.com/cann/pto-isa/pull/912)）。
  - 新增MGATHER/MSCATTER指令（[!935](https://gitcode.com/cann/pto-isa/pull/935), [!1136](https://gitcode.com/cann/pto-isa/pull/1136), [!309](https://gitcode.com/cann/pto-isa/pull/309), [!889](https://gitcode.com/cann/pto-isa/pull/889)）。
  - Reduce类指令支持返回值及对应索引（[!1124](https://gitcode.com/cann/pto-isa/pull/1124), [!928](https://gitcode.com/cann/pto-isa/pull/928)）。
  - TQUANT支持MXFP8/MXFP4量化（[!1187](https://gitcode.com/cann/pto-isa/pull/1187), [!1143](https://gitcode.com/cann/pto-isa/pull/1143)）。
  - 合轴类指令支持类型增强，TMOV/TEXTRACT/TINSERT支持Vec到Vec（[!1196](https://gitcode.com/cann/pto-isa/pull/1196)）。

通信类指令：
  - 新增A5 CCU异步通信类指令TGATHER、TBROADCAST、TSCATTER、TREDUCE（[!915](https://gitcode.com/cann/pto-isa/pull/915)）。
  - 支持全核同步指令SYNCALL（[!907](https://gitcode.com/cann/pto-isa/pull/907)）。
  - 新增异步prefetch指令（[!116](https://gitcode.com/cann/pto-isa/pull/116)）。
  - TPUT_ASYNC、TGET_ASYNC增加A5基于URMA的异步通信能力（[!991](https://gitcode.com/cann/pto-isa/pull/991)）。

CostModel仿真：
  - 新增A2A3算子级Costmodel，支持输出算子性能、Pipeline时间、泳道图等信息（[!1004](https://gitcode.com/cann/pto-isa/pull/1004)）。
  - 接入CCE Mock方案，支持A2A3已有指令性能预测（[!772](https://gitcode.com/cann/pto-isa/pull/772)）。

CPU-SIM：随NPU同步新增CPU仿真指令。

## 删除和废弃特性

### 运行时
- include/driver目录头文件已迁移到pkg_inc/driver目录，include/driver目录将在2027年06月30日下线，请尽快切换至pkg_inc/driver目录。

### aclblas与aclop接口编程
- 自Ascend 950产品开始，aclblas和aclop接口不推荐使用，后续版本将逐步废弃，建议迁移至对应的aclnn算子接口。

### 算子库

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

### 模型压缩工具

模型压缩工具以下特性在CANN 9.0.0标记为废弃，在当前版本已经删除。
- 非均匀量化。
- 自动混合精度。
- 近似校准。
- int4量化感知训练。
- amct_mindspore所有特性。

## 已知问题

问题：算子aclnnMatmulCompressDequant的输入参数deqScale的值为inf/-inf时，其精度详情中显示有inf或nan
【引入版本】CANN 8.5.0
【缺陷影响】测试特殊构造用例触发，非新算子引入，且实际量化场景下不会有deqScale为-inf和inf场景，当前版本影响可控
【规避方案】实际量化场景下不会有deqScale为-inf和inf场景

## 已修复问题

以下问题在9.1.0版本修复：

- 修复了QuantBatchMatmulV3算子在Atlas推理系列产品上，编译时指定AUTO_SYNC=false导致算子读写冲突的问题。
- 针对Atlas A2系列产品和Atlas A3系列产品，修复了MatmulReduceScatterV2算子在M小于512场景下，flag位清零过快导致其他卡检测不到，最终超时的问题。
- 修复了Atlas A2系列产品的大EP场景下，D节点注入片上内存多bit故障，无法进入快速恢复流程的问题。
- 修复了4k卡训练任务在500+step后，随机step位置概率性出现的通信超时问题。
- 修复了PD分离场景，decode频繁任务中断重启导致的refill积压问题。
- 修复了开源仓用户自定义算子和内置算子IR原型重名不生效的问题。
- 修复了aclnnAddmv算子压测偶现coredump的问题。
- 修复了万卡任务拉起时异常报错的问题。
- 修复了aclgraph场景特定shape下，MatMulV3性能比MatMulV2差的问题。
- 修复了fused_quant_mat_mul场景存在的精度问题。
- 修复了BatchMatmulV2在特定bias场景下存在的精度问题。
- 修复了FAG算子短序列GQA、NoMask场景存在的精度问题。

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
- 新增Tensor API参考文档。

#### 通信算子开发

- 新增“编程模型与概念 > CCU编程模型与概念”章节。
- 新增“通信算子开发 > CCU算子开发”章节。
- 通信算子开发API新增以下接口。
  - 控制面接口 > CCU Kernel生命周期与内存Token管理。
  - 数据面接口 > CCU接口。

#### 图开发

新增以下章节：

- 自定义Pass开发 > 使用自定义Pass修改Graph > 基于Pattern匹配实现Pass（Python）。
- 编程指南 > SuperKernel融合范围标定。
- 自定义算子入图 > 自定义算子入图。

### API参考

#### GE图引擎 API

- 接口参考 > Python语言接口 > pyatc接口：新增Python场景的atc命令行工具。
- 图基础数据结构和接口 > options参数名说明 > ge.tiling_schedule_optimize：修改该参数级别，由原来global session级修改为all所有级别。

### 算子库

#### ops-cv

新增算子多平台迁移指南文档，指导开发者将算子从Atlas A2 系列产品迁移至Ascend 950PR/Ascend 950DT 系列产品。

### 通信库

#### HCCL集合通信库

相关参考 > 通信算子支持度清单：新增“Ascend 950PR/Ascend 950 DT”支持度清单。

### 开发工具

#### ATC离线模型编译工具

参数说明--framework：补充说明Caffe框架在当前形态已不再演进，转模型不保证可用性的说明。

#### AMCT模型压缩工具

新增“基于LLM的量化”章节。

## 漏洞修补列表

版本开源及第三方软件漏洞修复情况详见[漏洞修补列表](https://www.hiascend.com/document/detail/zh/CANNCommunityEdition/910/maintenref/refdoc/refer002.html)。
