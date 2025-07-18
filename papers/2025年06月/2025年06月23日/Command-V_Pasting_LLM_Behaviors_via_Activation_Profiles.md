# Command-V：利用激活配置文件粘贴LLM行为模式

发布时间：2025年06月23日

`LLM应用` `人工智能` `模型迁移`

> Command-V: Pasting LLM Behaviors via Activation Profiles

# 摘要

> 对大型语言模型 (LLMs) 进行功能升级，通常需要耗时耗力的完整微调或蒸馏过程，这些步骤需要为每个架构重复执行。在本研究中，我们推出了一种创新方法 Command-V，这是一种无需反向传播的行为迁移技术。它通过从供体模型中复制现有的残差激活适配器，并将其效果无缝整合到受体模型中，实现行为的快速迁移。Command-V 通过分析小规模提示集合的层激活，推导出对应层之间的线性转换器，并在受体模型的激活空间中应用供体模型的干预。这一过程无需访问原始训练数据，且计算需求极低。在安全性拒绝增强、越狱功能促进和自动链式推理这三个实际案例中，Command-V 不仅达到了直接微调的效果，甚至在某些情况下表现更优，同时仅需微调所需计算资源的极小部分。我们的代码和数据已在 GitHub 上开放，方便研究和实践。

> Retrofitting large language models (LLMs) with new behaviors typically requires full finetuning or distillation-costly steps that must be repeated for every architecture. In this work, we introduce Command-V, a backpropagation-free behavior transfer method that copies an existing residual activation adapter from a donor model and pastes its effect into a recipient model. Command-V profiles layer activations on a small prompt set, derives linear converters between corresponding layers, and applies the donor intervention in the recipient's activation space. This process does not require access to the original training data and needs minimal compute. In three case studies-safety-refusal enhancement, jailbreak facilitation, and automatic chain-of-thought reasoning--Command-V matches or exceeds the performance of direct finetuning while using orders of magnitude less compute. Our code and data are accessible at https://github.com/GithuBarry/Command-V/.

[Arxiv](https://arxiv.org/abs/2506.19140)