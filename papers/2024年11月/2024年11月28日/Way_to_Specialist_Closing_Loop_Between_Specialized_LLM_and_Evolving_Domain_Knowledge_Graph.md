# 通往专家的途径：构建专业大型语言模型与不断演进的领域知识图谱之间的闭环

发布时间：2024年11月28日

`LLM应用` `知识图谱` `专业领域推理`

> Way to Specialist: Closing Loop Between Specialized LLM and Evolving Domain Knowledge Graph

# 摘要

> 大型语言模型（LLMs）在众多领域展现出非凡的性能。不过，通用的 LLMs 在需要专业知识的推理任务中仍有不足。以往对专业 LLMs 的研究侧重于特定领域的训练，这需要在领域数据获取和模型参数微调上投入大量精力。为应对这些难题，本文提出了 Way-to-Specialist（WTS）框架，它将检索增强生成与知识图谱（KGs）相结合，在无专门训练的情况下提升 LLMs 的专业能力。和现有的仅利用来自通用 KGs 或静态领域 KGs 的外部知识来提示 LLMs 以增强特定领域推理的范式不同，WTS 提出了创新的“LLM$\circlearrowright$KG”范式，实现了专业 LLMs 与领域知识图谱（DKG）的双向增强。所提出的范式包含两个紧密耦合的部分：DKG 增强的 LLMs 和 LLMs 辅助的 DKG 进化。前者从 DKG 中检索与问题相关的领域知识，并以此提示 LLMs 以增强特定领域任务的推理能力；后者借助 LLMs 从处理的任务中生成新的领域知识，并用于 DKG 的进化。WTS 打通了 DKG 增强的 LLMs 与 LLMs 辅助的 DKG 进化之间的循环，使其在逐步回答和从特定领域问题中学习的过程中，不断提升领域专业化水平。我们在涵盖 5 个领域的 6 个数据集上验证了 WTS 的性能。实验结果显示，WTS 在 4 个专业领域超越了之前的 SOTA，性能最大提升了 11.3%。

> Large language models (LLMs) have demonstrated exceptional performance across a wide variety of domains. Nonetheless, generalist LLMs continue to fall short in reasoning tasks necessitating specialized knowledge. Prior investigations into specialized LLMs focused on domain-specific training, which entails substantial efforts in domain data acquisition and model parameter fine-tuning. To address these challenges, this paper proposes the Way-to-Specialist (WTS) framework, which synergizes retrieval-augmented generation with knowledge graphs (KGs) to enhance the specialized capability of LLMs in the absence of specialized training. In distinction to existing paradigms that merely utilize external knowledge from general KGs or static domain KGs to prompt LLM for enhanced domain-specific reasoning, WTS proposes an innovative "LLM$\circlearrowright$KG" paradigm, which achieves bidirectional enhancement between specialized LLM and domain knowledge graph (DKG). The proposed paradigm encompasses two closely coupled components: the DKG-Augmented LLM and the LLM-Assisted DKG Evolution. The former retrieves question-relevant domain knowledge from DKG and uses it to prompt LLM to enhance the reasoning capability for domain-specific tasks; the latter leverages LLM to generate new domain knowledge from processed tasks and use it to evolve DKG. WTS closes the loop between DKG-Augmented LLM and LLM-Assisted DKG Evolution, enabling continuous improvement in the domain specialization as it progressively answers and learns from domain-specific questions. We validate the performance of WTS on 6 datasets spanning 5 domains. The experimental results show that WTS surpasses the previous SOTA in 4 specialized domains and achieves a maximum performance improvement of 11.3%.

[Arxiv](https://arxiv.org/abs/2411.19064)