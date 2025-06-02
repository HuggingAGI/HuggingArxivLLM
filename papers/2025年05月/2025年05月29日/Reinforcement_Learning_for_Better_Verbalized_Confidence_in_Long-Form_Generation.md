# 长文本生成中信心表达的强化学习方法

发布时间：2025年05月29日

`LLM应用` `大型语言模型` `事实生成`

> Reinforcement Learning for Better Verbalized Confidence in Long-Form Generation

# 摘要

> 幻觉仍然是大型语言模型 (LLMs) 在事实内容生成中安全可靠部署的主要挑战。已有研究探索了信心估计作为幻觉检测的有效方法，但通常依赖于需要昂贵计算采样的事后自我一致性方法。口头表达的信心提供了一种更高效的替代方案，但现有方法主要局限于短格式问答 (QA) 任务，无法很好地推广到开放生成。本文提出了一种名为 LoVeC (长格式口头信心) 的实时长格式生成口头信心估计方法。具体来说，我们使用强化学习 (RL) 来训练 LLMs 为每个生成的陈述附加数值信心分数，作为生成事实性的直接且可解释的信号。我们的实验考虑了包括 DPO、ORPO 和 GRPO 在内的 on-policy 和 off-policy RL 方法，以增强模型校准。我们引入了两种新的评估设置，自由形式标记和迭代标记，来评估不同的口头信心估计方法。在三个长格式 QA 数据集上的实验表明，我们的 RL 训练模型实现了更好的校准，并在跨领域中表现稳健。此外，我们的方法非常高效，因为它只需要在解码输出中添加几个令牌。

> Hallucination remains a major challenge for the safe and trustworthy deployment of large language models (LLMs) in factual content generation. Prior work has explored confidence estimation as an effective approach to hallucination detection, but often relies on post-hoc self-consistency methods that require computationally expensive sampling. Verbalized confidence offers a more efficient alternative, but existing approaches are largely limited to short-form question answering (QA) tasks and do not generalize well to open-ended generation. In this paper, we propose LoVeC (Long-form Verbalized Confidence), an on-the-fly verbalized confidence estimation method for long-form generation. Specifically, we use reinforcement learning (RL) to train LLMs to append numerical confidence scores to each generated statement, serving as a direct and interpretable signal of the factuality of generation. Our experiments consider both on-policy and off-policy RL methods, including DPO, ORPO, and GRPO, to enhance the model calibration. We introduce two novel evaluation settings, free-form tagging and iterative tagging, to assess different verbalized confidence estimation methods. Experiments on three long-form QA datasets show that our RL-trained models achieve better calibration and generalize robustly across domains. Also, our method is highly efficient, as it only requires adding a few tokens to the output being decoded.

[Arxiv](https://arxiv.org/abs/2505.23912)