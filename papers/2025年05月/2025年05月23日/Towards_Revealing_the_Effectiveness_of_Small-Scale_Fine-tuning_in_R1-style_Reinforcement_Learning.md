# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年05月23日

`LLM理论` `人工智能` `机器学习`

> Towards Revealing the Effectiveness of Small-Scale Fine-tuning in R1-style Reinforcement Learning

# 摘要

> R1风格的强化学习（RL）显著提升了大型语言模型的推理能力，但基于规则的RL机制仍不清晰。我们发现小规模的SFT训练对RL有显著影响，但效率较低。为了验证我们的观察，我们提出了一种分析框架，并通过测量样本效果来比较SFT和RL的效率。假设分析表明，SFT的效率受限于训练数据。基于此分析，我们提出了再蒸馏技术，通过从RL训练策略中进行小规模蒸馏来微调预训练模型。在骑士与无赖和MATH数据集上的实验展示了再蒸馏令人惊讶的高效性：再蒸馏模型仅需少量样本和计算就能达到RL性能。实证验证表明，样本效果是性能提升的良好指标。因此，在K&K数据集上，我们的再蒸馏Qwen2.5-1.5B模型仅用1K SFT样本就超越了DeepSeek-V3-0324。在MATH数据集上，仅需再蒸馏500样本，Qwen2.5-1.5B模型的性能就可媲美其指令微调版本，而无需RL。我们的工作解释了R1风格RL中的几个有趣现象，揭示了其实际成功背后的机制。代码已开源：https://github.com/on1262/deep-reasoning

> R1-style Reinforcement Learning (RL) significantly enhances Large Language Models' reasoning capabilities, yet the mechanism behind rule-based RL remains unclear. We found that small-scale SFT has significant influence on RL but shows poor efficiency. To explain our observations, we propose an analytical framework and compare the efficiency of SFT and RL by measuring sample effect. Hypothetical analysis show that SFT efficiency is limited by training data. Guided by our analysis, we propose Re-distillation, a technique that fine-tunes pretrain model through small-scale distillation from the RL-trained policy. Experiments on Knight & Knave and MATH datasets demonstrate re-distillation's surprising efficiency: re-distilled models match RL performance with far fewer samples and less computation. Empirical verification shows that sample effect is a good indicator of performance improvements. As a result, on K&K dataset, our re-distilled Qwen2.5-1.5B model surpasses DeepSeek-V3-0324 with only 1K SFT samples. On MATH, Qwen2.5-1.5B fine-tuned with re-distilled 500 samples matches its instruct-tuned variant without RL. Our work explains several interesting phenomena in R1-style RL, shedding light on the mechanisms behind its empirical success. Code is available at: https://github.com/on1262/deep-reasoning

[Arxiv](https://arxiv.org/abs/2505.17988)