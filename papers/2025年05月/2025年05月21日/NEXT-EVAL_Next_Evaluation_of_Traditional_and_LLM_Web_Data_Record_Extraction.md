# NEXT-EVAL：传统方法与LLM网络数据记录提取的下一步评估

发布时间：2025年05月21日

`LLM应用` `数据科学` `信息抽取`

> NEXT-EVAL: Next Evaluation of Traditional and LLM Web Data Record Extraction

# 摘要

> 网页数据记录提取方法的有效评估至关重要，但现有评估手段因静态、领域特定的基准和不透明的评分实践而受到限制。这使得传统基于结构启发式的算法技术与能够跨多样化布局实现零样本提取的大型语言模型（LLM）方法之间的公平比较尤为具有挑战性。为突破这些限制，我们提出了一套具体的评估框架。

我们的框架通过以下方式系统地进行评估：
1. 从任意MHTML快照生成评估数据集
2. 标注基于XPath的监督标签
3. 采用感知结构的指标进行一致评分，特别防止文本生成幻觉，仅允许对位置幻觉进行评估
4. 通过HTML瘦身、层次JSON和扁平JSON等预处理策略优化LLM输入，同时保留DOM语义

此外，我们通过转换DOM结构和修改内容创建了一个公开可用的合成数据集。我们在多种输入格式上对确定性启发式算法和现成LLMs进行了全面基准测试。结果表明，与Slimmed HTML和Hierarchical JSON等其他输入格式相比，Flat JSON输入使LLMs能够实现更高的提取准确度（F1得分为0.9567）和最小的幻觉。

本研究为网页数据记录提取的严格基准测试奠定了标准化基础，为该领域的下一步合乎原理的进步铺平了道路。

> Effective evaluation of web data record extraction methods is crucial, yet hampered by static, domain-specific benchmarks and opaque scoring practices. This makes fair comparison between traditional algorithmic techniques, which rely on structural heuristics, and Large Language Model (LLM)-based approaches, offering zero-shot extraction across diverse layouts, particularly challenging. To overcome these limitations, we introduce a concrete evaluation framework. Our framework systematically generates evaluation datasets from arbitrary MHTML snapshots, annotates XPath-based supervision labels, and employs structure-aware metrics for consistent scoring, specifically preventing text hallucination and allowing only for the assessment of positional hallucination. It also incorporates preprocessing strategies to optimize input for LLMs while preserving DOM semantics: HTML slimming, Hierarchical JSON, and Flat JSON. Additionally, we created a publicly available synthetic dataset by transforming DOM structures and modifying content. We benchmark deterministic heuristic algorithms and off-the-shelf LLMs across these multiple input formats. Our benchmarking shows that Flat JSON input enables LLMs to achieve superior extraction accuracy (F1 score of 0.9567) and minimal hallucination compared to other input formats like Slimmed HTML and Hierarchical JSON. We establish a standardized foundation for rigorous benchmarking, paving the way for the next principled advancements in web data record extraction.

[Arxiv](https://arxiv.org/abs/2505.17125)