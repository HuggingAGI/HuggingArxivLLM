# 蒸馏设备端语言模型，用于机器人规划，最大限度减少人工干预

发布时间：2025年06月20日

`LLM应用

摘要中提到，论文讨论了如何将大型语言模型的能力迁移到设备端的小型模型，用于机器人规划，并展示了其在实际应用中的效果。这属于将LLM应用于具体场景，因此归类为LLM应用。` `机器人`

> Distilling On-device Language Models for Robot Planning with Minimal Human Intervention

# 摘要

> 大型语言模型（LLMs）赋予了机器人强大的上下文推理能力与自然的人机界面。然而，当前具备 LLM 功能的机器人通常依赖于云端托管的模型，这在通信基础设施不稳定的环境中（如户外或工业场景）限制了它们的实用性。我们提出了一种名为 PRISM 的框架，用于在设备端运行且仅需少量人工干预的小型语言模型（SLM）机器人规划器的蒸馏。从现有的 LLM 功能规划器出发，PRISM 能够自动合成多样化任务与环境，从 LLM 中提取规划方案，并利用这些合成数据集蒸馏出一个紧凑的 SLM 作为源模型的即插即用替代品。我们将 PRISM 应用于三个 LLM 功能规划器，分别用于地图绘制与探索、操作以及家庭辅助任务，并展示了 PRISM 如何将 Llama-3.2-3B 的性能从 GPT-4o 的 10-20% 提升至 93% 以上——仅使用合成数据。我们进一步证明，蒸馏后的规划器能够在异构机器人平台（地面与空中）和多样化环境（室内与室外）中实现良好泛化。所有软件、训练模型及数据集均可在 https://zacravichandran.github.io/PRISM 获取。

> Large language models (LLMs) provide robots with powerful contextual reasoning abilities and a natural human interface. Yet, current LLM-enabled robots typically depend on cloud-hosted models, limiting their usability in environments with unreliable communication infrastructure, such as outdoor or industrial settings. We present PRISM, a framework for distilling small language model (SLM)-enabled robot planners that run on-device with minimal human supervision. Starting from an existing LLM-enabled planner, PRISM automatically synthesizes diverse tasks and environments, elicits plans from the LLM, and uses this synthetic dataset to distill a compact SLM as a drop-in replacement of the source model. We apply PRISM to three LLM-enabled planners for mapping and exploration, manipulation, and household assistance, and we demonstrate that PRISM improves the performance of Llama-3.2-3B from 10-20% of GPT-4o's performance to over 93% - using only synthetic data. We further demonstrate that the distilled planners generalize across heterogeneous robotic platforms (ground and aerial) and diverse environments (indoor and outdoor). We release all software, trained models, and datasets at https://zacravichandran.github.io/PRISM.

[Arxiv](https://arxiv.org/abs/2506.17486)