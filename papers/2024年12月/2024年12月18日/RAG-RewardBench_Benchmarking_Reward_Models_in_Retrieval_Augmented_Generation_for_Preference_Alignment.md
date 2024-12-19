# RAG-RewardBench：针对检索增强生成中的奖励模型开展基准测试，以达成偏好对齐

发布时间：2024年12月18日

`RAG` `语言模型` `检索增强`

> RAG-RewardBench: Benchmarking Reward Models in Retrieval Augmented Generation for Preference Alignment

# 摘要

> 尽管现有的检索增强语言模型（RALMs）在提供可信响应及基于可靠来源方面成果显著，但它们往往忽视了与人类偏好的有效对齐。在对齐过程中，奖励模型（RMs）充当着人类价值观的关键代理，以引导优化。然而，在RALMs中如何评估和选择可靠的RM用于偏好对齐，尚不明确。为此，我们推出了RAG-RewardBench，这是评估RAG设置中RMs的首个基准。首先，我们设计了四个关键且富有挑战性的RAG特定场景来评估RMs，涵盖多跳推理、细粒度引用、适当弃权和冲突鲁棒性。接着，我们纳入了18个RAG子集、6个检索器和24个RALMs，以增添数据源的多样性。最后，我们采用LLM作为裁判的方式来提升偏好标注的效率和效果，其与人类标注具有很强的相关性。基于RAG-RewardBench，我们对45个RMs展开了全面评估，揭示了它们在RAG场景中的局限性。此外，我们还发现现有的经过训练的RALMs在偏好对齐方面几乎毫无进展，这凸显了转向偏好对齐训练的必要性。我们在https://huggingface.co/datasets/jinzhuoran/RAG-RewardBench/公开了基准和代码，以供后续工作使用。

> Despite the significant progress made by existing retrieval augmented language models (RALMs) in providing trustworthy responses and grounding in reliable sources, they often overlook effective alignment with human preferences. In the alignment process, reward models (RMs) act as a crucial proxy for human values to guide optimization. However, it remains unclear how to evaluate and select a reliable RM for preference alignment in RALMs. To this end, we propose RAG-RewardBench, the first benchmark for evaluating RMs in RAG settings. First, we design four crucial and challenging RAG-specific scenarios to assess RMs, including multi-hop reasoning, fine-grained citation, appropriate abstain, and conflict robustness. Then, we incorporate 18 RAG subsets, six retrievers, and 24 RALMs to increase the diversity of data sources. Finally, we adopt an LLM-as-a-judge approach to improve preference annotation efficiency and effectiveness, exhibiting a strong correlation with human annotations. Based on the RAG-RewardBench, we conduct a comprehensive evaluation of 45 RMs and uncover their limitations in RAG scenarios. Additionally, we also reveal that existing trained RALMs show almost no improvement in preference alignment, highlighting the need for a shift towards preference-aligned training.We release our benchmark and code publicly at https://huggingface.co/datasets/jinzhuoran/RAG-RewardBench/ for future work.

[Arxiv](https://arxiv.org/abs/2412.13746)