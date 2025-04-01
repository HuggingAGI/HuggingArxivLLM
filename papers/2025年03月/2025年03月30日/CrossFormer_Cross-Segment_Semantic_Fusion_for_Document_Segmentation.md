# 跨段语义融合器：文档分割中的跨段语义融合研究

发布时间：2025年03月30日

`LLM应用` `生成模型`

> CrossFormer: Cross-Segment Semantic Fusion for Document Segmentation

# 摘要

> 文本语义分割旨在根据主题、上下文信息和文档结构，将文档划分为多个具有连贯语义的段落。传统方法通常通过将文档预处理为段落来应对输入长度限制，但这一过程导致了段落间关键语义信息的丢失。为此，我们提出了CrossFormer——一种基于Transformer的创新模型，配备跨段落融合模块，能够动态建模文档段落间的潜在语义依赖关系，从而显著提升分割精度。此外，CrossFormer可替代基于规则的分块方法，在检索增强生成（RAG）系统中生成语义连贯性更强的分块，显著提升系统效果。全面的评估验证了CrossFormer在公共文本语义分割数据集上的 state-of-the-art 性能，并在 RAG 基准测试中取得了显著提升。

> Text semantic segmentation involves partitioning a document into multiple paragraphs with continuous semantics based on the subject matter, contextual information, and document structure. Traditional approaches have typically relied on preprocessing documents into segments to address input length constraints, resulting in the loss of critical semantic information across segments. To address this, we present CrossFormer, a transformer-based model featuring a novel cross-segment fusion module that dynamically models latent semantic dependencies across document segments, substantially elevating segmentation accuracy. Additionally, CrossFormer can replace rule-based chunk methods within the Retrieval-Augmented Generation (RAG) system, producing more semantically coherent chunks that enhance its efficacy. Comprehensive evaluations confirm CrossFormer's state-of-the-art performance on public text semantic segmentation datasets, alongside considerable gains on RAG benchmarks.

[Arxiv](https://arxiv.org/abs/2503.23671)