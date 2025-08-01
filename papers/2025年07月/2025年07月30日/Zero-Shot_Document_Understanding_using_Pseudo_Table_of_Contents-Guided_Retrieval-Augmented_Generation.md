# 基于伪目录指南的零样本文档理解与检索增强生成

发布时间：2025年07月30日

`LLM应用

论文摘要中提到，DocsRay利用多模态大型语言模型的原生能力，结合RAG技术，解决多模态文档理解的挑战。虽然提到了RAG，但论文的主要贡献在于应用这些技术来解决实际问题，因此归类为LLM应用。` `信息处理` `办公自动化`

> Zero-Shot Document Understanding using Pseudo Table of Contents-Guided Retrieval-Augmented Generation

# 摘要

> 理解复杂的多模态文档仍然充满挑战，主要由于文档结构的不一致性和训练数据的有限性。我们推出	extit{DocsRay}，一个无需训练的文档理解系统，它巧妙结合了伪目录生成与分层检索增强生成（RAG）。我们的方法充分发挥多模态大型语言模型的原生能力，无需专用模型或额外训练，即可轻松处理包含文本、图像、图表和表格等多样化元素的文档。DocsRay的框架巧妙融合了三项核心技术：(1) 语义结构模块，通过基于提示的LLM交互生成分层伪目录；(2) 零样本多模态分析，利用多模态LLM的内在能力将多样化的文档元素统一转换为以文本为中心的表示形式；(3) 高效的两阶段分层检索系统，将检索复杂度从【数学公式】降低到【数学公式】。在平均49.4页和20,971个文本标记的文档上进行评估，DocsRay将查询延迟从3.89秒减少到2.12秒，效率提升了45%。在MMLongBench-Doc基准测试中，DocsRay-Pro达到了64.7%的准确率，显著超越了之前最先进的结果。

> Understanding complex multimodal documents remains challenging due to their structural inconsistencies and limited training data availability. We introduce \textit{DocsRay}, a training-free document understanding system that integrates pseudo Table of Contents (TOC) generation with hierarchical Retrieval-Augmented Generation (RAG). Our approach leverages multimodal Large Language Models' (LLMs) native capabilities to seamlessly process documents containing diverse elements such as text, images, charts, and tables without requiring specialized models or additional training. DocsRay's framework synergistically combines three key techniques: (1) a semantic structuring module using prompt-based LLM interactions to generate a hierarchical pseudo-TOC, (2) zero-shot multimodal analysis that converts diverse document elements into unified, text-centric representations using the inherent capabilities of multimodal LLMs, and (3) an efficient two-stage hierarchical retrieval system that reduces retrieval complexity from $O(N)$ to $O(S + k_1 \cdot N_s)$. Evaluated on documents averaging 49.4 pages and 20,971 textual tokens, DocsRay reduced query latency from 3.89 to 2.12 seconds, achieving a 45% efficiency improvement. On the MMLongBench-Doc benchmark, DocsRay-Pro attains an accuracy of 64.7%, substantially surpassing previous state-of-the-art results.

[Arxiv](https://arxiv.org/abs/2507.23217)