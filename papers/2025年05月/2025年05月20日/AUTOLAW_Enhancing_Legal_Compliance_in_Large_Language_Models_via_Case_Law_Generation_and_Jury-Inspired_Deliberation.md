# # 自动法律合规增强：借助案例法生成与陪审团启发的审议流程，提升大型语言模型的法律合规性

发布时间：2025年05月20日

`LLM应用` `合规性`

> AUTOLAW: Enhancing Legal Compliance in Large Language Models via Case Law Generation and Jury-Inspired Deliberation

# 摘要

> 随着领域特定的大型语言模型 (LLMs) 在法律等领域的迅速发展，我们迫切需要能够应对地区法律差异的框架，以确保合规性和可信度。然而，现有的法律评估基准往往缺乏灵活性，难以适应多样的本地化情境，这使其在快速变化的监管环境中应用受限。为解决这一问题，我们提出了 AutoLaw——一个结合了对抗数据生成和陪审团式审议过程的新型违规检测框架，旨在提升 LLMs 的法律合规性。与传统的静态方法不同，AutoLaw 能够动态合成案例法以反映本地法规，并借助一组基于 LLM 的“陪审员”来模拟司法决策过程。陪审员根据其合成的法律专业知识进行排名和选拔，从而实现了一个能够最大限度减少偏见并提高检测准确性的审议过程。在 Law-SG、Case-SG（合法性）和 Unfair-TOS（政策）三个基准测试上的评估结果证明了 AutoLaw 的有效性：对抗数据生成增强了 LLM 的辨别能力，而陪审团投票策略则显著提升了违规检测率。我们的研究结果表明，AutoLaw 在自适应探测法律不一致性和提供可靠、情境感知判决方面具有显著优势，为在法律敏感应用中评估和提升 LLMs 提供了一个可扩展的解决方案。

> The rapid advancement of domain-specific large language models (LLMs) in fields like law necessitates frameworks that account for nuanced regional legal distinctions, which are critical for ensuring compliance and trustworthiness. Existing legal evaluation benchmarks often lack adaptability and fail to address diverse local contexts, limiting their utility in dynamically evolving regulatory landscapes. To address these gaps, we propose AutoLaw, a novel violation detection framework that combines adversarial data generation with a jury-inspired deliberation process to enhance legal compliance of LLMs. Unlike static approaches, AutoLaw dynamically synthesizes case law to reflect local regulations and employs a pool of LLM-based "jurors" to simulate judicial decision-making. Jurors are ranked and selected based on synthesized legal expertise, enabling a deliberation process that minimizes bias and improves detection accuracy. Evaluations across three benchmarks: Law-SG, Case-SG (legality), and Unfair-TOS (policy), demonstrate AutoLaw's effectiveness: adversarial data generation improves LLM discrimination, while the jury-based voting strategy significantly boosts violation detection rates. Our results highlight the framework's ability to adaptively probe legal misalignments and deliver reliable, context-aware judgments, offering a scalable solution for evaluating and enhancing LLMs in legally sensitive applications.

[Arxiv](https://arxiv.org/abs/2505.14015)