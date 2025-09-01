# OwkinZero：用AI加速生物学发现

发布时间：2025年08月25日

`强化学习` `医疗健康`

> OwkinZero: Accelerating Biological Discovery with AI

# 摘要

> 尽管大型语言模型（LLMs）正迅速推动科学研究，但在转化医学和生物医学发现所需的核心生物学推理任务上，它们仍面临挑战。为解决这一局限，我们创建并精心整理了八个全面的基准数据集，涵盖30多万个可验证问答对，每个数据集均聚焦药物发现的关键难题，如靶点成药性、治疗方式适配性及药物扰动效应。借助这一资源，我们采用基于可验证奖励的强化学习策略，对开源LLMs进行后训练，进而开发出OwkinZero模型。研究结果显示，专门优化的8-32B OwkinZero模型在这些生物学基准测试中，性能显著超越了更大规模的顶级商业LLMs。值得关注的是，我们发现了泛化能力的一个关键特征：在单一任务上训练的专业模型，在面对从未接触过的新任务时，表现始终优于其基础模型。这一泛化效应在我们的综合OwkinZero模型中进一步放大——这些模型通过混合数据集训练，实现了更广泛的跨任务性能提升。这项研究为解决当前LLMs在生物学推理方面的短板迈出了关键一步，证明通过在精心整理的数据上进行针对性强化学习，能够激发专业模型的可泛化性能，进而加速AI驱动的生物学发现。

> While large language models (LLMs) are rapidly advancing scientific research, they continue to struggle with core biological reasoning tasks essential for translational and biomedical discovery. To address this limitation, we created and curated eight comprehensive benchmark datasets comprising over 300,000 verifiable question-and-answer pairs, each targeting critical challenges in drug discovery including target druggability, modality suitability, and drug perturbation effects. Using this resource, we developed the OwkinZero models by post-training open-source LLMs through a Reinforcement Learning from Verifiable Rewards strategy. Our results demonstrate that specialized 8-32B OwkinZero models substantially outperform larger, state-of-the-art commercial LLMs on these biological benchmarks. Remarkably, we uncover evidence of a key aspect of generalization: specialist models trained on a single task consistently outperform their base models on previously unseen tasks. This generalization effect is further amplified in our comprehensive OwkinZero models, which were trained on a mixture of datasets and achieve even broader cross-task improvements. This study represents a significant step toward addressing the biological reasoning blind spot in current LLMs, demonstrating that targeted reinforcement learning on carefully curated data can unlock generalizable performance in specialized models, thereby accelerating AI-driven biological discovery.

[Arxiv](https://arxiv.org/abs/2508.16315)