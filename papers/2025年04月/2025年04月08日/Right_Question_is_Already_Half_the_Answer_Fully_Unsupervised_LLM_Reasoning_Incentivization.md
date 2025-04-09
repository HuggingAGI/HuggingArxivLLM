# 正确的问题已解答一半：激励 LLM 进行推理的完全无监督方法

发布时间：2025年04月08日

`LLM理论` `人工智能` `优化算法`

> Right Question is Already Half the Answer: Fully Unsupervised LLM Reasoning Incentivization

# 摘要

> 大型语言模型 (LLMs) 虽然在数学推理等复杂任务中表现出色，但现有提升推理能力的方法多依赖于预训练后的监督微调 (SFT) 和强化学习 (RL)，这些方法需要依赖外部监督信息（如人工标注的推理轨迹、标准答案或预训练奖励模型），限制了其扩展性和实用性。本研究提出了一种名为基于熵最小化的策略优化方法 (EMPO)，首次尝试实现完全无监督的 LLM 推理能力提升。EMPO 不依赖任何监督信息，通过在潜在语义空间中持续优化 LLM 对未标注查询的预测熵，实现了推理能力的自我进化。实验结果显示，EMPO 在数学推理和常识推理任务中表现优异。例如，在无监督条件下，EMPO 将 Qwen2.5-Math-7B Base 的数学推理准确率从 30.7% 提升至 48.1%，并将 Qwen2.5-7B Instruct 的事实准确性从 87.16% 提升至 97.25%。

> While large language models (LLMs) have demonstrated exceptional capabilities in challenging tasks such as mathematical reasoning, existing methods to enhance reasoning ability predominantly rely on supervised fine-tuning (SFT) followed by reinforcement learning (RL) on reasoning-specific data after pre-training. However, these approaches critically depend on external supervisions--such as human labelled reasoning traces, verified golden answers, or pre-trained reward models--which limits scalability and practical applicability. In this work, we propose Entropy Minimized Policy Optimization (EMPO), which makes an early attempt at fully unsupervised LLM reasoning incentivization. EMPO does not require any supervised information for incentivizing reasoning capabilities (i.e., neither verifiable reasoning traces, problems with golden answers, nor additional pre-trained reward models). By continuously minimizing the predictive entropy of LLMs on unlabeled user queries in a latent semantic space, EMPO enables purely self-supervised evolution of reasoning capabilities with strong flexibility and practicality. Our experiments demonstrate competitive performance of EMPO on both mathematical reasoning and free-form commonsense reasoning tasks. Specifically, without any supervised signals, EMPO boosts the accuracy of Qwen2.5-Math-7B Base from 30.7\% to 48.1\% on mathematical benchmarks and improves truthfulness accuracy of Qwen2.5-7B Instruct from 87.16\% to 97.25\% on TruthfulQA.

[Arxiv](https://arxiv.org/abs/2504.05812)