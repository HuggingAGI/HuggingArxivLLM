# # UltraEdit：零训练、零主题、零记忆的大型语言模型持续编辑

发布时间：2025年05月20日

`LLM理论` `模型编辑` `终身学习`

> UltraEdit: Training-, Subject-, and Memory-Free Lifelong Editing in Large Language Models

# 摘要

> 终身学习使大型语言模型 (LLMs) 能够通过持续更新内部知识来适应不断变化的信息。一个理想的系统应支持高效且广泛的更新，同时保留现有能力并确保可靠部署。模型编辑作为实现这一目标的有前途的解决方案，提供了一种专注且高效的方式来修订模型的内部知识。尽管最近的范式在这一领域取得了显著进展，但它们往往难以满足大规模实用终身适应的需求。为了解决这一差距，我们提出了ULTRAEDIT——一种全新的编辑解决方案，具有无训练、无主题、无内存需求的特点，特别适合于超大规模、现实世界的终身模型编辑。ULTRAEDIT通过仅依赖轻量级线性代数运算来计算参数偏移的自包含过程进行编辑，实现了快速且一致的参数修改，同时带来极小的开销。为了在终身学习环境中提高可扩展性，ULTRAEDIT采用了终身规范化策略，持续更新轮次间的特征统计，使其能够适应分布变化并保持一致性。ULTRAEDIT的编辑速度超过现有最佳方法7倍，同时仅消耗其三分之一的VRAM，使其成为目前唯一能够在24GB消费级GPU上编辑70亿参数LLM的方法。此外，我们构建了ULTRAEDITBENCH——目前为止最大的数据集，拥有超过200万的编辑对，并证明我们的方法在保持高精度的同时支持多达100万次编辑。在四个数据集和六个模型上的全面实验表明，ULTRAEDIT在各种模型编辑场景中始终展现出更优的性能。我们的代码可在以下链接获取：https://github.com/XiaojieGu/UltraEdit.

> Lifelong learning enables large language models (LLMs) to adapt to evolving information by continually updating their internal knowledge. An ideal system should support efficient, wide-ranging updates while preserving existing capabilities and ensuring reliable deployment. Model editing stands out as a promising solution for this goal, offering a focused and efficient way to revise a model's internal knowledge. Although recent paradigms have made notable progress, they often struggle to meet the demands of practical lifelong adaptation at scale. To bridge this gap, we propose ULTRAEDIT-a fundamentally new editing solution that is training-, subject- and memory-free, making it particularly well-suited for ultra-scalable, real-world lifelong model editing. ULTRAEDIT performs editing through a self-contained process that relies solely on lightweight linear algebra operations to compute parameter shifts, enabling fast and consistent parameter modifications with minimal overhead. To improve scalability in lifelong settings, ULTRAEDIT employs a lifelong normalization strategy that continuously updates feature statistics across turns, allowing it to adapt to distributional shifts and maintain consistency over time. ULTRAEDIT achieves editing speeds over 7x faster than the previous state-of-the-art method-which was also the fastest known approach-while consuming less than 1/3 the VRAM, making it the only method currently capable of editing a 7B LLM on a 24GB consumer-grade GPU. Furthermore, we construct ULTRAEDITBENCH-the largest dataset in the field to date, with over 2M editing pairs-and demonstrate that our method supports up to 1M edits while maintaining high accuracy. Comprehensive experiments on four datasets and six models show that ULTRAEDIT consistently achieves superior performance across diverse model editing scenarios. Our code is available at: https://github.com/XiaojieGu/UltraEdit.

[Arxiv](https://arxiv.org/abs/2505.14679)