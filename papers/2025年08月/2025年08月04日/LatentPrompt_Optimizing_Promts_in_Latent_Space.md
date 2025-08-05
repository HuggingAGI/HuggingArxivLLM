# # 潜在提示：优化提示的潜在空间方法

发布时间：2025年08月04日

`LLM应用` `金融分析`

> LatentPrompt: Optimizing Promts in Latent Space

# 摘要

> 最近研究发现，优化大型语言模型（LLMs）的提示能显著提升任务效果，但现有优化方法多依赖启发式策略或手动探索。我们推出LatentPrompt——一个无需特定模型的提示优化框架，它通过潜在语义空间自动完成候选提示的生成、评估与优化，完全摆脱了手动规则的束缚。该方法从一组初始提示出发，将其映射至连续潜在空间中，系统性探索以寻找最优提示，从而最大化任务表现。在金融语料库情感分类基准测试中，LatentPrompt仅需一次优化循环，分类准确率便提升了约3%。这一框架应用广泛，只需黑盒访问LLM并结合自动评估指标，适用于各类领域与任务。

> Recent advances have shown that optimizing prompts for Large Language Models (LLMs) can significantly improve task performance, yet many optimization techniques rely on heuristics or manual exploration. We present LatentPrompt, a model-agnostic framework for prompt optimization that leverages latent semantic space to automatically generate, evaluate, and refine candidate prompts without requiring hand-crafted rules. Beginning with a set of seed prompts, our method embeds them in a continuous latent space and systematically explores this space to identify prompts that maximize task-specific performance. In a proof-of-concept study on the Financial PhraseBank sentiment classification benchmark, LatentPrompt increased classification accuracy by approximately 3 percent after a single optimization cycle. The framework is broadly applicable, requiring only black-box access to an LLM and an automatic evaluation metric, making it suitable for diverse domains and tasks.

[Arxiv](https://arxiv.org/abs/2508.02452)