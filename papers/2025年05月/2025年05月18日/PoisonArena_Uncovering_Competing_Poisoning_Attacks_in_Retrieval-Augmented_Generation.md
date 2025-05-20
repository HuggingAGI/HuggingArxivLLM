# PoisonArena：探索检索增强生成中的对抗性中毒攻击

发布时间：2025年05月18日

`RAG` `人工智能安全`

> PoisonArena: Uncovering Competing Poisoning Attacks in Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）系统广泛应用于提升大型语言模型（LLMs）的事实准确性，但它们正日益面临中毒攻击的威胁——攻击者通过篡改内容污染检索器的语料库。尽管现有研究主要聚焦于单攻击者场景，但现实环境中往往涉及多个攻击者，他们目标冲突、互相竞争。本研究推出PoisonArena，首个系统研究和评估RAG系统中竞争性中毒攻击的基准框架。我们正式定义了多攻击者的威胁模型，攻击者利用互斥的虚假信息争夺同一查询的回答控制权。PoisonArena采用Bradley-Terry模型量化各方法在对抗环境中的竞争表现。通过在Natural Questions和MS MARCO数据集上的广泛实验，我们发现许多孤立环境下的成功攻击策略在竞争压力下失效。我们的研究揭示了传统评估指标如攻击成功率（ASR）和F1分数的局限性，并强调了在现实世界攻击鲁棒性评估中进行竞争性评估的必要性。PoisonArena为在更现实的多对手条件下基准测试和开发未来的攻击与防御策略提供了标准化框架。项目页面：https://github.com/yxf203/PoisonArena。

> Retrieval-Augmented Generation (RAG) systems, widely used to improve the factual grounding of large language models (LLMs), are increasingly vulnerable to poisoning attacks, where adversaries inject manipulated content into the retriever's corpus. While prior research has predominantly focused on single-attacker settings, real-world scenarios often involve multiple, competing attackers with conflicting objectives. In this work, we introduce PoisonArena, the first benchmark to systematically study and evaluate competing poisoning attacks in RAG. We formalize the multi-attacker threat model, where attackers vie to control the answer to the same query using mutually exclusive misinformation. PoisonArena leverages the Bradley-Terry model to quantify each method's competitive effectiveness in such adversarial environments. Through extensive experiments on the Natural Questions and MS MARCO datasets, we demonstrate that many attack strategies successful in isolation fail under competitive pressure. Our findings highlight the limitations of conventional evaluation metrics like Attack Success Rate (ASR) and F1 score and underscore the need for competitive evaluation to assess real-world attack robustness. PoisonArena provides a standardized framework to benchmark and develop future attack and defense strategies under more realistic, multi-adversary conditions. Project page: https://github.com/yxf203/PoisonArena.

[Arxiv](https://arxiv.org/abs/2505.12574)