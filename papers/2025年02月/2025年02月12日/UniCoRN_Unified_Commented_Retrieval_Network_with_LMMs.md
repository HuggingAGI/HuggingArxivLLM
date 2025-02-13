# UniCoRN：统一评论检索网络，基于语言模型的融合方法

发布时间：2025年02月12日

`RAG` `多模态检索` `生成式语言模型`

> UniCoRN: Unified Commented Retrieval Network with LMMs

# 摘要

> 传统多模态检索方法在处理复杂组合查询时存在局限性，难以同时推理查询和检索实体的视觉内容。大语言模型（LMMs）虽能回答更复杂的视觉问题，但缺乏检索相关实体支持答案的能力。为突破这些限制，我们提出了UniCoRN——一种结合了组合式多模态检索与生成式语言方法的统一注释检索网络，超越了传统的检索增强生成（RAG）。通过引入实体适配模块，UniCoRN能够将检索到的多模态实体重新注入LMM，使其在生成答案和注释时能够关注这些实体。保持基础LMM冻结的同时，UniCoRN不仅保留了原有能力，还实现了检索与文本生成的无缝结合。为验证这些新能力，我们提出了带评论的检索任务（CoR）及其对应数据集，旨在准确回答问题的同时生成详细注释。实验结果显示，与最先进方法相比，UniCoRN在组合式多模态检索中召回率提升了+4.5%，在CoR任务中评论的METEOR和BEM指标分别提升了+14.9%和+18.4%。

> Multimodal retrieval methods have limitations in handling complex, compositional queries that require reasoning about the visual content of both the query and the retrieved entities. On the other hand, Large Multimodal Models (LMMs) can answer with language to more complex visual questions, but without the inherent ability to retrieve relevant entities to support their answers. We aim to address these limitations with UniCoRN, a Unified Commented Retrieval Network that combines the strengths of composed multimodal retrieval methods and generative language approaches, going beyond Retrieval-Augmented Generation (RAG). We introduce an entity adapter module to inject the retrieved multimodal entities back into the LMM, so it can attend to them while generating answers and comments. By keeping the base LMM frozen, UniCoRN preserves its original capabilities while being able to perform both retrieval and text generation tasks under a single integrated framework. To assess these new abilities, we introduce the Commented Retrieval task (CoR) and a corresponding dataset, with the goal of retrieving an image that accurately answers a given question and generate an additional textual response that provides further clarification and details about the visual information. We demonstrate the effectiveness of UniCoRN on several datasets showing improvements of +4.5% recall over the state of the art for composed multimodal retrieval and of +14.9% METEOR / +18.4% BEM over RAG for commenting in CoR.

[Arxiv](https://arxiv.org/abs/2502.08254)