# 上下文提示的进化：一种开放式的自我复制视角

发布时间：2025年06月22日

`LLM应用` `人工智能`

> Evolving Prompts In-Context: An Open-ended, Self-replicating Perspective

# 摘要

> 我们提出了一种全新的提示设计范式，挑战传统大型语言模型（LLM）提示方法的核心理念。传统观点认为，精心设计的指令和演示是上下文学习（ICL）成功的关键，但我们发现，将随机的演示内容修剪成看似杂乱无章的“胡言乱语”，反而能够在多种任务中实现性能的显著提升。令人惊讶的是，这种“胡言乱语”式的提示方式不仅能够达到，甚至超越现有最先进自动提示优化技术的效果，且这种提升在不同对齐程度的LLM中均表现显著。然而，找到有效的修剪策略并非易事，现有归因方法和提示压缩算法难以提供可靠的结果，遑论依赖人类直觉。针对这一挑战，我们提出了一种名为PromptQuine的自我发现提示优化框架——一种进化搜索框架，仅通过低数据模式即可自动寻优。就像自然界中因资源限制而产生的复杂现象（如共生与自组织），我们的框架通过充分利用上下文中可用的标记，进化并优化出非传统却极为有效的提示方案。我们在分类、多选问答、文本生成和数学推理等多种任务中验证了PromptQuine的有效性，并实现了高效的运行时性能。我们希望这一发现不仅能够为上下文学习的机制研究提供新的视角，更能激发更多创新，为开发更高效的LLM提示策略铺平道路。

> We propose a novel prompt design paradigm that challenges conventional wisdom in large language model (LLM) prompting. While conventional wisdom prioritizes well-crafted instructions and demonstrations for in-context learning (ICL), we show that pruning random demonstrations into seemingly incoherent "gibberish" can remarkably improve performance across diverse tasks. Notably, the "gibberish" always matches or surpasses state-of-the-art automatic prompt optimization techniques, achieving substantial gains regardless of LLM alignment. Nevertheless, discovering an effective pruning strategy is non-trivial, as existing attribution methods and prompt compression algorithms fail to deliver robust results, let alone human intuition. In terms of this, we propose a self-discover prompt optimization framework, PromptQuine, an evolutionary search framework that automatically searches for the pruning strategy by itself using only low-data regimes. Much like the emergent complexity in nature--such as symbiosis and self-organization--arising in response to resource constraints, our framework evolves and refines unconventional yet highly effective prompts by leveraging only the tokens present within the context. We demonstrate its effectiveness across classification, multi-choice question answering, generation and math reasoning tasks across LLMs, while achieving decent runtime efficiency. We hope our findings can guide mechanistic studies on in-context learning, and provide a call to action, to pave the way for more open-ended search algorithms for more effective LLM prompting.

[Arxiv](https://arxiv.org/abs/2506.17930)