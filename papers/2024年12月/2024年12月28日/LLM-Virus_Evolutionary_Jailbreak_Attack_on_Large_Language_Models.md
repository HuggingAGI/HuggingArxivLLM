# LLM-Virus: 大型语言模型的进化性越狱攻击

发布时间：2024年12月28日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）在安全对齐方面的局限性，特别是针对越狱攻击的研究。论文提出了一种基于进化算法的越狱攻击方法（LLM-Virus），并对其进行了实验验证。这些内容主要涉及LLM的理论研究，特别是关于其安全性和对抗性攻击的理论分析，因此归类为“LLM理论”。` `人工智能` `网络安全`

> LLM-Virus: Evolutionary Jailbreak Attack on Large Language Models

# 摘要

> 尽管安全对齐的大型语言模型（LLMs）已成为解决复杂现实问题的多智能体框架等强大系统的基石，但它们仍易受越狱攻击等对抗性查询的威胁，这些攻击旨在诱导有害内容。研究攻击方法有助于我们更好地理解LLM的局限性，并在帮助性与安全性之间找到平衡。然而，现有越狱攻击多依赖不透明的优化技术（如令牌级梯度下降）和启发式搜索方法（如LLM精炼），在透明度、可转移性和计算成本方面存在不足。为此，我们借鉴生物病毒的进化和感染过程，提出了基于进化算法的越狱攻击方法——LLM-Virus，即进化越狱。LLM-Virus将越狱攻击视为进化和迁移学习问题，利用LLMs作为启发式进化算子，确保高攻击效率、可转移性和低时间成本。实验结果表明，LLM-Virus在多个安全基准上表现优异，甚至超越现有攻击方法。

> While safety-aligned large language models (LLMs) are increasingly used as the cornerstone for powerful systems such as multi-agent frameworks to solve complex real-world problems, they still suffer from potential adversarial queries, such as jailbreak attacks, which attempt to induce harmful content. Researching attack methods allows us to better understand the limitations of LLM and make trade-offs between helpfulness and safety. However, existing jailbreak attacks are primarily based on opaque optimization techniques (e.g. token-level gradient descent) and heuristic search methods like LLM refinement, which fall short in terms of transparency, transferability, and computational cost. In light of these limitations, we draw inspiration from the evolution and infection processes of biological viruses and propose LLM-Virus, a jailbreak attack method based on evolutionary algorithm, termed evolutionary jailbreak. LLM-Virus treats jailbreak attacks as both an evolutionary and transfer learning problem, utilizing LLMs as heuristic evolutionary operators to ensure high attack efficiency, transferability, and low time cost. Our experimental results on multiple safety benchmarks show that LLM-Virus achieves competitive or even superior performance compared to existing attack methods.

[Arxiv](https://arxiv.org/abs/2501.00055)