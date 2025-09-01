# OwkinZero：借助AI加速生物学发现

发布时间：2025年08月25日

`LLM应用` `医疗健康`

> OwkinZero: Accelerating Biological Discovery with AI

# 摘要

> 尽管大型语言模型（LLMs）在推动科学研究方面进展迅速，但在转化医学与生物医学发现不可或缺的核心生物推理任务上，它们仍显乏力。为突破这一局限，我们构建并筛选出八个全面的基准数据集，涵盖超30万条可验证问答对，精准聚焦药物研发中的关键难题，如靶点成药性、治疗方式适配性及药物扰动效应。依托该资源，我们采用基于可验证奖励的强化学习策略对开源LLMs进行后训练，成功研发出OwkinZero模型。研究结果显示，经过专项训练的8-32B OwkinZero模型在这些生物基准测试中，大幅超越了更大规模的顶尖商业LLMs。尤为重要的是，我们揭示了泛化能力的一个关键特征：针对单一任务训练的专业模型，在面对未接触过的新任务时，性能始终优于其基础模型。这一泛化效应在综合训练的OwkinZero模型中进一步增强——通过混合数据集训练，该模型实现了更广泛的跨任务提升。本研究为填补当前LLMs在生物推理方面的短板迈出了关键一步，证实通过在精心整理的数据上实施靶向强化学习，能够激发专业模型的泛化能力，进而加速人工智能驱动的生物发现进程。

> While large language models (LLMs) are rapidly advancing scientific research, they continue to struggle with core biological reasoning tasks essential for translational and biomedical discovery. To address this limitation, we created and curated eight comprehensive benchmark datasets comprising over 300,000 verifiable question-and-answer pairs, each targeting critical challenges in drug discovery including target druggability, modality suitability, and drug perturbation effects. Using this resource, we developed the OwkinZero models by post-training open-source LLMs through a Reinforcement Learning from Verifiable Rewards strategy. Our results demonstrate that specialized 8-32B OwkinZero models substantially outperform larger, state-of-the-art commercial LLMs on these biological benchmarks. Remarkably, we uncover evidence of a key aspect of generalization: specialist models trained on a single task consistently outperform their base models on previously unseen tasks. This generalization effect is further amplified in our comprehensive OwkinZero models, which were trained on a mixture of datasets and achieve even broader cross-task improvements. This study represents a significant step toward addressing the biological reasoning blind spot in current LLMs, demonstrating that targeted reinforcement learning on carefully curated data can unlock generalizable performance in specialized models, thereby accelerating AI-driven biological discovery.

[Arxiv](https://arxiv.org/abs/2508.16315)