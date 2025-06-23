# 基于因果框架的稳健奖励建模

发布时间：2025年06月19日

`LLM理论

这篇论文探讨了奖励模型在对齐大型语言模型中的挑战，并提出了一种新的框架来改进模型的对齐过程，属于LLM理论的范畴。` `人工智能` `因果推理`

> Robust Reward Modeling via Causal Rubrics

# 摘要

> 奖励模型（RMs）是通过人类反馈对齐大型语言模型（LLMs）的关键，但它们常常面临奖励黑客问题。这些模型容易过度关注表面或虚假的属性（如响应长度或格式），错误地将从训练数据相关性中学习到的这些线索当作质量（如事实性、相关性）的真实因果驱动因素。这种情况的根本原因是标准训练目标往往难以区分这些因素，导致奖励模型脆弱且策略对齐不力。我们提出了Crome（因果稳健奖励建模），这是一个基于明确因果模型的新框架，旨在缓解这一问题。Crome采用了两种合成针对性增强方法：（1）因果增强，通过沿特定因果属性不同的配对，强制沿每个因果属性的敏感性；（2）中性增强，通过以虚假属性为主要变化的标签相同配对，强制沿虚假属性的不变性。值得注意的是，我们的增强方法无需任何关于虚假因素的知识，仅通过沿因果准则的答案干预生成，这些因果准则通过查询一个Oracle LLM来识别。实证研究表明，Crome在RewardBench上显著超越标准基线，平均准确率提升高达5.4%，并在特定类别中分别获得13.2%和7.2%的提升。Crome的鲁棒性在Best-of-N推理设置中也得到了进一步验证，随着N的增加，在包括流行的RewardBench（涵盖聊天、聊天-困难、安全和推理任务）、以安全为重点的WildGuardTest以及专门针对推理的GSM8k等多个基准测试中均表现出一致的提升。

> Reward models (RMs) are fundamental to aligning Large Language Models (LLMs) via human feedback, yet they often suffer from reward hacking. They tend to latch on to superficial or spurious attributes, such as response length or formatting, mistaking these cues learned from correlations in training data for the true causal drivers of quality (e.g., factuality, relevance). This occurs because standard training objectives struggle to disentangle these factors, leading to brittle RMs and misaligned policies. We introduce Crome (Causally Robust Reward Modeling), a novel framework grounded in an explicit causal model designed to mitigate reward hacking. Crome employs the following synthetic targeted augmentations during training: (1) Causal Augmentations, which are pairs that differ along specific causal attributes, to enforce sensitivity along each causal attribute individually, and (2) Neutral Augmentations, which are tie-label pairs varying primarily in spurious attributes, to enforce invariance along spurious attributes. Notably, our augmentations are produced without any knowledge of spurious factors, via answer interventions only along causal rubrics, that are identified by querying an oracle LLM. Empirically, Crome significantly outperforms standard baselines on RewardBench, improving average accuracy by up to 5.4% and achieving gains of up to 13.2% and 7.2% in specific categories. The robustness of Crome is further testified by the consistent gains obtained in a Best-of-N inference setting across increasing N, across various benchmarks, including the popular RewardBench (covering chat, chat-hard, safety, and reasoning tasks), the safety-focused WildGuardTest, and the reasoning-specific GSM8k.

[Arxiv](https://arxiv.org/abs/2506.16507)