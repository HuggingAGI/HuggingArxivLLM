# SPRI: 大型语言模型与上下文情境原则的对齐

发布时间：2025年02月05日

`LLM应用

理由：这篇论文主要讨论了如何通过提出的Situated-PRInciples（SPRI）框架来改进大型语言模型（LLMs）在复杂任务中的表现，特别是在与人类价值观对齐方面。SPRI框架能够实时生成指导原则，并利用这些原则来对齐模型响应，从而提升模型在复杂领域任务中的表现。这属于LLM在实际应用中的改进和优化，因此归类为LLM应用。` `人工智能`

> SPRI: Aligning Large Language Models with Context-Situated Principles

# 摘要

> # 摘要
将大型语言模型（LLMs）与人类价值观对齐，尤其是在需要复杂人类监督的任务中，既费时又费力。先前的研究通过预定义规则或原则来引导模型行为（Bai et al., 2022; Sun et al., 2023），但这些原则往往过于通用，难以适应具体情境。为此，我们提出了Situated-PRInciples（SPRI）框架，该框架几乎无需人工干预，能够为每个输入查询实时生成指导原则，并利用这些原则对齐模型响应。我们在三个任务上验证了SPRI的效果：1）SPRI在复杂领域任务中生成的原则与专家制定的原则表现相当；2）SPRI生成的原则能够创建实例特定的评分标准，优于现有的LLM-as-a-judge框架；3）使用SPRI生成合成SFT数据显著提升了模型真实性。代码和模型生成结果已开源：https://github.com/honglizhan/SPRI-public。

> Aligning Large Language Models to integrate and reflect human values, especially for tasks that demand intricate human oversight, is arduous since it is resource-intensive and time-consuming to depend on human expertise for context-specific guidance. Prior work has utilized predefined sets of rules or principles to steer the behavior of models (Bai et al., 2022; Sun et al., 2023). However, these principles tend to be generic, making it challenging to adapt them to each individual input query or context. In this work, we present Situated-PRInciples (SPRI), a framework requiring minimal or no human effort that is designed to automatically generate guiding principles in real-time for each input query and utilize them to align each response. We evaluate SPRI on three tasks, and show that 1) SPRI can derive principles in a complex domain-specific task that leads to on-par performance as expert-crafted ones; 2) SPRI-generated principles lead to instance-specific rubrics that outperform prior LLM-as-a-judge frameworks; 3) using SPRI to generate synthetic SFT data leads to substantial improvement on truthfulness. We release our code and model generations at https://github.com/honglizhan/SPRI-public.

[Arxiv](https://arxiv.org/abs/2502.03397)