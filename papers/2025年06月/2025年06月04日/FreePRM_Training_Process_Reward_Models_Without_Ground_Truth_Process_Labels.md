# FreePRM：无真实流程标签的流程奖励模型训练方法

发布时间：2025年06月04日

`LLM理论` `机器学习`

> FreePRM: Training Process Reward Models Without Ground Truth Process Labels

# 摘要

> 近期研究表明，大语言模型（LLMs）的进步凸显了过程奖励模型（PRMs）在提升模型性能中的至关重要性。然而，训练PRMs通常需要基于步骤的标签，这些标签无论是人工标注还是自动生成，都面临成本高昂和难以大规模获取的挑战。为解决这一难题，我们提出了FreePRM——一个无需真实步骤级标签的弱监督框架，用于训练PRMs。FreePRM首先根据最终结果的正确性生成伪步骤级标签，然后通过Buffer Probability技术有效消除伪标签中的噪声影响。实验结果表明，在ProcessBench数据集上，FreePRM实现了平均F1分数53.0%，相较于基于Math-Shepherd的全监督PRM提升了+24.1%。与其它开源PRMs相比，FreePRM的表现优于RLHFlow-PRM-Mistral-8B（28.4%）+24.6%，EurusPRM（31.3%）+21.7%，以及Skywork-PRM-7B（42.1%）+10.9%。这项研究为PRM训练开辟了全新范式，在大幅降低对昂贵步骤级标注依赖的同时，仍保持了强劲的性能表现。

> Recent advancements in Large Language Models (LLMs) have demonstrated that Process Reward Models (PRMs) play a crucial role in enhancing model performance. However, training PRMs typically requires step-level labels, either manually annotated or automatically generated, which can be costly and difficult to obtain at scale. To address this challenge, we introduce FreePRM, a weakly supervised framework for training PRMs without access to ground-truth step-level labels. FreePRM first generates pseudo step-level labels based on the correctness of final outcome, and then employs Buffer Probability to eliminate impact of noise inherent in pseudo labeling. Experimental results show that FreePRM achieves an average F1 score of 53.0% on ProcessBench, outperforming fully supervised PRM trained on Math-Shepherd by +24.1%. Compared to other open-source PRMs, FreePRM outperforms upon RLHFlow-PRM-Mistral-8B (28.4%) by +24.6%, EurusPRM (31.3%) by +21.7%, and Skywork-PRM-7B (42.1%) by +10.9%. This work introduces a new paradigm in PRM training, significantly reducing reliance on costly step-level annotations while maintaining strong performance.

[Arxiv](https://arxiv.org/abs/2506.03570)