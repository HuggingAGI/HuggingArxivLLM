# Command-V：借助激活配置文件复制LLM行为模式

发布时间：2025年06月23日

`LLM应用` `人工智能` `模型优化`

> Command-V: Pasting LLM Behaviors via Activation Profiles

# 摘要

> 通常，要在大型语言模型（LLMs）中添加新行为，需要进行完整的微调或蒸馏，这些步骤成本高昂且必须为每个架构重复执行。在本研究中，我们引入了Command-V，这是一种无需反向传播的行为转移方法，它从供体模型中复制现有的残差激活适配器，并将其效果粘贴到受体模型中。Command-V在小提示集上分析层激活，推导出对应层之间的线性转换器，并在受体模型的激活空间中应用供体模型的干预。这一过程无需访问原始训练数据，且计算需求极低。在三个案例研究中——安全拒绝增强、越狱辅助和自动链式推理——Command-V的表现与直接微调相当甚至更优，同时计算资源消耗少得多。我们的代码和数据可在https://github.com/GithuBarry/Command-V/获取。

> Retrofitting large language models (LLMs) with new behaviors typically requires full finetuning or distillation-costly steps that must be repeated for every architecture. In this work, we introduce Command-V, a backpropagation-free behavior transfer method that copies an existing residual activation adapter from a donor model and pastes its effect into a recipient model. Command-V profiles layer activations on a small prompt set, derives linear converters between corresponding layers, and applies the donor intervention in the recipient's activation space. This process does not require access to the original training data and needs minimal compute. In three case studies-safety-refusal enhancement, jailbreak facilitation, and automatic chain-of-thought reasoning--Command-V matches or exceeds the performance of direct finetuning while using orders of magnitude less compute. Our code and data are accessible at https://github.com/GithuBarry/Command-V/.

[Arxiv](https://arxiv.org/abs/2506.19140)