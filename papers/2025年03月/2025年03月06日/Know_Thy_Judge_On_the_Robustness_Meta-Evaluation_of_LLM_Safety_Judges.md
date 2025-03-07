# # 标题
了解裁判者：LLM安全裁判的鲁棒性元评估

发布时间：2025年03月06日

`LLM应用

分类说明：这篇论文探讨了基于大型语言模型（LLM）的裁判系统在安全评估中的应用，揭示了评估中的关键挑战和对抗攻击的可能性。它属于LLM的应用层面，因为它专注于评估和测试LLM的安全性，而不是LLM本身的理论或架构。`

> Know Thy Judge: On the Robustness Meta-Evaluation of LLM Safety Judges

# 摘要

> 基于大型语言模型（LLM）的裁判系统是离线基准测试、自动化红队测试和在线护栏等关键安全评估流程的核心。然而，这一普遍需求引发了一个重要问题：我们能否信任这些评估者的评估结果？在本文中，我们揭示了两个常被忽视的关键挑战：(i) 真实世界中的评估，其中提示敏感性和分布偏移等因素可能会影响性能；(ii) 针对裁判的对抗攻击。通过研究常用的安全裁判系统，我们发现：模型输出风格的微小变化可能导致同一数据集上的假阴性率跃升高达0.24，而对模型生成过程的对抗攻击则可能误导某些裁判，使其将100%的有害生成内容错误分类为安全内容。这些发现揭示了当前元评估基准中的空白以及LLM裁判系统在鲁棒性方面的弱点，表明在某些裁判系统下攻击成功率低可能产生一种虚假的安全感。

> Large Language Model (LLM) based judges form the underpinnings of key safety evaluation processes such as offline benchmarking, automated red-teaming, and online guardrailing. This widespread requirement raises the crucial question: can we trust the evaluations of these evaluators? In this paper, we highlight two critical challenges that are typically overlooked: (i) evaluations in the wild where factors like prompt sensitivity and distribution shifts can affect performance and (ii) adversarial attacks that target the judge. We highlight the importance of these through a study of commonly used safety judges, showing that small changes such as the style of the model output can lead to jumps of up to 0.24 in the false negative rate on the same dataset, whereas adversarial attacks on the model generation can fool some judges into misclassifying 100% of harmful generations as safe ones. These findings reveal gaps in commonly used meta-evaluation benchmarks and weaknesses in the robustness of current LLM judges, indicating that low attack success under certain judges could create a false sense of security.

[Arxiv](https://arxiv.org/abs/2503.04474)