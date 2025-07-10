# 审视他人的不足：基于LLM的科学知识生产框架

发布时间：2025年07月09日

`LLM应用` `社交网络`

> The Flaws of Others: An LLM-driven Framework for Scientific Knowledge Production

# 摘要

> 大型语言模型让写作成为人类与软件之间的实时对话。我们用一种讨论网络模型捕捉这一新型媒介，将人和大型语言模型视为平等节点，追踪他们陈述的传播。我们拓宽研究范围，不再局限于孤立的幻觉现象，定义了无效化（任何事实、逻辑或结构漏洞），并展示了它引发的四种危害：偏离事实、自我修复、重新编造和外部检测。我们开发了一种通用的讨论网络数学模型，提供深刻见解：仅受偏离事实和自我修复支配的网络稳定在适度错误率；加入重新编造则复现当前大型语言模型的高错误率。只要让每个虚假声明有很小概率接受同行评审，系统就会转向以真实为主导的状态。我们通过开源的\emph{Flaws-of-Others (FOO) 算法}实现同行评审：一个可配置循环，其中任何一组智能体相互批评，协调器整合判断。我们的启示既实际又文化：在这个新型媒介中，可靠性不在于完善单个模型，而在于将不完美模型连接成相互监督的网络。

> Large-language models turn writing into a live exchange between humans and software. We capture this new medium with a discursive-network model that treats people and LLMs as equal nodes and tracks how their statements circulate. Broadening the focus from isolated hallucinations, we define invalidation (any factual, logical, or structural breach) and show it follows four hazards: drift from truth, self-repair, fresh fabrication, and external detection. A general mathematical model of discursive networks is developed to provide valuable insights: A network governed only by drift and self-repair stabilizes at a modest error rate; adding fabrication reproduces the high rates seen in current LLMs. Giving each false claim even a small chance of peer review shifts the system to a truth-dominant state. We operationalize peer review with the open-source \emph{Flaws-of-Others (FOO) algorithm}: a configurable loop in which any set of agents critique one another while a harmoniser merges their verdicts. The takeaway is practical and cultural: reliability in this new medium comes not from perfecting single models but from wiring imperfect ones into networks that keep each other honest.

[Arxiv](https://arxiv.org/abs/2507.06565)