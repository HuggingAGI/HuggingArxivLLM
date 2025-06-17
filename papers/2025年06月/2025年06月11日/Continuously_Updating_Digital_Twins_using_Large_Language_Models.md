# 借助大型语言模型 实时更新数字孪生

发布时间：2025年06月11日

`LLM应用` `数字孪生` `工业互联网`

> Continuously Updating Digital Twins using Large Language Models

# 摘要

> 数字孪生是现实系统的动态模型，能够模拟其对各种操作的响应。在复杂环境中，系统的状态、动作变量及相关数据和知识会不断变化，要求数字孪生需持续更新以保持实用性。然而，现有方法难以应对这一挑战，因为它们依赖固定且明确的建模环境，无法在不重新设计的情况下适应新变量，也无法在不重新训练的情况下整合新信息。为解决这一问题，我们采用大语言模型将数字孪生建模为上下文学习问题，实现在推理阶段对孪生模型的无缝更新。我们开发了CALM-DT，一种基于上下文自适应语言模型的数字孪生系统，通过利用微调编码器进行样本检索，仅借助上下文学习即可在多样化状态-动作空间中实现精准模拟。实证研究表明，CALM-DT不仅在性能上与现有数字孪生方法相媲美，还具备无需参数更新即可适应建模环境变化的独特能力。

> Digital twins are models of real-world systems that can simulate their dynamics in response to potential actions. In complex settings, the state and action variables, and available data and knowledge relevant to a system can constantly change, requiring digital twins to continuously update with these changes to remain relevant. Current approaches struggle in this regard, as they require fixed, well-defined modelling environments, and they cannot adapt to novel variables without re-designs, or incorporate new information without re-training. To address this, we frame digital twinning as an in-context learning problem using large language models, enabling seamless updates to the twin at inference time. We develop CALM-DT, a Context-Adaptive Language Model-based Digital Twin that can accurately simulate across diverse state-action spaces using in-context learning alone by utilising fine-tuned encoders for sample retrieval. We empirically demonstrate CALM-DT's competitive performance with existing digital twin approaches, and its unique ability to adapt to changes in its modelling environment without parameter updates.

[Arxiv](https://arxiv.org/abs/2506.12091)