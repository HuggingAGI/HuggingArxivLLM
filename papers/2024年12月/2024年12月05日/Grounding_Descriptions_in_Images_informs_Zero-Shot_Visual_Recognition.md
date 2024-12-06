# 图像中的描述扎根为零样本视觉识别提供了信息

发布时间：2024年12月05日

`LLM应用` `图像分类` `视觉识别`

> Grounding Descriptions in Images informs Zero-Shot Visual Recognition

# 摘要

> 像 CLIP 这样的视觉语言模型（VLMs）因其具备在开放词汇概念上进行零样本视觉识别的能力而备受青睐。这是通过选取文本表述与查询图像相似度最高的对象类别来达成的。尽管在某些领域表现出色，但此方法在识别细粒度实体以及推广到训练分布未涵盖的未见概念时遭遇困境。近期的工作尝试在测试时整合类别描述来应对这些挑战，不过改进程度有限。我们把这些有限的成效归咎于图像和描述表示之间存在根本的不匹配，这源自 CLIP 的预训练结构。在本文中，我们提出了 GRAIN，一种新的预训练策略，旨在同时在精细和粗略层面上对齐表示。我们的方法学会将文本描述共同定位在图像区域中，并使总体标题与全局图像表示相匹配。为推动这种预训练，我们借助冻结的多模态大型语言模型（MLLMs）来获取大规模的合成标注。我们证明了在 11 个不同的图像分类数据集中，我们的模型与当前最先进的方法相比，零样本性能得到了提升。此外，我们引入了 Products-2023，这是一个新整理且手动标注、具有新颖概念的数据集，并通过在其上进行基准测试展示了我们模型识别这些概念的能力。我们的模型在其他下游任务（如检索）上取得的显著进步进一步凸显了我们方法所学习到的表示的高品质。代码可在 https://github.com/shaunak27/grain-clip 获取。

> Vision-language models (VLMs) like CLIP have been cherished for their ability to perform zero-shot visual recognition on open-vocabulary concepts. This is achieved by selecting the object category whose textual representation bears the highest similarity with the query image. While successful in some domains, this method struggles with identifying fine-grained entities as well as generalizing to unseen concepts that are not captured by the training distribution. Recent works attempt to mitigate these challenges by integrating category descriptions at test time, albeit yielding modest improvements. We attribute these limited gains to a fundamental misalignment between image and description representations, which is rooted in the pretraining structure of CLIP. In this paper, we propose GRAIN, a new pretraining strategy aimed at aligning representations at both fine and coarse levels simultaneously. Our approach learns to jointly ground textual descriptions in image regions along with aligning overarching captions with global image representations. To drive this pre-training, we leverage frozen Multimodal Large Language Models (MLLMs) to derive large-scale synthetic annotations. We demonstrate the enhanced zero-shot performance of our model compared to current state-of-the art methods across 11 diverse image classification datasets. Additionally, we introduce Products-2023, a newly curated, manually labeled dataset featuring novel concepts, and showcase our model's ability to recognize these concepts by benchmarking on it. Significant improvements achieved by our model on other downstream tasks like retrieval further highlight the superior quality of representations learned by our approach. Code available at https://github.com/shaunak27/grain-clip .

[Arxiv](https://arxiv.org/abs/2412.04429)