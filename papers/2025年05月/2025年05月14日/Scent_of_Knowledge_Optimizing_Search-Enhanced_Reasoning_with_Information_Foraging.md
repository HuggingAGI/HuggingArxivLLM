# 知识的芬芳：利用信息觅食优化搜索辅助推理能力

发布时间：2025年05月14日

`RAG` `问答系统`

> Scent of Knowledge: Optimizing Search-Enhanced Reasoning with Information Foraging

# 摘要

> 通过外部检索增强大型语言模型（LLMs）已成为解决其知识截止限制的标准方法。然而，传统检索增强生成方法采用静态预推理检索策略，难以应对复杂任务。近期推理时扩展技术的进展展示了LLMs动态与外部工具交互的潜力，推动了自适应推理时检索的转变。受信息觅食理论（IFT）启发，我们提出InForage——一个强化学习框架，将检索增强推理形式化为动态信息获取过程。与现有方法不同，InForage通过奖励中间检索质量，鼓励LLMs通过自适应搜索行为迭代收集和整合信息。为促进训练，我们构建了一个基于人工引导的数据集，记录了复杂真实世界网络任务中的迭代搜索和推理轨迹。在通用问答、多跳推理任务以及新开发的实时网络问答数据集上的广泛评估表明，InForage在性能上优于基线方法。这些结果凸显了InForage在构建健壮、自适应和高效推理代理方面的有效性。

> Augmenting large language models (LLMs) with external retrieval has become a standard method to address their inherent knowledge cutoff limitations. However, traditional retrieval-augmented generation methods employ static, pre-inference retrieval strategies, making them inadequate for complex tasks involving ambiguous, multi-step, or evolving information needs. Recent advances in test-time scaling techniques have demonstrated significant potential in enabling LLMs to dynamically interact with external tools, motivating the shift toward adaptive inference-time retrieval. Inspired by Information Foraging Theory (IFT), we propose InForage, a reinforcement learning framework that formalizes retrieval-augmented reasoning as a dynamic information-seeking process. Unlike existing approaches, InForage explicitly rewards intermediate retrieval quality, encouraging LLMs to iteratively gather and integrate information through adaptive search behaviors. To facilitate training, we construct a human-guided dataset capturing iterative search and reasoning trajectories for complex, real-world web tasks. Extensive evaluations across general question answering, multi-hop reasoning tasks, and a newly developed real-time web QA dataset demonstrate InForage's superior performance over baseline methods. These results highlight InForage's effectiveness in building robust, adaptive, and efficient reasoning agents.

[Arxiv](https://arxiv.org/abs/2505.09316)