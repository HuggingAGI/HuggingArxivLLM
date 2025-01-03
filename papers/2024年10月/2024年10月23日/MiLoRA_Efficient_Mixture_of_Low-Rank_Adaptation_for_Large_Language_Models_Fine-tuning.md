# MiLoRA: 大型语言模型微调的高效低秩适应混合方法

发布时间：2024年10月23日

`LLM应用` `人工智能` `云计算`

> MiLoRA: Efficient Mixture of Low-Rank Adaptation for Large Language Models Fine-tuning

# 摘要

> 低秩适应（LoRA）及其专家混合（MOE）变体是高效的参数微调方法，但在多租户环境中会因引入LoRA模块和MOE路由器而导致延迟增加。为此，我们提出了混合低秩适应（MiLoRA），一种创新的LoRA变体。MiLoRA将每个LoRA模块视为专家，并采用提示感知路由机制，在生成首个新令牌前计算路由结果并复用，从而降低延迟。实验表明，MiLoRA在常识推理、数学推理及LLM评估基准上表现优异，且在多租户环境中显著减少了延迟。

> Low-rank adaptation (LoRA) and its mixture-of-experts (MOE) variants are highly effective parameter-efficient fine-tuning (PEFT) methods. However, they introduce significant latency in multi-tenant settings due to the LoRA modules and MOE routers added to multiple linear modules in the Transformer layer. To address this issue, we propose Mixture of Low-Rank Adaptation (MiLoRA), a novel and efficient LoRA variant. MiLoRA differs from previous MOE-style LoRA methods by considering each LoRA module as an expert and employing a prompt-aware routing mechanism. This mechanism calculates expert routing results once before generating the first new token and reuses these results for subsequent tokens, reducing latency. Extensive experiments and analysis on commonsense reasoning tasks, math reasoning tasks, and widely used LLM evaluation benchmarks demonstrate that MiLoRA consistently outperforms strong PEFT baselines with comparable tunable parameter budgets. Additionally, MiLoRA significantly reduces latency in multi-tenant settings compared to previous LoRA-based methods.

[Arxiv](https://arxiv.org/abs/2410.18035)