# Chain-of-Memory: Enhancing GUI Agents for Cross-Application Navigation
记忆链：增强 GUI 代理实现跨应用导航

发布时间：2025年06月22日

`Agent` `软件工程` `人工智能`

> Chain-of-Memory: Enhancing GUI Agents for Cross-Application Navigation

# 摘要

> 多模态大型语言模型（MLLMs）在图形用户界面（GUI）代理的开发中正吸引越来越多的关注。现有方法通常依赖历史截图或操作来隐式表示任务状态，但这种依赖给GUI代理准确理解任务状态带来了挑战，并突显了在复杂且冗长的跨应用任务中缺乏有效机制来存储关键信息。为了解决这些问题，我们提出了记忆链（CoM），一种在GUI代理中显式建模短期记忆和长期记忆的新方法。CoM通过捕获动作描述、整合任务相关的屏幕信息，并维护一个专用的记忆模块来存储和管理这些信息，从而实现这一点。通过利用显式记忆表示，CoM使GUI代理能够更好地理解任务状态并持续保留关键历史信息。为了赋予GUI代理记忆管理能力并评估CoM的有效性，我们开发了GUI Odyssey-CoM数据集，其中包含111,000个标注了记忆链的屏幕-动作对。实验结果表明，CoM显著提升了GUI代理在跨应用任务中的性能。此外，GUI Odyssey-CoM使7B规模的模型能够实现与72B规模模型相当的记忆管理能力。该数据集和代码将开源发布。

> Multimodal large language models (MLLMs) are attracting growing attention in the development of Graphical User Interface (GUI) agents. Existing approaches often rely on historical screenshots or actions to implicitly represent the task state. This reliance poses challenges for GUI agents in accurately understanding task states and underscores the absence of effective mechanisms to store critical information in complex and lengthy cross-app tasks. To address these challenges, we propose Chain-of-Memory (CoM), a novel approach for explicitly modeling short-term and long-term memory in GUI agents. CoM achieves this by capturing action descriptions, integrating task-relevant screen information, and maintaining a dedicated memory module to store and manage this information. By leveraging explicit memory representations, CoM enables GUI agents to better understand task states and retain critical historical information persistently. To equip GUI agents with memory management capabilities and evaluate the effectiveness of CoM, we developed the GUI Odyssey-CoM, a dataset comprising 111k screen-action pairs annotated with Chain-of-Memory. Experimental results demonstrate that CoM significantly improves GUI agents' performance in cross-application tasks. Additionally, GUI Odyssey-CoM enables 7B models to achieve memory management capabilities comparable to 72B models. The dataset and code will be open-sourced.

[Arxiv](https://arxiv.org/abs/2506.18158)