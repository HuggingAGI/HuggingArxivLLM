# LIFT：长输入微调助力大型语言模型理解长上下文

发布时间：2025年02月20日

`LLM理论` `模型优化`

> LIFT: Improving Long Context Understanding of Large Language Models through Long Input Fine-Tuning

# 摘要

> 长上下文理解一直是大语言模型的难题，主要受限于其有限的上下文窗口。本文提出了一种全新的长上下文建模框架——长输入微调（LIFT）。通过动态调整模型参数以适应长输入，LIFT能够有效提升任意短上下文大语言模型的长上下文处理能力。与不断扩展上下文窗口以适应更长输入的传统方法不同，LIFT选择将长输入存储并融入模型参数中。通过将长输入微调到模型参数中，LIFT赋予了短上下文大语言模型在推理时即使未提供所需上下文信息仍能回答问题的能力。此外，为了在保持原有上下文学习（ICL）能力的同时进一步提升LIFT的性能，我们引入了门控记忆（Gated Memory），一种专门设计的注意力适配器，能够自动平衡长输入记忆与ICL之间的关系。我们对LIFT在长上下文理解方面的优势与局限性进行了全面分析，为未来研究提供了宝贵的指导方向。


> Long context understanding remains challenging for large language models due to their limited context windows. This paper presents Long Input Fine-Tuning (LIFT), a novel framework for long-context modeling that can improve the long-context performance of arbitrary (short-context) LLMs by dynamically adapting model parameters based on the long input. Importantly, LIFT, rather than endlessly extending the context window size to accommodate increasingly longer inputs in context, chooses to store and absorb the long input in parameter. By fine-tuning the long input into model parameters, LIFT allows short-context LLMs to answer questions even when the required information is not provided in the context during inference. Furthermore, to enhance LIFT performance while maintaining the original in-context learning (ICL) capabilities, we introduce Gated Memory, a specialized attention adapter that automatically balances long input memorization and ICL. We provide a comprehensive analysis of the strengths and limitations of LIFT on long context understanding, offering valuable directions for future research.

[Arxiv](https://arxiv.org/abs/2502.14644)