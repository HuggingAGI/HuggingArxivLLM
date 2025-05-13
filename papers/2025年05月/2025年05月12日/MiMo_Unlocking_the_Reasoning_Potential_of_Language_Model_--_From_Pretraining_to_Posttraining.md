# MiMo：释放语言模型的推理潜力——从预训练到微调

发布时间：2025年05月12日

`LLM应用` `人工智能`

> MiMo: Unlocking the Reasoning Potential of Language Model -- From Pretraining to Posttraining

# 摘要

> 我们隆重推出专为推理任务打造的大型语言模型 MiMo-7B，该模型在预训练和后训练两个阶段均进行了精心优化。在预训练阶段，我们优化了数据预处理流程，并采用三阶段数据混合策略，显著提升了基础模型的推理能力。MiMo-7B-Base 在 25 万亿个令牌的海量数据上进行预训练，同时引入了多令牌预测目标，进一步提升了性能并加速了推理速度。进入后训练阶段，我们精心整理了一个包含 13 万个可验证数学和编程问题的数据集，用于强化学习。我们创新性地采用了以测试难度驱动的代码奖励方案，有效缓解了稀疏奖励问题，并通过战略性数据重采样技术稳定了训练过程。经过全面评估，MiMo-7B-Base 展现出了惊人的推理潜力，甚至超越了规模大得多的 32B 模型。最终，经过强化学习调优的 MiMo-7B-RL 模型在数学、代码和一般推理任务中表现卓越，性能远超 OpenAI o1-mini。模型检查点现已开源，访问地址为 https://github.com/xiaomimimo/MiMo。

> We present MiMo-7B, a large language model born for reasoning tasks, with optimization across both pre-training and post-training stages. During pre-training, we enhance the data preprocessing pipeline and employ a three-stage data mixing strategy to strengthen the base model's reasoning potential. MiMo-7B-Base is pre-trained on 25 trillion tokens, with additional Multi-Token Prediction objective for enhanced performance and accelerated inference speed. During post-training, we curate a dataset of 130K verifiable mathematics and programming problems for reinforcement learning, integrating a test-difficulty-driven code-reward scheme to alleviate sparse-reward issues and employing strategic data resampling to stabilize training. Extensive evaluations show that MiMo-7B-Base possesses exceptional reasoning potential, outperforming even much larger 32B models. The final RL-tuned model, MiMo-7B-RL, achieves superior performance on mathematics, code and general reasoning tasks, surpassing the performance of OpenAI o1-mini. The model checkpoints are available at https://github.com/xiaomimimo/MiMo.

[Arxiv](https://arxiv.org/abs/2505.07608)