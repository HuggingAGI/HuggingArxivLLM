# MMFactory：一款面向视觉语言任务的通用解决方案搜索引擎

发布时间：2024年12月23日

`LLM应用` `视觉任务` `模型框架`

> MMFactory: A Universal Solution Search Engine for Vision-Language Tasks

# 摘要

> 随着基础模型与视觉语言模型的不断进步，以及有效的微调技术，针对各类视觉任务，大量通用及专用模型应运而生。尽管这些模型灵活且易于获取，但没有任何一个模型能够应对潜在用户可能构想的所有任务和/或应用。近期诸如视觉编程以及带有集成工具的多模态LLM等方法，旨在通过程序合成来攻克复杂的视觉任务。然而，这些方法忽视了用户的约束条件（比如性能/计算需求），生成了难以部署的针对测试样本的特定解决方案，有时还需要可能超出普通用户能力的低级指令。为突破这些局限，我们推出了MMFactory，这是一个包含模型和指标路由组件的通用框架，如同在各类可用模型中的解决方案搜索引擎。基于任务描述、少量样本输入输出对以及（可选的）资源和/或性能约束，MMFactory能够通过实例化并组合其模型库中的视觉语言工具，为用户提供多样的编程解决方案。除了生成这些解决方案，MMFactory还给出指标和基准性能/资源特征，方便用户挑选符合其独特设计约束的方案。从技术层面来讲，我们还引入了基于委员会的解决方案提议者，它借助多代理LLM对话为用户生成可执行、多样化、通用且强大的解决方案。实验结果显示，MMFactory凭借为用户问题规格提供前沿的解决方案，超越了现有方法。项目页面可在 https://davidhalladay.github.io/mmfactory_demo 查看。

> With advances in foundational and vision-language models, and effective fine-tuning techniques, a large number of both general and special-purpose models have been developed for a variety of visual tasks. Despite the flexibility and accessibility of these models, no single model is able to handle all tasks and/or applications that may be envisioned by potential users. Recent approaches, such as visual programming and multimodal LLMs with integrated tools aim to tackle complex visual tasks, by way of program synthesis. However, such approaches overlook user constraints (e.g., performance / computational needs), produce test-time sample-specific solutions that are difficult to deploy, and, sometimes, require low-level instructions that maybe beyond the abilities of a naive user. To address these limitations, we introduce MMFactory, a universal framework that includes model and metrics routing components, acting like a solution search engine across various available models. Based on a task description and few sample input-output pairs and (optionally) resource and/or performance constraints, MMFactory can suggest a diverse pool of programmatic solutions by instantiating and combining visio-lingual tools from its model repository. In addition to synthesizing these solutions, MMFactory also proposes metrics and benchmarks performance / resource characteristics, allowing users to pick a solution that meets their unique design constraints. From the technical perspective, we also introduced a committee-based solution proposer that leverages multi-agent LLM conversation to generate executable, diverse, universal, and robust solutions for the user. Experimental results show that MMFactory outperforms existing methods by delivering state-of-the-art solutions tailored to user problem specifications. Project page is available at https://davidhalladay.github.io/mmfactory_demo.

[Arxiv](https://arxiv.org/abs/2412.18072)