# 聚焦何处：利用参考查询提升视觉定位效果

发布时间：2024年12月26日

`其他

**理由：**
这篇论文主要讨论的是视觉定位（Visual Grounding）任务，即根据自然语言描述在图像中精确定位目标对象。虽然涉及自然语言处理（NLP）和计算机视觉（CV）的结合，但其核心内容并不直接涉及大型语言模型（LLM）、检索增强生成（RAG）或智能体（Agent）等主题。因此，将其分类为其他更为合适。` `计算机视觉`

> Referencing Where to Focus: Improving VisualGrounding with Referential Query

# 摘要

> # 摘要
视觉定位（Visual Grounding）旨在根据自然语言描述在图像中精确定位目标对象。近年来，基于DETR的视觉定位方法因其无需依赖预生成候选框或预定义锚框，直接预测目标坐标的特性而备受关注。然而，现有研究多聚焦于设计更强大的多模态解码器，通常通过随机初始化或语言嵌入生成可学习查询。这种简单的查询生成方式在解码初期缺乏目标相关信息，增加了模型学习难度。此外，现有方法在查询学习过程中仅利用最深层的图像特征，忽视了其他层次特征的重要性。为此，我们提出了RefFormer方法，包含一个可无缝集成到CLIP中的查询适应模块，生成参考查询为解码器提供先验上下文，以及一个任务特定的解码器。通过引入参考查询，我们有效降低了解码器的学习难度，使其更精准地聚焦于目标对象。同时，查询适应模块还能作为适配器，保留CLIP中的丰富知识，无需调整主干网络参数。大量实验表明，RefFormer在五个视觉定位基准上均优于现有最先进方法，展现了其高效性和有效性。

> Visual Grounding aims to localize the referring object in an image given a natural language expression. Recent advancements in DETR-based visual grounding methods have attracted considerable attention, as they directly predict the coordinates of the target object without relying on additional efforts, such as pre-generated proposal candidates or pre-defined anchor boxes. However, existing research primarily focuses on designing stronger multi-modal decoder, which typically generates learnable queries by random initialization or by using linguistic embeddings. This vanilla query generation approach inevitably increases the learning difficulty for the model, as it does not involve any target-related information at the beginning of decoding. Furthermore, they only use the deepest image feature during the query learning process, overlooking the importance of features from other levels. To address these issues, we propose a novel approach, called RefFormer. It consists of the query adaption module that can be seamlessly integrated into CLIP and generate the referential query to provide the prior context for decoder, along with a task-specific decoder. By incorporating the referential query into the decoder, we can effectively mitigate the learning difficulty of the decoder, and accurately concentrate on the target object. Additionally, our proposed query adaption module can also act as an adapter, preserving the rich knowledge within CLIP without the need to tune the parameters of the backbone network. Extensive experiments demonstrate the effectiveness and efficiency of our proposed method, outperforming state-of-the-art approaches on five visual grounding benchmarks.

[Arxiv](https://arxiv.org/abs/2412.19155)