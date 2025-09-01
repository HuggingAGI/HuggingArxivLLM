# 基于检索增强生成的文档视觉问答模型增强

发布时间：2025年08月28日

`RAG` `基础理论`

> Enhancing Document VQA Models via Retrieval-Augmented Generation

# 摘要

> 文档视觉问答（Document VQA）需应对长达数十页的文档，但主流系统仍采用拼接所有页面或依赖超大型视觉语言模型的方案，两者均存在内存消耗大的问题。检索增强生成（RAG）则提供了一种更优解：先检索精简的相关片段，再基于所选证据生成答案。本文通过两种检索变体（基于OCR文本的检索和无需OCR的纯视觉检索），在多个模型及基准测试上系统评估了RAG在Document VQA中的应用效果。在多页数据集MP-DocVQA、DUDE和InfographicVQA上的测试显示，文本检索变体相比“全页拼接”基线ANLS提升最高达22.5，而纯视觉检索无需文本提取即可实现5.0的ANLS提升。消融实验表明，检索与重排序组件是性能提升的核心，而近期多项研究提出的布局引导分块策略（旨在利用页面结构）在这些数据集上却收效甚微。实验结果证实，精准的证据筛选能在不同模型规模及多页基准测试中稳定提升准确率，充分体现了其在实际文档视觉问答场景中的应用价值。

> Document Visual Question Answering (Document VQA) must cope with documents that span dozens of pages, yet leading systems still concatenate every page or rely on very large vision-language models, both of which are memory-hungry. Retrieval-Augmented Generation (RAG) offers an attractive alternative, first retrieving a concise set of relevant segments before generating answers from this selected evidence. In this paper, we systematically evaluate the impact of incorporating RAG into Document VQA through different retrieval variants - text-based retrieval using OCR tokens and purely visual retrieval without OCR - across multiple models and benchmarks. Evaluated on the multi-page datasets MP-DocVQA, DUDE, and InfographicVQA, the text-centric variant improves the "concatenate-all-pages" baseline by up to +22.5 ANLS, while the visual variant achieves +5.0 ANLS improvement without requiring any text extraction. An ablation confirms that retrieval and reranking components drive most of the gain, whereas the layout-guided chunking strategy - proposed in several recent works to leverage page structure - fails to help on these datasets. Our experiments demonstrate that careful evidence selection consistently boosts accuracy across multiple model sizes and multi-page benchmarks, underscoring its practical value for real-world Document VQA.

[Arxiv](https://arxiv.org/abs/2508.18984)