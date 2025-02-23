# Text2World：大型语言模型生成符号世界模型的基准测试

发布时间：2025年02月18日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在生成符号世界模型方面的应用，提出了新的基准测试工具Text2World，并分析了LLMs在世界建模中的表现及提升策略。因此，它属于LLM应用类别。` `人工智能` `基准测试`

> Text2World: Benchmarking Large Language Models for Symbolic World Model Generation

# 摘要

> 近年来，利用大型语言模型（LLMs）从文本描述生成符号世界模型的研究热度持续攀升。尽管LLMs在世界建模领域已得到广泛应用，但现有研究仍面临诸多挑战，如评估的随机性、对间接指标的依赖以及领域范围有限。为突破这些限制，我们推出了一款基于规划领域定义语言（PDDL）的全新基准测试工具——Text2World。它涵盖了数百个多样化领域，并通过多标准、基于执行的指标实现更可靠的评估。通过Text2World对当前LLMs进行基准测试后发现，采用大规模强化学习训练的推理模型表现更优。然而，即使是性能最佳的模型，在世界建模方面仍显不足。基于此，我们探索了多种提升LLMs世界建模能力的策略，包括测试时缩放和代理训练等。Text2World有望成为未来研究的重要资源，为利用LLMs构建世界模型奠定基础。项目详情请访问https://text-to-world.github.io/。

> Recently, there has been growing interest in leveraging large language models (LLMs) to generate symbolic world models from textual descriptions. Although LLMs have been extensively explored in the context of world modeling, prior studies encountered several challenges, including evaluation randomness, dependence on indirect metrics, and a limited domain scope. To address these limitations, we introduce a novel benchmark, Text2World, based on planning domain definition language (PDDL), featuring hundreds of diverse domains and employing multi-criteria, execution-based metrics for a more robust evaluation. We benchmark current LLMs using Text2World and find that reasoning models trained with large-scale reinforcement learning outperform others. However, even the best-performing model still demonstrates limited capabilities in world modeling. Building on these insights, we examine several promising strategies to enhance the world modeling capabilities of LLMs, including test-time scaling, agent training, and more. We hope that Text2World can serve as a crucial resource, laying the groundwork for future research in leveraging LLMs as world models. The project page is available at https://text-to-world.github.io/.

[Arxiv](https://arxiv.org/abs/2502.13092)