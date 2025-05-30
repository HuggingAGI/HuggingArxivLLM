# ContextQFormer: 面向多轮多模态对话的新型上下文建模方法

发布时间：2025年05月29日

`LLM应用` `多模态对话`

> ContextQFormer: A New Context Modeling Method for Multi-Turn Multi-Modal Conversations

# 摘要

> 多模态大型语言模型展现了出色的零样本能力和强大的图像理解能力。然而，现有开源模型在多轮交互，尤其是长上下文场景中表现较弱。为解决这一问题，我们引入了一个名为ContextQFormer的上下文建模模块，通过内存块增强上下文信息的表现。此外，为促进进一步研究，我们构建了一个全新的多轮多模态对话数据集TMDialog，用于预训练、指令微调和评估，该数据集即将开源。与其它多模态对话数据集相比，TMDialog包含更长的对话内容，为多轮多模态对话研究提供了支持。实验结果表明，ContextQFormer在TMDialog上与三个基线模型相比，可用率提升了2%-4%。

> Multi-modal large language models have demonstrated remarkable zero-shot abilities and powerful image-understanding capabilities. However, the existing open-source multi-modal models suffer from the weak capability of multi-turn interaction, especially for long contexts. To address the issue, we first introduce a context modeling module, termed ContextQFormer, which utilizes a memory block to enhance the presentation of contextual information. Furthermore, to facilitate further research, we carefully build a new multi-turn multi-modal dialogue dataset (TMDialog) for pre-training, instruction-tuning, and evaluation, which will be open-sourced lately. Compared with other multi-modal dialogue datasets, TMDialog contains longer conversations, which supports the research of multi-turn multi-modal dialogue. In addition, ContextQFormer is compared with three baselines on TMDialog and experimental results illustrate that ContextQFormer achieves an improvement of 2%-4% in available rate over baselines.

[Arxiv](https://arxiv.org/abs/2505.23121)