# 差异何在？通过Token模式解析提示与模型变化的影响

发布时间：2025年04月22日

`LLM应用` `提示工程` `模型评估`

> What's the Difference? Supporting Users in Identifying the Effects of Prompt and Model Changes Through Token Patterns

# 摘要

> 大语言模型的提示工程充满挑战，因为即使是微小的提示调整或模型变更，也可能显著影响生成文本。现有的自动化指标或人工评估方法都存在不足，要么见解有限，要么耗时费力。我们提出了Spotlight，一种结合自动化与人工分析的新方法。通过数据挖掘技术，我们能够自动区分语言模型输出中的随机变化与系统性差异。这一过程提取出描述系统性差异的标记模式，指导用户高效分析提示和模型变更的影响。我们设计了三个基准测试，验证了标记模式提取方法的可靠性，并展示了我们的方法如何为现有提示数据带来新见解。从以人为本的视角，通过演示研究和用户研究，我们证明了Spotlight方法如何帮助用户理解模型输出的系统性差异，发现由提示或模型变更引发的相关差异（如性别或文化相关的内容），从而支持提示工程和以人为本的模型行为研究。

> Prompt engineering for large language models is challenging, as even small prompt perturbations or model changes can significantly impact the generated output texts. Existing evaluation methods, either automated metrics or human evaluation, have limitations, such as providing limited insights or being labor-intensive. We propose Spotlight, a new approach that combines both automation and human analysis. Based on data mining techniques, we automatically distinguish between random (decoding) variations and systematic differences in language model outputs. This process provides token patterns that describe the systematic differences and guide the user in manually analyzing the effects of their prompt and model changes efficiently. We create three benchmarks to quantitatively test the reliability of token pattern extraction methods and demonstrate that our approach provides new insights into established prompt data. From a human-centric perspective, through demonstration studies and a user study, we show that our token pattern approach helps users understand the systematic differences of language model outputs, and we are able to discover relevant differences caused by prompt and model changes (e.g. related to gender or culture), thus supporting the prompt engineering process and human-centric model behavior research.

[Arxiv](https://arxiv.org/abs/2504.15815)