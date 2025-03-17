# 稀有节肢动物分类推断：融合密集图像描述与RAG实现可解释分类

发布时间：2025年03月13日

`RAG` `生物学` `生物多样性保护`

> Taxonomic Reasoning for Rare Arthropods: Combining Dense Image Captioning and RAG for Interpretable Classification

# 摘要

> 面对气候变化的严峻挑战和节肢动物生物多样性锐减的现状，基于生物图像的自动分类已成为研究焦点。然而，传统的AI方法，如基于CNN或ViTs的深度学习模型，在处理长尾类别和推理预测结果方面存在局限。我们创新性地结合图像描述生成、检索增强生成（RAG）与大型语言模型（LLMs），为生物多样性监测提供了新的解决方案，尤其在识别稀有和未知节肢动物物种方面展现出巨大潜力。

简单视觉语言模型（VLM）虽在常见物种分类上表现优异，但RAG模型通过将显式的分类特征描述与外部生物多样性文本数据匹配，成功实现了对更稀有物种的分类。相较于简单的LLMs，RAG模型在减少过度自信和提升准确性方面表现突出，尤其是在科和属等复杂分类层级上，展现了其在捕捉 taxonomy 细微差别方面的潜力。我们的研究结果表明，现代视觉语言AI技术在生物多样性保护中具有广阔前景，强调了高质量数据整理和与公民科学平台合作的重要性，这将有助于提升物种识别能力、完善未知物种表征，并最终为制定有效的保护策略提供科学依据。

> In the context of pressing climate change challenges and the significant biodiversity loss among arthropods, automated taxonomic classification from organismal images is a subject of intense research. However, traditional AI pipelines based on deep neural visual architectures such as CNNs or ViTs face limitations such as degraded performance on the long-tail of classes and the inability to reason about their predictions. We integrate image captioning and retrieval-augmented generation (RAG) with large language models (LLMs) to enhance biodiversity monitoring, showing particular promise for characterizing rare and unknown arthropod species. While a naive Vision-Language Model (VLM) excels in classifying images of common species, the RAG model enables classification of rarer taxa by matching explicit textual descriptions of taxonomic features to contextual biodiversity text data from external sources. The RAG model shows promise in reducing overconfidence and enhancing accuracy relative to naive LLMs, suggesting its viability in capturing the nuances of taxonomic hierarchy, particularly at the challenging family and genus levels. Our findings highlight the potential for modern vision-language AI pipelines to support biodiversity conservation initiatives, emphasizing the role of comprehensive data curation and collaboration with citizen science platforms to improve species identification, unknown species characterization and ultimately inform conservation strategies.

[Arxiv](https://arxiv.org/abs/2503.10886)