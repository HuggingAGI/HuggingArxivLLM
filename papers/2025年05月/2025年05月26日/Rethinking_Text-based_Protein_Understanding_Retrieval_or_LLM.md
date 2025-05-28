# 重新审视蛋白质文本理解：检索，还是 LLM？

发布时间：2025年05月26日

`LLM应用` `生物技术` `人工智能`

> Rethinking Text-based Protein Understanding: Retrieval or LLM?

# 摘要

> 近年来，蛋白质文本模型因其在蛋白质生成和理解方面的潜力而备受关注。目前，研究者主要通过持续预训练和多模态对齐，将蛋白质相关知识整合到大型语言模型中，实现对文本描述与蛋白质序列的同步理解。通过对现有模型架构及基于文本的蛋白质理解基准的深入分析，我们发现当前基准中存在显著的数据泄露问题。此外，传统的自然语言处理指标无法准确评估模型在这一领域的性能。为解决这些问题，我们重新组织了现有数据集，并引入了一个基于生物实体的新评估框架。基于此观察，我们提出了一种增强检索的方法，该方法在蛋白质到文本生成任务中显著优于微调后的LLMs，并在无需训练的场景中展现了卓越的准确性和效率。我们的代码和数据可在https://github.com/IDEA-XL/RAPM上查看。

> In recent years, protein-text models have gained significant attention for their potential in protein generation and understanding. Current approaches focus on integrating protein-related knowledge into large language models through continued pretraining and multi-modal alignment, enabling simultaneous comprehension of textual descriptions and protein sequences. Through a thorough analysis of existing model architectures and text-based protein understanding benchmarks, we identify significant data leakage issues present in current benchmarks. Moreover, conventional metrics derived from natural language processing fail to accurately assess the model's performance in this domain. To address these limitations, we reorganize existing datasets and introduce a novel evaluation framework based on biological entities. Motivated by our observation, we propose a retrieval-enhanced method, which significantly outperforms fine-tuned LLMs for protein-to-text generation and shows accuracy and efficiency in training-free scenarios. Our code and data can be seen at https://github.com/IDEA-XL/RAPM.

[Arxiv](https://arxiv.org/abs/2505.20354)