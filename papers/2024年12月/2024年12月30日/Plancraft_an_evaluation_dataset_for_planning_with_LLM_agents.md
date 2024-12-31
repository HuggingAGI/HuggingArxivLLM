# Plancraft：一个用于 LLM 代理规划的评估数据集

发布时间：2024年12月30日

`Agent` `人工智能评估`

> Plancraft: an evaluation dataset for planning with LLM agents

# 摘要

> 我们推出了 Plancraft，这是用于 LLM 代理的多模态评估数据集。Plancraft 具有纯文本和基于《我的世界》制作图形用户界面的多模态两种界面。我们引入《我的世界》维基来评估工具使用和检索增强生成（RAG），还设置了神谕规划器和神谕 RAG 信息提取器，以分解现代代理架构的不同组件。为评估决策制定，Plancraft 还包含故意设置为无法解决的示例子集，带来现实挑战，要求代理不仅要完成任务，还要判断任务是否根本可解。我们在任务中对开源和闭源的 LLM 及策略进行基准测试，并将其性能与手工规划器对比。我们发现 LLM 和 VLM 在 Plancraft 带来的规划问题上表现不佳，并给出了提升其能力的建议。

> We present Plancraft, a multi-modal evaluation dataset for LLM agents. Plancraft has both a text-only and multi-modal interface, based on the Minecraft crafting GUI. We include the Minecraft Wiki to evaluate tool use and Retrieval Augmented Generation (RAG), as well as an oracle planner and oracle RAG information extractor, to ablate the different components of a modern agent architecture. To evaluate decision-making, Plancraft also includes a subset of examples that are intentionally unsolvable, providing a realistic challenge that requires the agent not only to complete tasks but also to decide whether they are solvable at all. We benchmark both open-source and closed-source LLMs and strategies on our task and compare their performance to a handcrafted planner. We find that LLMs and VLMs struggle with the planning problems that Plancraft introduces, and we offer suggestions on how to improve their capabilities.

[Arxiv](https://arxiv.org/abs/2412.21033)