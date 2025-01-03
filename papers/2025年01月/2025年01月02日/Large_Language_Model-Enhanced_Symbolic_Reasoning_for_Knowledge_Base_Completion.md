# 基于大型语言模型的符号推理助力知识库补全

发布时间：2025年01月02日

`LLM应用

理由：这篇论文主要讨论了如何将大型语言模型（LLMs）与基于规则的推理相结合，以提升知识库补全（KBC）的灵活性和可靠性。论文提出了一个由子图提取器、LLM提议者和规则推理器组成的新框架，利用LLMs生成多样且有意义的规则，并结合基于规则的推理以提高可靠性。这种方法属于LLM在实际应用中的使用，因此归类为LLM应用。` `知识库` `推理系统`

> Large Language Model-Enhanced Symbolic Reasoning for Knowledge Base Completion

# 摘要

> 将大型语言模型（LLMs）与基于规则的推理相结合，为提升知识库补全（KBC）的灵活性和可靠性提供了强有力的解决方案。传统基于规则的KBC方法虽具备可验证的推理能力，但灵活性不足；而LLMs虽拥有强大的语义理解能力，却容易产生幻觉。为了融合LLMs的理解能力与基于规则方法的逻辑严谨性，我们提出了一个由子图提取器、LLM提议者和规则推理器组成的新框架。子图提取器首先从知识库中抽取子图，随后LLM利用这些子图生成多样且有意义的规则，以辅助推断缺失事实。为避免LLMs生成中的幻觉问题，这些规则会由规则推理器进一步精炼，筛选出知识库中最具价值的规则用于知识库补全。我们的方法具有两大优势：一是利用LLMs提升规则的丰富性和多样性，二是结合基于规则的推理以提高可靠性。该方法在多个知识库数据集上表现优异，充分证明了所提出框架的鲁棒性和通用性。

> Integrating large language models (LLMs) with rule-based reasoning offers a powerful solution for improving the flexibility and reliability of Knowledge Base Completion (KBC). Traditional rule-based KBC methods offer verifiable reasoning yet lack flexibility, while LLMs provide strong semantic understanding yet suffer from hallucinations. With the aim of combining LLMs' understanding capability with the logical and rigor of rule-based approaches, we propose a novel framework consisting of a Subgraph Extractor, an LLM Proposer, and a Rule Reasoner. The Subgraph Extractor first samples subgraphs from the KB. Then, the LLM uses these subgraphs to propose diverse and meaningful rules that are helpful for inferring missing facts. To effectively avoid hallucination in LLMs' generations, these proposed rules are further refined by a Rule Reasoner to pinpoint the most significant rules in the KB for Knowledge Base Completion. Our approach offers several key benefits: the utilization of LLMs to enhance the richness and diversity of the proposed rules and the integration with rule-based reasoning to improve reliability. Our method also demonstrates strong performance across diverse KB datasets, highlighting the robustness and generalizability of the proposed framework.

[Arxiv](https://arxiv.org/abs/2501.01246)