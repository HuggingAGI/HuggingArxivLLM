# 在流程监督下，大型语言模型能够学习并推广隐写术的思维链。

发布时间：2025年06月02日

`LLM理论` `人工智能` `模型监控`

> Large language models can learn and generalize steganographic chain-of-thought under process supervision

# 摘要

> 链式思维（CoT）推理不仅显著提升了模型的性能，还为理解决策过程提供了关键见解，使其成为监控模型意图和规划的重要工具。通过主动阻止模型基于链式思维采取与目标不一致或有害意图的行动，链式思维监控能够有效降低模型部署带来的风险。然而，开发者可能由于客户偏好或监管要求，有动力训练模型以消除链式思维中显露出的有害意图迹象。近期研究表明，禁止提及某种特定的奖励黑客行为（这可能是为了使链式思维对用户更易接受，或是试图阻止此类行为的简单尝试），会导致不希望的推理链被模糊，但相关行为仍可能持续存在。这种模糊化威胁了链式思维监控的可靠性。然而，推理链的模糊化可能源于其内在化为潜在空间计算，或被编码在链式思维中。在这里，我们对这些结果进行了扩展。首先，我们展示了对关键推理链中特定字符串进行惩罚会导致模型使用替代字符串。关键的是，这并不会改变模型执行任务的根本方法，表明模型能够学习以隐写方式编码其推理过程。我们进一步证明，模型可以推广一种编码方案。当被惩罚的字符串属于某一广泛类别时，模型不仅学会替换训练中见过的字符串，还会为该类别的所有成员开发一种通用编码方案，并将其应用于独立测试中的字符串。

> Chain-of-thought (CoT) reasoning not only enhances large language model performance but also provides critical insights into decision-making processes, marking it as a useful tool for monitoring model intent and planning. By proactively preventing models from acting on CoT indicating misaligned or harmful intent, CoT monitoring can be used to reduce risks associated with deploying models. However, developers may be incentivized to train away the appearance of harmful intent from CoT traces, by either customer preferences or regulatory requirements. Recent works have shown that banning mention of a specific example of reward hacking, which may be done either to make CoT presentable to users or as a naive attempt to prevent the behavior, causes obfuscation of the undesired reasoning traces but the persistence of the undesired behavior. Such obfuscation threatens the reliability of CoT monitoring. However, obfuscation of reasoning can be due to its internalization to latent space computation, or its encoding within the CoT. Here, we provide an extension to these results. First, we show that penalizing the use of specific strings within load-bearing reasoning traces causes models to substitute alternative strings. Crucially, this does not alter the underlying method by which the model performs the task, demonstrating that the model can learn to steganographically encode its reasoning. We further demonstrate that models can generalize an encoding scheme. When the penalized strings belong to an overarching class, the model learns not only to substitute strings seen in training, but also develops a general encoding scheme for all members of the class which it can apply to held-out testing strings.

[Arxiv](https://arxiv.org/abs/2506.01926)