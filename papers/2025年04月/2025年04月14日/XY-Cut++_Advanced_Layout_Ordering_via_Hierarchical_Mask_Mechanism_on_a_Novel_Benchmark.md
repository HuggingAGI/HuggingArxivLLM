# XY-Cut++：在新型基准测试中通过层次化掩码机制实现的高级版式排序

发布时间：2025年04月14日

`RAG` `文档图像处理`

> XY-Cut++: Advanced Layout Ordering via Hierarchical Mask Mechanism on a Novel Benchmark

# 摘要

> 文档阅读顺序恢复是文档图像理解中的基础任务，对提升检索增强生成（RAG）效果至关重要，同时也是大型语言模型（LLMs）处理前的关键步骤。现有方法在处理复杂布局（如多栏报纸）、跨模态元素（视觉区域与文本语义）的高开销交互以及缺乏稳健评估基准方面存在诸多挑战。为此，我们推出了XY-Cut++，一种集预掩码处理、多粒度分割和跨模态匹配于一体的先进布局排序方法。与传统XY-Cut技术相比，XY-Cut++显著提升了布局排序的准确性。具体而言，它不仅达到了最先进的性能水平（整体BLEU分数为98.8），还相较现有基线方法提升了高达24%的性能。在新引入的DocBench-100数据集上，XY-Cut++在简单和复杂布局中均展现了高度一致的准确性。这一突破为文档结构恢复奠定了可靠基础，为布局排序任务树立了新标准，同时为更高效的RAG和LLM预处理提供了助力。

> Document Reading Order Recovery is a fundamental task in document image understanding, playing a pivotal role in enhancing Retrieval-Augmented Generation (RAG) and serving as a critical preprocessing step for large language models (LLMs). Existing methods often struggle with complex layouts(e.g., multi-column newspapers), high-overhead interactions between cross-modal elements (visual regions and textual semantics), and a lack of robust evaluation benchmarks. We introduce XY-Cut++, an advanced layout ordering method that integrates pre-mask processing, multi-granularity segmentation, and cross-modal matching to address these challenges. Our method significantly enhances layout ordering accuracy compared to traditional XY-Cut techniques. Specifically, XY-Cut++ achieves state-of-the-art performance (98.8 BLEU overall) while maintaining simplicity and efficiency. It outperforms existing baselines by up to 24\% and demonstrates consistent accuracy across simple and complex layouts on the newly introduced DocBench-100 dataset. This advancement establishes a reliable foundation for document structure recovery, setting a new standard for layout ordering tasks and facilitating more effective RAG and LLM preprocessing.

[Arxiv](https://arxiv.org/abs/2504.10258)