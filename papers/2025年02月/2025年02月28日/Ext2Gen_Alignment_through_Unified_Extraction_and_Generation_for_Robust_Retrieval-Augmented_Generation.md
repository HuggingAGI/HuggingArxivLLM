# Ext2Gen：通过统一抽取与生成实现稳健的检索增强生成

发布时间：2025年02月28日

`RAG` `生成模型`

> Ext2Gen: Alignment through Unified Extraction and Generation for Robust Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）通过整合外部知识为LLMs赋能，但生成过程仍面临两大挑战：相关片段位置的不确定性及检索引发的信息过载，这些问题会导致幻觉现象。我们提出了一种新型的先抽取再生成模型Ext2Gen，该模型通过先提取与查询相关的句子，再生成答案，从而显著提升了RAG的鲁棒性。为了进一步优化该模型，我们引入了基于成对反馈学习的偏好对齐机制，确保模型在面对不同检索结果时仍能生成稳健的答案。大量实验结果表明，Ext2Gen在识别与查询相关的句子时，不仅精准度高，而且召回率也表现优异，最终生成的答案可靠性显著提升。此外，将我们的模型部署在RAG环境中进行测试，结果显示它不仅显著提升了基础LLM的性能，还与诸如查询扩展等高级检索策略实现了良好的协同效应。目前，我们正在准备将该数据集和模型开源，敬请期待。

> Retrieval-augmented generation (RAG) enhances LLMs by integrating external knowledge, but generation remains fragile due to the uncertain placement of relevant chunks and retrieval-induced information overload, leading to hallucinations. We propose Ext2Gen, a novel extract-then-generate model that enhances RAG robustness by first extracting query-relevant sentences before generating answers. To optimize this model, we employ preference alignment through pairwise feedback learning, enabling the model to generate robust answers regardless of variations in retrieval results. Extensive experiments demonstrate that Ext2Gen effectively identifies query-relevant sentences with high precision and recall, leading to highly reliable answers. Furthermore, deploying our model in a RAG environment reveals that it not only boosts the performance of the base LLM but also synergizes with advanced retrieval strategies like query expansion. The dataset and model will be released soon.

[Arxiv](https://arxiv.org/abs/2503.04789)