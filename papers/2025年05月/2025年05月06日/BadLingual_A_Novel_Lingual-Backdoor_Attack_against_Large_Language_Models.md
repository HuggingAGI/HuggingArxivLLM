# BadLingual：针对大型语言模型的新型语言后门攻击方法

发布时间：2025年05月06日

`LLM应用

论文摘要讨论了一种针对大型语言模型的新型后门攻击，分析了其在实际应用中的有效性，并提出了改进方法。这属于LLMs在安全方面的实际应用研究，因此归类为LLM应用。` `网络安全` `人工智能`

> BadLingual: A Novel Lingual-Backdoor Attack against Large Language Models

# 摘要

> 本文提出了一种针对大型语言模型 (LLMs) 的新型后门攻击——语言后门攻击。其核心创新在于，语言本身成为触发器，劫持受感染的 LLMs 生成煽动性言论，精准针对特定语言群体，加剧恶意行为的种族歧视。我们首先实现了基线语言后门攻击，通过将特定下游任务的训练数据集翻译成触发语言实施数据投毒。然而，该基线攻击在任务泛化上表现不佳，且在现实场景中不可行。为解决这一问题，我们设计了 BadLingual，一种任务无关的语言后门，能够触发聊天 LLMs 中的任何下游任务。我们采用基于 PPL 约束的贪婪坐标梯度搜索 (PGCG) 的对抗训练新方法，扩展语言后门的决策边界，增强其跨任务泛化能力。通过广泛实验，我们验证了所提攻击的有效性。具体而言，基线攻击在指定任务中实现 90% 以上的攻击成功率 (ASR)，但在任务无关场景下，仅达六项任务中的 37.61%。相比之下，BadLingual 比基线提升了 37.35%。本研究为具有多语言能力的 LLMs 的漏洞提供了新视角，并有望推动未来防御研究，增强 LLMs 的鲁棒性。

> In this paper, we present a new form of backdoor attack against Large Language Models (LLMs): lingual-backdoor attacks. The key novelty of lingual-backdoor attacks is that the language itself serves as the trigger to hijack the infected LLMs to generate inflammatory speech. They enable the precise targeting of a specific language-speaking group, exacerbating racial discrimination by malicious entities. We first implement a baseline lingual-backdoor attack, which is carried out by poisoning a set of training data for specific downstream tasks through translation into the trigger language. However, this baseline attack suffers from poor task generalization and is impractical in real-world settings. To address this challenge, we design BadLingual, a novel task-agnostic lingual-backdoor, capable of triggering any downstream tasks within the chat LLMs, regardless of the specific questions of these tasks. We design a new approach using PPL-constrained Greedy Coordinate Gradient-based Search (PGCG) based adversarial training to expand the decision boundary of lingual-backdoor, thereby enhancing the generalization ability of lingual-backdoor across various tasks. We perform extensive experiments to validate the effectiveness of our proposed attacks. Specifically, the baseline attack achieves an ASR of over 90% on the specified tasks. However, its ASR reaches only 37.61% across six tasks in the task-agnostic scenario. In contrast, BadLingual brings up to 37.35% improvement over the baseline. Our study sheds light on a new perspective of vulnerabilities in LLMs with multilingual capabilities and is expected to promote future research on the potential defenses to enhance the LLMs' robustness

[Arxiv](https://arxiv.org/abs/2505.03501)