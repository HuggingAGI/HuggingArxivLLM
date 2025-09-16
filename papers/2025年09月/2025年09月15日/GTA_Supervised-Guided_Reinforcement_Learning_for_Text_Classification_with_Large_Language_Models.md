# GTA：面向大型语言模型文本分类的监督引导强化学习

发布时间：2025年09月15日

`强化学习` `基础理论`

> GTA: Supervised-Guided Reinforcement Learning for Text Classification with Large Language Models

# 摘要

> 在自然语言处理任务中，纯强化学习（RL）微调方法常受困于探索低效与收敛缓慢，而监督微调（SFT）虽训练高效，却存在性能上限受限、理论基础不及RL扎实的问题。为平衡效率与性能，我们提出猜-思-答（GTA）框架，在统一训练范式中融合SFT的高效性与RL的性能增益。GTA的工作流程为：模型先生成初步猜测（通过交叉熵损失优化），随后对该猜测进行反思，再生成最终答案——其中RL奖励同时作用于最终输出与整个GTA结构的格式设计。这种混合方法不仅收敛速度快于纯RL，性能上限也高于纯SFT。为缓解两种训练信号的梯度冲突，我们引入损失掩码与梯度约束机制。在四个文本分类基准数据集上的实验结果显示，GTA不仅显著加快收敛，性能还超越了单独的SFT与RL基线模型。

> In natural language processing tasks, pure reinforcement learning (RL) fine-tuning methods often suffer from inefficient exploration and slow convergence; while supervised fine-tuning (SFT) methods, although efficient in training, have limited performance ceiling and less solid theoretical foundation compared to RL. To address efficiency-capability trade-off, we propose the Guess-Think-Answer (GTA) framework that combines the efficiency of SFT with the capability gains of RL in a unified training paradigm. GTA works by having the model first produce a provisional guess (optimized via cross-entropy loss), then reflect on this guess before generating the final answer, with RL rewards shaping both the final output and the format of the entire GTA structure. This hybrid approach achieves both faster convergence than pure RL and higher performance ceiling than pure SFT. To mitigate gradient conflicts between the two training signals, we employ loss masking and gradient constraints. Empirical results on four text classification benchmarks demonstrate that GTA substantially accelerates convergence while outperforming both standalone SFT and RL baselines.

[Arxiv](https://arxiv.org/abs/2509.12108)