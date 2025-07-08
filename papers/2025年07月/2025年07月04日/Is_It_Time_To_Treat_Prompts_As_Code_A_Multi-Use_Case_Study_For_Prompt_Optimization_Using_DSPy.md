# 是否该将提示词视为代码？使用DSPy的多案例研究探索提示优化

发布时间：2025年07月04日

`LLM应用` `提示工程` `提示优化`

> Is It Time To Treat Prompts As Code? A Multi-Use Case Study For Prompt Optimization Using DSPy

# 摘要

> 尽管提示工程是释放大型语言模型（LLMs）全部潜力的核心，但设计有效的提示仍然是一项耗时且依赖直觉的试错工作。本研究探讨了声明式自改进Python框架（DSPy），这是一种通过程序化方式创建和优化提示的优化框架，并将其应用于五个用例：护栏机制执行、代码中的幻觉检测、代码生成、路由代理以及提示评估。每个用例均考察了通过DSPy进行提示优化对性能的影响。虽然某些用例仅显示出小幅改进——例如护栏机制用例中的微小提升，以及幻觉检测中的部分优化——但其他用例则展现了显著的优势。在提示评估标准任务中，性能大幅提升，准确率从46.2%跃升至64.0%。在路由代理用例中，研究探讨了通过优化提示提升表现不佳的提示以及使较小模型通过优化提示匹敌更强模型的可能性。尽管提示优化使准确率从85.0%提升至90.0%，但使用优化提示的较便宜模型并未带来性能提升。总体而言，本研究结果表明，DSPy的系统化提示优化能够提升LLM性能，尤其在指令微调和示例选择同时得到优化时效果更为显著。然而，不同任务的影响程度不同，凸显了在提示优化研究中评估具体用例的重要性。


> Although prompt engineering is central to unlocking the full potential of Large Language Models (LLMs), crafting effective prompts remains a time-consuming trial-and-error process that relies on human intuition. This study investigates Declarative Self-improving Python (DSPy), an optimization framework that programmatically creates and refines prompts, applied to five use cases: guardrail enforcement, hallucination detection in code, code generation, routing agents, and prompt evaluation. Each use case explores how prompt optimization via DSPy influences performance. While some cases demonstrated modest improvements - such as minor gains in the guardrails use case and selective enhancements in hallucination detection - others showed notable benefits. The prompt evaluation criterion task demonstrated a substantial performance increase, rising accuracy from 46.2% to 64.0%. In the router agent case, the possibility of improving a poorly performing prompt and of a smaller model matching a stronger one through optimized prompting was explored. Although prompt refinement increased accuracy from 85.0% to 90.0%, using the optimized prompt with a cheaper model did not improve performance. Overall, this study's findings suggest that DSPy's systematic prompt optimization can enhance LLM performance, particularly when instruction tuning and example selection are optimized together. However, the impact varies by task, highlighting the importance of evaluating specific use cases in prompt optimization research.

[Arxiv](https://arxiv.org/abs/2507.03620)