# AutoDroid-V2：借由代码生成增强基于 SLM 的 GUI 代理

发布时间：2024年12月23日

`LLM应用` `移动 UI 代理`

> AutoDroid-V2: Boosting SLM-based GUI Agents via Code Generation

# 摘要

> 大型语言模型（LLMs）为移动 UI 代理领域带来了令人欣喜的新突破，这一长期研究领域旨在通过移动 UI 交互来完成各类自然语言任务。然而，现有的 UI 代理往往需要强大的大型模型所具备的高推理能力，这类模型难以在终端用户设备上本地部署，从而引发了对用户隐私和集中服务成本的重大担忧。要减小所需模型的规模，一种方法是利用高质量训练数据定制较小的特定领域模型，比如不同类型应用和任务的大规模人工演示，但此类数据集极难获取。受近期小型语言模型（SLMs）出色编码能力的启发，我们提议将 UI 任务自动化问题转化为代码生成问题，这能通过设备上的 SLM 有效解决，并借助设备上的代码解释器高效执行。不同于可利用公共数据集广泛预训练的普通编码任务，由于目标应用的多样性、复杂性和多变性，生成 UI 自动化代码颇具挑战。因此，我们采用以文档为中心的方法，为每个应用自动构建细粒度的 API 文档，并基于此生成多样的任务样本。通过用合成文档和任务样本来引导代理，它学会生成精准高效的脚本以完成未曾见过的任务。通过与最先进的移动 UI 代理进行详细对比，我们的方法显著提高了移动任务自动化的成功率，降低了延迟和令牌消耗。代码将会开源。

> Large language models (LLMs) have brought exciting new advances to mobile UI agents, a long-standing research field that aims to complete arbitrary natural language tasks through mobile UI interactions. However, existing UI agents usually demand high reasoning capabilities of powerful large models that are difficult to be deployed locally on end-users' devices, which raises huge concerns about user privacy and centralized serving cost. One way to reduce the required model size is to customize a smaller domain-specific model with high-quality training data, e.g. large-scale human demonstrations of diverse types of apps and tasks, while such datasets are extremely difficult to obtain. Inspired by the remarkable coding abilities of recent small language models (SLMs), we propose to convert the UI task automation problem to a code generation problem, which can be effectively solved by an on-device SLM and efficiently executed with an on-device code interpreter. Unlike normal coding tasks that can be extensively pretrained with public datasets, generating UI automation code is challenging due to the diversity, complexity, and variability of target apps. Therefore, we adopt a document-centered approach that automatically builds fine-grained API documentation for each app and generates diverse task samples based on this documentation. By guiding the agent with the synthetic documents and task samples, it learns to generate precise and efficient scripts to complete unseen tasks. Based on detailed comparisons with state-of-the-art mobile UI agents, our approach effectively improves the mobile task automation with significantly higher success rates and lower latency/token consumption. Code will be open-sourced.

[Arxiv](https://arxiv.org/abs/2412.18116)