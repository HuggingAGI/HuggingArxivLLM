# 大型语言模型驱动的个性化网络代理

发布时间：2024年10月22日

`Agent

理由：这篇论文主要讨论了基于大型语言模型（LLMs）的个性化 Web 代理，强调了如何通过整合用户个性化数据来提升代理的性能。论文提出了一个名为“个性化用户记忆增强对齐”（PUMA）的框架，并构建了一个评估基准（PersonalWAB）来测试代理的性能。这些内容主要围绕智能代理的设计、优化和评估展开，因此应归类为Agent。` `Web应用` `个性化服务`

> Large Language Models Empowered Personalized Web Agents

# 摘要

> # 摘要
Web 代理已成为基于用户指令自动化完成 Web 任务的有力工具，显著提升了用户体验。近年来，Web 代理从传统代理演变为基于大型语言模型（LLMs）的智能代理。然而，现有基于 LLM 的 Web 代理往往忽视了用户个性化数据（如用户配置文件和历史 Web 行为）在理解用户个性化指令和执行定制操作中的关键作用。为此，我们首次提出了 LLM 赋能的个性化 Web 代理任务，旨在通过整合个性化数据和用户指令，实现更精准的指令理解和操作执行。为解决缺乏全面评估基准的问题，我们构建了“个性化 Web 代理基准”（PersonalWAB），涵盖用户指令、个性化数据、Web 功能以及跨三个个性化 Web 任务的两种评估范式。此外，我们提出了“个性化用户记忆增强对齐”（PUMA）框架，通过任务特定的检索策略筛选相关历史 Web 行为，并基于这些行为，利用微调和直接偏好优化技术，使 LLMs 更好地执行个性化操作。大量实验表明，PUMA 在 PersonalWAB 上的表现显著优于现有 Web 代理。

> Web agents have emerged as a promising direction to automate Web task completion based on user instructions, significantly enhancing user experience. Recently, Web agents have evolved from traditional agents to Large Language Models (LLMs)-based Web agents. Despite their success, existing LLM-based Web agents overlook the importance of personalized data (e.g., user profiles and historical Web behaviors) in assisting the understanding of users' personalized instructions and executing customized actions. To overcome the limitation, we first formulate the task of LLM-empowered personalized Web agents, which integrate personalized data and user instructions to personalize instruction comprehension and action execution. To address the absence of a comprehensive evaluation benchmark, we construct a Personalized Web Agent Benchmark (PersonalWAB), featuring user instructions, personalized user data, Web functions, and two evaluation paradigms across three personalized Web tasks. Moreover, we propose a Personalized User Memory-enhanced Alignment (PUMA) framework to adapt LLMs to the personalized Web agent task. PUMA utilizes a memory bank with a task-specific retrieval strategy to filter relevant historical Web behaviors. Based on the behaviors, PUMA then aligns LLMs for personalized action execution through fine-tuning and direct preference optimization. Extensive experiments validate the superiority of PUMA over existing Web agents on PersonalWAB.

[Arxiv](https://arxiv.org/abs/2410.17236)