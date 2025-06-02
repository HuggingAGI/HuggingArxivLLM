# # 微调 SLM 还是提示 LLM？生成低代码工作流的探讨

发布时间：2025年05月29日

`LLM应用` `结构化输出` `低代码工作流`

> Fine-Tune an SLM or Prompt an LLM? The Case of Generating Low-Code Workflows

# 摘要

> 大型语言模型 (LLMs) 如 GPT-4o 可通过适当提示处理多种复杂任务。随着按token成本的降低，微调小型语言模型 (SLMs) 在实际应用中的优势——推理速度快、成本低——可能不再显著。本研究发现，对于需要结构化输出的领域特定任务，SLMs 仍具质量优势。我们通过比较微调 SLM 与提示 LLMs 在生成 JSON 格式低代码工作流任务中的表现，发现虽然优秀提示可产生合理结果，但微调平均提升质量 10%。我们还进行了系统性错误分析，揭示了模型的局限性。

> Large Language Models (LLMs) such as GPT-4o can handle a wide range of complex tasks with the right prompt. As per token costs are reduced, the advantages of fine-tuning Small Language Models (SLMs) for real-world applications -- faster inference, lower costs -- may no longer be clear. In this work, we present evidence that, for domain-specific tasks that require structured outputs, SLMs still have a quality advantage. We compare fine-tuning an SLM against prompting LLMs on the task of generating low-code workflows in JSON form. We observe that while a good prompt can yield reasonable results, fine-tuning improves quality by 10% on average. We also perform systematic error analysis to reveal model limitations.

[Arxiv](https://arxiv.org/abs/2505.24189)