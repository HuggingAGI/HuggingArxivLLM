# # RankCoT：基于排序思维链精炼知识，提升检索增强生成能力

发布时间：2025年02月25日

`RAG` `知识精炼` `生成式AI`

> RankCoT: Refining Knowledge for Retrieval-Augmented Generation through Ranking Chain-of-Thoughts

# 摘要

> 检索增强生成（RAG）通过整合外部知识显著提升了大型语言模型（LLMs）的性能。然而，LLMs在有效利用检索文档中的知识时仍然面临挑战，常常被无关或噪声信息误导。为了解决这一问题，我们提出了RankCoT——一种基于给定查询和所有检索文档，通过引入重新排序信号生成CoT（思维链）摘要的知识精炼方法。在训练过程中，RankCoT首先提示LLM根据查询和单个文档生成CoT候选。随后，RankCoT对LLM进行微调，使其能够直接从这些候选输出中生成基于所有检索文档的最佳CoT，这一过程要求LLM在生成CoT风格摘要时过滤掉无关文档。此外，RankCoT还引入了一种自我反思机制，进一步优化CoT输出，从而生成更高质量的训练数据。我们的实验结果证明了RankCoT的有效性，其性能优于其他知识精炼模型。进一步分析表明，RankCoT能够提供更短但同样有效的精炼结果，从而帮助生成器产出更准确的回答。所有代码和数据均可在https://github.com/NEUIR/RankCoT获取。

> Retrieval-Augmented Generation (RAG) enhances the performance of Large Language Models (LLMs) by incorporating external knowledge. However, LLMs still encounter challenges in effectively utilizing the knowledge from retrieved documents, often being misled by irrelevant or noisy information. To address this issue, we introduce RankCoT, a knowledge refinement method that incorporates reranking signals in generating CoT-based summarization for knowledge refinement based on given query and all retrieval documents. During training, RankCoT prompts the LLM to generate Chain-of-Thought (CoT) candidates based on the query and individual documents. It then fine-tunes the LLM to directly reproduce the best CoT from these candidate outputs based on all retrieved documents, which requires LLM to filter out irrelevant documents during generating CoT-style summarization. Additionally, RankCoT incorporates a self-reflection mechanism that further refines the CoT outputs, resulting in higher-quality training data. Our experiments demonstrate the effectiveness of RankCoT, showing its superior performance over other knowledge refinement models. Further analysis reveals that RankCoT can provide shorter but effective refinement results, enabling the generator to produce more accurate answers. All code and data are available at https://github.com/NEUIR/RankCoT.

[Arxiv](https://arxiv.org/abs/2502.17888)