# # 重写预训练数据，助力大语言模型在数学与代码领域更上一层楼

发布时间：2025年05月05日

`LLM应用` `程序合成` `数学推理`

> Rewriting Pre-Training Data Boosts LLM Performance in Math and Code

# 摘要

> 大型语言模型（LLMs）在程序合成和数学推理中的表现受制于预训练语料的质量。我们开源了两个数据集，基于Llama 3.3社区许可，通过系统性重写公开数据，显著提升了模型性能。SwallowCode（约161亿token）采用四阶段管道从The-Stack-v2精炼Python代码：语法验证、pylint风格筛选，以及两阶段LLM重写，确保代码风格一致并转化为高效、自包含的示例。与传统方法不同，我们的转换策略通过升级低质代码，最大化数据价值。SwallowMath（约230亿token）通过去除模板、恢复上下文并重新格式化解决方案为简明的逐步解释，优化了Finemath-4+。在固定5000亿token预算下，使用SwallowCode持续预训练Llama-3.1-8B，使HumanEval和HumanEval+的pass@1分别提升+17.0和+17.7，超越了基线模型的代码生成能力。SwallowMath在GSM8K和MATH上的准确率分别提升了+12.4和+7.6。消融实验表明，每阶段管道均带来增量提升，重写过程贡献最大。所有数据集、提示和检查点均已公开，助力可重复研究，并推动LLM在专业领域的预训练发展。

> The performance of large language models (LLMs) in program synthesis and mathematical reasoning is fundamentally limited by the quality of their pre-training corpora. We introduce two openly licensed datasets, released under the Llama 3.3 Community License, that significantly enhance LLM performance by systematically rewriting public data. SwallowCode (approximately 16.1 billion tokens) refines Python snippets from The-Stack-v2 through a novel four-stage pipeline: syntax validation, pylint-based style filtering, and a two-stage LLM rewriting process that enforces style conformity and transforms snippets into self-contained, algorithmically efficient examples. Unlike prior methods that rely on exclusionary filtering or limited transformations, our transform-and-retain approach upgrades low-quality code, maximizing data utility. SwallowMath (approximately 2.3 billion tokens) enhances Finemath-4+ by removing boilerplate, restoring context, and reformatting solutions into concise, step-by-step explanations. Within a fixed 50 billion token training budget, continual pre-training of Llama-3.1-8B with SwallowCode boosts pass@1 by +17.0 on HumanEval and +17.7 on HumanEval+ compared to Stack-Edu, surpassing the baseline model's code generation capabilities. Similarly, substituting SwallowMath yields +12.4 accuracy on GSM8K and +7.6 on MATH. Ablation studies confirm that each pipeline stage contributes incrementally, with rewriting delivering the largest gains. All datasets, prompts, and checkpoints are publicly available, enabling reproducible research and advancing LLM pre-training for specialized domains.

[Arxiv](https://arxiv.org/abs/2505.02881)