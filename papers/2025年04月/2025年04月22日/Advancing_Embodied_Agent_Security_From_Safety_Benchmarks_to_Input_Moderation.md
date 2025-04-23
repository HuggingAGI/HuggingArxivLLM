# # 推进具身智能体安全：从安全基准到输入内容的调节

发布时间：2025年04月22日

`Agent` `人工智能`

> Advancing Embodied Agent Security: From Safety Benchmarks to Input Moderation

# 摘要

> 具身智能体在多个领域展现出巨大潜力，确保其行为安全是实现广泛应用的关键前提。然而，现有研究主要关注通用大型语言模型的安全性，缺乏专门针对具身智能体的安全基准和输入 moderation 方法。为填补这一空白，本文提出了一种新型输入 moderation 框架，专为保护具身智能体而设计。该框架涵盖 taxonomy 定义、数据集整理、 moderator 架构、模型训练和严格评估等环节。我们引入了 EAsafetyBench，一个精心设计的安全基准，旨在促进专门针对具身智能体的 moderator 的训练和评估。此外，我们提出了 Pinpoint，这是一种创新的 prompt-decoupled 输入 moderation 方案，通过遮蔽注意力机制有效隔离和缓解功能性 prompts 对 moderation 任务的影响。在多样化的基准数据集和模型上进行的广泛实验验证了所提方法的可行性和有效性。结果显示，我们的方法实现了 94.58% 的平均检测准确率，超越现有最先进的技术，并以每实例仅 0.002 秒的处理时间展现了卓越的 moderation 效率。


> Embodied agents exhibit immense potential across a multitude of domains, making the assurance of their behavioral safety a fundamental prerequisite for their widespread deployment. However, existing research predominantly concentrates on the security of general large language models, lacking specialized methodologies for establishing safety benchmarks and input moderation tailored to embodied agents. To bridge this gap, this paper introduces a novel input moderation framework, meticulously designed to safeguard embodied agents. This framework encompasses the entire pipeline, including taxonomy definition, dataset curation, moderator architecture, model training, and rigorous evaluation. Notably, we introduce EAsafetyBench, a meticulously crafted safety benchmark engineered to facilitate both the training and stringent assessment of moderators specifically designed for embodied agents. Furthermore, we propose Pinpoint, an innovative prompt-decoupled input moderation scheme that harnesses a masked attention mechanism to effectively isolate and mitigate the influence of functional prompts on moderation tasks. Extensive experiments conducted on diverse benchmark datasets and models validate the feasibility and efficacy of the proposed approach. The results demonstrate that our methodologies achieve an impressive average detection accuracy of 94.58%, surpassing the performance of existing state-of-the-art techniques, alongside an exceptional moderation processing time of merely 0.002 seconds per instance.

[Arxiv](https://arxiv.org/abs/2504.15699)