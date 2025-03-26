# # 宪法式 AI 在小型 LLM 中的效果如何？以 DeepSeek-R1 为例的研究

发布时间：2025年02月01日

`LLM应用

摘要讨论了大型语言模型（LLMs）的安全风险，并探讨了宪法人工智能（CAI）的自我批评机制在小型模型中的应用。研究结果表明，这些机制可以有效减少危害，但效果因模型而异。这属于将LLM应用于提升安全性，因此归类为LLM应用。` `模型安全` `对齐技术`

> How Effective Is Constitutional AI in Small LLMs? A Study on DeepSeek-R1 and Its Peers

# 摘要

> 近期的事件凸显了大型语言模型（LLMs）的安全风险，推动了对宪法人工智能（CAI）等对齐方法的研究。本文探讨了CAI的自我批评机制在小型、未经过滤的7-9B参数模型上的应用：DeepSeek-R1、Gemma-2、Llama 3.1和Qwen2.5。通过HarmBench测试，我们发现所有模型均展现了通过自我批评减少危害的能力，但效果差异显著，其中DeepSeek-R1凭借其明确的推理过程取得了更优的结果。这些发现表明，受CAI启发的提示策略可以提升资源受限模型的安全性，但其成功依赖于模型检测危害的能力。

> Recent incidents highlight safety risks in Large Language Models (LLMs), motivating research into alignment methods like Constitutional AI (CAI). This paper explores CAI's self-critique mechanism on small, uncensored 7-9B parameter models: DeepSeek-R1, Gemma-2, Llama 3.1, and Qwen2.5. Using HarmBench, we demonstrate that while all models showed capacity for harm reduction through self-critique, effectiveness varied significantly, with DeepSeek-R1's explicit reasoning process yielding superior results. These findings suggest that CAI-inspired prompting strategies can enhance safety in resource-constrained models, though success depends on the model's capacity for harm detection.

[Arxiv](https://arxiv.org/abs/2503.17365)