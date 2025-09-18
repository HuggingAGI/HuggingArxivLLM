# # OpenHA：《我的世界》中的一系列开源分层智能体模型

发布时间：2025年09月12日

`Agent` `媒体与娱乐`

> OpenHA: A Series of Open-Source Hierarchical Agentic Models in Minecraft

# 摘要

> 动作空间的选择是开发高性能端到端可训练智能体的关键难题，至今悬而未决。本文首次在开放式《我的世界》环境中，对视觉-语言-动作（VLA）或层次化智能体模型的主流抽象动作空间及分词器展开大规模系统比较。分析发现，不存在普适最优的动作空间；相反，最优抽象方式与任务高度相关，这给通用智能体的构建带来了难题。为此，我们提出动作链（CoA）框架：一种能在单一整体式VLA模型中融合高层规划与低层控制的全新方案。CoA不把抽象动作当作独立策略的指令，而是将其视为一种中间推理步骤（类似思维链），用于引导最终可执行动作的生成。我们进一步证明，采用CoA范式、在多样化动作空间混合数据上训练的一体化智能体，能习得更稳健且泛化性更强的策略。该统一智能体性能刷新了当前最先进水平，相比高性能专用基线模型，整体任务成功率显著提高。为推动可复现研究，我们发布了OpenHA（开放层次化智能体）套件，内含800余项任务的综合基准、精选数据集、源代码及所有预训练模型 checkpoint，详情可访问https://github.com/CraftJarvis/OpenHA。

> The choice of action spaces is a critical yet unresolved challenge in developing capable, end-to-end trainable agents. This paper first presents a large-scale, systematic comparison of prominent abstracted action spaces and tokenizers for Vision-Language-Action (VLA) or hierarchical agent models in the open-ended Minecraft. Our analysis reveals that no single action space is universally optimal; instead, the most effective abstraction is highly task-dependent, creating a dilemma for building generalist agents. To resolve this, we introduce Chain of Action (CoA), a novel framework that unifies high-level planning and low-level control within a single, monolithic VLA model. CoA treats an abstracted action not as a command for a separate policy, but as an intermediate reasoning step--akin to a chain of thought--that guides the generation of the final, executable action. Furthermore, we demonstrate that an All-in-One agent trained on a diverse mixture of action spaces using the CoA paradigm learns a more robust and generalizable policy. This unified agent achieves a new state-of-the-art, improving the overall task success rate over strong, specialized baselines. To foster reproducible research, we release the OpenHA (Open Hierarchical Agents) suite, which includes our comprehensive benchmark of over 800 distinct tasks, curated datasets, source code, and all pretrained model checkpoints at https://github.com/CraftJarvis/OpenHA

[Arxiv](https://arxiv.org/abs/2509.13347)