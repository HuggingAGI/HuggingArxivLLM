# RapGuard: 利用理性感知的防御性提示守护多模态大型语言模型

发布时间：2024年12月25日

`LLM应用

理由：该论文主要讨论的是如何通过动态安全提示框架（RapGuard）来减少多模态大语言模型（MLLMs）生成有害内容的问题。这涉及到对现有LLM的应用进行改进和优化，以提高其在实际应用中的安全性和性能。因此，该论文应归类为LLM应用。` `人工智能` `内容安全`

> RapGuard: Safeguarding Multimodal Large Language Models via Rationale-aware Defensive Prompting

# 摘要

> 尽管多模态大语言模型（MLLMs）在视觉-语言推理领域取得了显著进展，但它们比纯文本模型更容易生成有害内容。现有的防御性提示技术依赖静态的统一安全指南，无法应对不同多模态场景中的特定风险。为此，我们提出了RapGuard，一个基于多模态链式思维推理的动态安全提示框架。RapGuard通过针对每个输入的独特风险生成定制化提示，有效减少有害输出，同时在良性任务上保持高性能。实验表明，RapGuard在多个MLLM基准测试中实现了顶尖的安全性能，显著降低了有害内容，且不影响响应质量。

> While Multimodal Large Language Models (MLLMs) have made remarkable progress in vision-language reasoning, they are also more susceptible to producing harmful content compared to models that focus solely on text. Existing defensive prompting techniques rely on a static, unified safety guideline that fails to account for the specific risks inherent in different multimodal contexts. To address these limitations, we propose RapGuard, a novel framework that uses multimodal chain-of-thought reasoning to dynamically generate scenario-specific safety prompts. RapGuard enhances safety by adapting its prompts to the unique risks of each input, effectively mitigating harmful outputs while maintaining high performance on benign tasks. Our experimental results across multiple MLLM benchmarks demonstrate that RapGuard achieves state-of-the-art safety performance, significantly reducing harmful content without degrading the quality of responses.

[Arxiv](https://arxiv.org/abs/2412.18826)