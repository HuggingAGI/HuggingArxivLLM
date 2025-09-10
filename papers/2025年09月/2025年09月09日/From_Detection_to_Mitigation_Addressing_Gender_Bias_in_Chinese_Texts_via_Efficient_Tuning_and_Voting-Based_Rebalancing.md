# 从检测到缓解：通过高效调优与基于投票的再平衡应对中文文本中的性别偏见

发布时间：2025年09月09日

`LLM应用` `基础理论`

> From Detection to Mitigation: Addressing Gender Bias in Chinese Texts via Efficient Tuning and Voting-Based Rebalancing

# 摘要

> 本文介绍了我们团队针对NLPCC-2025共享任务7的解决方案，该任务聚焦中文句子级别的性别偏见检测与缓解。其目标是通过自动检测、分类并缓解性别偏见，提升自然语言生成的公平性与可控性。为应对此挑战，我们采用基于大型语言模型（LLMs）的微调方案，借助低秩适应（LoRA）高效适配偏见检测任务。数据处理上，我们构建更均衡的训练集以缓解类别不平衡，并引入多源异构样本提升模型泛化能力。针对检测与分类子任务，我们采用多数投票策略，整合多个专家模型的输出结果以提升性能。此外，为优化偏见生成检测与缓解效果，我们设计多温度采样机制来捕捉偏见表达方式的潜在差异。实验结果验证了我们的方法在偏见检测、分类及缓解任务中的有效性，最终以47.90%的平均得分在该共享任务中位列第四。

> This paper presents our team's solution to Shared Task 7 of NLPCC-2025, which focuses on sentence-level gender bias detection and mitigation in Chinese. The task aims to promote fairness and controllability in natural language generation by automatically detecting, classifying, and mitigating gender bias. To address this challenge, we adopt a fine-tuning approach based on large language models (LLMs), efficiently adapt to the bias detection task via Low-Rank Adaptation (LoRA). In terms of data processing, we construct a more balanced training set to alleviate class imbalance and introduce heterogeneous samples from multiple sources to enhance model generalization. For the detection and classification sub-tasks, we employ a majority voting strategy that integrates outputs from multiple expert models to boost performance. Additionally, to improve bias generation detection and mitigation, we design a multi-temperature sampling mechanism to capture potential variations in bias expression styles. Experimental results demonstrate the effectiveness of our approach in bias detection, classification, and mitigation. Our method ultimately achieves an average score of 47.90%, ranking fourth in the shared task.

[Arxiv](https://arxiv.org/abs/2509.07889)