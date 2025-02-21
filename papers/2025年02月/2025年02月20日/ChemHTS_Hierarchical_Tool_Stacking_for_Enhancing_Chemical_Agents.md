# ChemHTS：分层工具叠加，提升化学智能体能力

发布时间：2025年02月20日

`LLM应用` `分子设计`

> ChemHTS: Hierarchical Tool Stacking for Enhancing Chemical Agents

# 摘要

> 大型语言模型（LLMs）在化学研究领域展现出了巨大潜力，尤其在分子设计、反应预测和性质估算等任务中表现突出。尽管工具增强的LLMs被引入以提升推理和计算能力，但现有方法仍存在工具调用错误和工具间协作不足的问题，限制了整体性能。为解决这些挑战，我们提出了ChemHTS（化学分层工具堆叠），这是一种通过分层堆叠策略优化工具调用路径的创新方法。ChemHTS包含两个关键阶段：工具自我堆叠预热和多层决策优化，使LLMs能够动态优化工具使用。我们在四个经典化学任务中评估了ChemHTS，结果显示其优于GPT-4o、DeepSeek-R1和化学专用模型ChemDFM等强大基线模型。此外，我们定义了四种不同的工具堆叠行为以增强可解释性，揭示了工具协作的有效性。我们的数据集和代码已在url{https://github.com/Chang-pw/ChemHTS}公开发布。

> Large Language Models (LLMs) have demonstrated remarkable potential in scientific research, particularly in chemistry-related tasks such as molecular design, reaction prediction, and property estimation. While tool-augmented LLMs have been introduced to enhance reasoning and computation in these domains, existing approaches suffer from tool invocation errors and lack effective collaboration among diverse tools, limiting their overall performance. To address these challenges, we propose ChemHTS (Chemical Hierarchical Tool Stacking), a novel method that optimizes tool invocation pathways through a hierarchical stacking strategy. ChemHTS consists of two key stages: tool self-stacking warmup and multi-layer decision optimization, enabling LLMs to refine tool usage dynamically. We evaluate ChemHTS across four classical chemistry tasks and demonstrate its superiority over strong baselines, including GPT-4o, DeepSeek-R1, and chemistry-specific models, including ChemDFM. Furthermore, we define four distinct tool-stacking behaviors to enhance interpretability, providing insights into the effectiveness of tool collaboration. Our dataset and code are publicly available at url{https://github.com/Chang-pw/ChemHTS}.

[Arxiv](https://arxiv.org/abs/2502.14327)