# PanelTR：基于多智能体科学讨论的零样本表格推理框架

发布时间：2025年08月08日

`LLM应用` `数据处理`

> PanelTR: Zero-Shot Table Reasoning Framework Through Multi-Agent Scientific Discussion

# 摘要

> 表格推理，包括表格问答和事实核查，往往依赖于标注数据或复杂的数据增强，这限制了其灵活性和泛化能力。尽管大型语言模型（LLMs）功能多样，但在这些任务中表现不如简单的监督模型。为了解决这些问题，我们提出了PanelTR框架，该框架通过LLM代理科学家采用结构化的科学方法实现稳健的表格推理。PanelTR的工作流程包括代理科学家进行个体调查、自我评审以及参与协作性的同行评审讨论。这一过程由五种科学家角色驱动，能够在不依赖数据增强或参数优化的情况下实现语义层面的迁移。在四个基准上的实验结果表明，PanelTR不仅超越了普通LLMs的表现，还与完全监督的模型相媲美，同时保持了对训练数据的独立性。我们的研究结果表明，结构化的科学方法能够通过灵活的语义理解有效处理超越表格推理的复杂任务，在零样本情境下表现优异。

> Table reasoning, including tabular QA and fact verification, often depends on annotated data or complex data augmentation, limiting flexibility and generalization. LLMs, despite their versatility, often underperform compared to simple supervised models. To approach these issues, we introduce PanelTR, a framework utilizing LLM agent scientists for robust table reasoning through a structured scientific approach. PanelTR's workflow involves agent scientists conducting individual investigations, engaging in self-review, and participating in collaborative peer-review discussions. This process, driven by five scientist personas, enables semantic-level transfer without relying on data augmentation or parametric optimization. Experiments across four benchmarks show that PanelTR outperforms vanilla LLMs and rivals fully supervised models, all while remaining independent of training data. Our findings indicate that structured scientific methodology can effectively handle complex tasks beyond table reasoning with flexible semantic understanding in a zero-shot context.

[Arxiv](https://arxiv.org/abs/2508.06110)