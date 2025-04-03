# 全层次视觉目标粒度的统一指代表达分割方法研究

发布时间：2025年04月02日

`其他` `计算机视觉` `图像分割`

> Towards Unified Referring Expression Segmentation Across Omni-Level Visual Target Granularities

# 摘要

> 指代表达分割（RES）的目标是分割出与描述性语言表达相匹配的目标实体掩膜。虽然传统 RES 方法主要集中在对象级定位上，但现实场景需要一个更灵活的框架，能够处理多粒度的目标，包括多对象、单对象或部件级的引用。由于用户描述目标的方式多样且细微，这带来了巨大挑战。然而，现有的数据集和模型主要专注于设计对象级目标定位的专用模型，缺乏多粒度 RES 所需的数据资源和统一框架。本文朝着视觉粒度统一的 RES 任务迈出了重要一步。为克服数据稀缺的限制，我们引入了一种新的多粒度指代表达分割（MRES）任务，并发布了 RefCOCOm 基准数据集，其中包括部件级标注以促进更细粒度的视觉理解。此外，我们创建了 MRES-32M，这是目前最大的视觉定位数据集，包含 100 万张图像上的 3220 万个掩膜和描述，专门用于部件级视觉语言定位。为解决多粒度 RES 的挑战，我们提出了 UniRES++，这是一个统一的多模态大型语言模型，整合了对象级和部件级 RES 任务。UniRES++ 针对细粒度视觉特征探索进行了专门设计。通过联合模型架构和参数，UniRES++ 在多个基准测试中实现了最先进的性能，包括用于 MRES 的 RefCOCOm、用于通用 RES 的 gRefCOCO，以及用于经典 RES 的 RefCOCO、RefCOCO+ 和 RefCOCOg。为了促进未来对多粒度视觉定位的研究，我们的 RefCOCOm 基准数据集、MRES-32M 数据集和模型 UniRES++ 将在 https://github.com/Rubics-Xuan/MRES 上公开发布。

> Referring expression segmentation (RES) aims at segmenting the entities' masks that match the descriptive language expression. While traditional RES methods primarily address object-level grounding, real-world scenarios demand a more versatile framework that can handle multiple levels of target granularity, such as multi-object, single object or part-level references. This introduces great challenges due to the diverse and nuanced ways users describe targets. However, existing datasets and models mainly focus on designing grounding specialists for object-level target localization, lacking the necessary data resources and unified frameworks for the more practical multi-grained RES. In this paper, we take a step further towards visual granularity unified RES task. To overcome the limitation of data scarcity, we introduce a new multi-granularity referring expression segmentation (MRES) task, alongside the RefCOCOm benchmark, which includes part-level annotations for advancing finer-grained visual understanding. In addition, we create MRES-32M, the largest visual grounding dataset, comprising over 32.2M masks and captions across 1M images, specifically designed for part-level vision-language grounding. To tackle the challenges of multi-granularity RES, we propose UniRES++, a unified multimodal large language model that integrates object-level and part-level RES tasks. UniRES++ incorporates targeted designs for fine-grained visual feature exploration. With the joint model architecture and parameters, UniRES++ achieves state-of-the-art performance across multiple benchmarks, including RefCOCOm for MRES, gRefCOCO for generalized RES, and RefCOCO, RefCOCO+, RefCOCOg for classic RES. To foster future research into multi-grained visual grounding, our RefCOCOm benchmark, MRES-32M dataset and model UniRES++ will be publicly available at https://github.com/Rubics-Xuan/MRES.

[Arxiv](https://arxiv.org/abs/2504.01954)