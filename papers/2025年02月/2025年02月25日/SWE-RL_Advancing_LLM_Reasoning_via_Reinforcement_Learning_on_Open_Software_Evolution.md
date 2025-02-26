# SWE-RL：通过强化学习在开放软件演化中提升大语言模型推理能力

发布时间：2025年02月25日

`LLM应用` `软件工程`

> SWE-RL: Advancing LLM Reasoning via Reinforcement Learning on Open Software Evolution

# 摘要

> DeepSeek-R1 的最新发布展现了强化学习（RL）在提升大型语言模型（LLMs）通用推理能力方面的巨大潜力。虽然 DeepSeek-R1 与其他后续研究主要聚焦于将 RL 应用于竞技编程和数学问题，但本文提出了一种全新的方法——SWE-RL，它是首个将基于 RL 的 LLM 推理能力扩展到现实世界软件工程领域的尝试。

通过采用轻量级规则基础奖励机制（如真实解决方案与 LLM 生成解决方案之间的相似性得分），SWE-RL 赋予了 LLM 自主恢复开发者推理过程和解决方案的能力。这一过程是通过从海量开源软件演化数据中学习实现的，这些数据完整记录了软件生命周期的每一个细节，包括代码快照、代码变更以及各类事件（如问题和拉取请求）。

基于 Llama 3 训练而成的推理模型 Llama3-SWE-RL-70B 在 SWE-bench Verified 数据集上达到了 41.0% 的解决率，这一数据集由经过人工验证的真实 GitHub 问题组成。据我们所知，这是目前中型（<100B）LLMs 中报告的最优性能，甚至可以与 GPT-4 等领先专有 LLM 相媲美。令人惊喜的是，尽管 Llama3-SWE-RL 仅在软件演化数据上进行了 RL 训练，它却展现出了强大的通用推理能力。例如，在函数编码、库使用、代码推理、数学和通用语言理解等五个跨领域任务中表现均有显著提升，而监督微调基线在这些任务上的平均表现甚至出现了下降。

总体而言，SWE-RL 为通过强化学习在海量软件工程数据上提升 LLM 的推理能力开辟了全新的研究方向。

> The recent DeepSeek-R1 release has demonstrated the immense potential of reinforcement learning (RL) in enhancing the general reasoning capabilities of large language models (LLMs). While DeepSeek-R1 and other follow-up work primarily focus on applying RL to competitive coding and math problems, this paper introduces SWE-RL, the first approach to scale RL-based LLM reasoning for real-world software engineering. Leveraging a lightweight rule-based reward (e.g., the similarity score between ground-truth and LLM-generated solutions), SWE-RL enables LLMs to autonomously recover a developer's reasoning processes and solutions by learning from extensive open-source software evolution data -- the record of a software's entire lifecycle, including its code snapshots, code changes, and events such as issues and pull requests. Trained on top of Llama 3, our resulting reasoning model, Llama3-SWE-RL-70B, achieves a 41.0% solve rate on SWE-bench Verified -- a human-verified collection of real-world GitHub issues. To our knowledge, this is the best performance reported for medium-sized (<100B) LLMs to date, even comparable to leading proprietary LLMs like GPT-4o. Surprisingly, despite performing RL solely on software evolution data, Llama3-SWE-RL has even emerged with generalized reasoning skills. For example, it shows improved results on five out-of-domain tasks, namely, function coding, library use, code reasoning, mathematics, and general language understanding, whereas a supervised-finetuning baseline even leads to performance degradation on average. Overall, SWE-RL opens up a new direction to improve the reasoning capabilities of LLMs through reinforcement learning on massive software engineering data.

[Arxiv](https://arxiv.org/abs/2502.18449)