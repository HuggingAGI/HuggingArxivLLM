# # 大型语言模型用于生物学中零-shot因果结构的推理
大型语言模型能够用于生物学中零-shot因果结构的推理，展现出强大的上下文推理能力。

发布时间：2025年03月06日

`LLM应用

摘要主要探讨了大型语言模型在生物领域的因果推理应用，通过评估模型在真实数据中的表现，展示了其在科学发现中的潜力，属于LLM的实际应用。` `因果学习`

> Large Language Models for Zero-shot Inference of Causal Structures in Biology

# 摘要

> 基因、蛋白质等生物实体通过因果分子网络相互作用。这些网络中的因果关系由复杂多样的机制介导，涉及潜在变量，且往往与特定细胞环境相关。在实践中，表征这些网络仍具挑战性。我们提出了一种全新框架，用于评估大型语言模型（LLMs）在生物领域进行零-shot因果推理的能力。我们利用真实世界干预数据，系统性地评估从LLM获取的因果主张，涵盖了一百多个变量和数千个因果假设。此外，我们探讨了多种提示策略和检索增强方法，包括大规模且可能相互冲突的科学文献集合。研究结果显示，通过定制化的增强和提示，即使是相对较小的LLMs也能捕捉到生物系统因果结构中的重要特征。这表明LLMs有望成为生物发现中的协调工具，通过帮助提炼当前知识，使其更易于后续分析。我们评估LLMs与实验数据相结合的方法，对于因果学习、LLMs和科学发现交叉领域的一系列问题具有广泛的相关性。

> Genes, proteins and other biological entities influence one another via causal molecular networks. Causal relationships in such networks are mediated by complex and diverse mechanisms, through latent variables, and are often specific to cellular context. It remains challenging to characterise such networks in practice. Here, we present a novel framework to evaluate large language models (LLMs) for zero-shot inference of causal relationships in biology. In particular, we systematically evaluate causal claims obtained from an LLM using real-world interventional data. This is done over one hundred variables and thousands of causal hypotheses. Furthermore, we consider several prompting and retrieval-augmentation strategies, including large, and potentially conflicting, collections of scientific articles. Our results show that with tailored augmentation and prompting, even relatively small LLMs can capture meaningful aspects of causal structure in biological systems. This supports the notion that LLMs could act as orchestration tools in biological discovery, by helping to distil current knowledge in ways amenable to downstream analysis. Our approach to assessing LLMs with respect to experimental data is relevant for a broad range of problems at the intersection of causal learning, LLMs and scientific discovery.

[Arxiv](https://arxiv.org/abs/2503.04347)