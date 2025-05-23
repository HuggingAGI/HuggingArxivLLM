# 日期片段：分词中隐藏的时间推理瓶颈

发布时间：2025年05月21日

`LLM应用` `时间推理`

> Date Fragments: A Hidden Bottleneck of Tokenization for Temporal Reasoning

# 摘要

> 现代BPE分词器常将日期拆分成毫无意义的片段，例如，20250312 → 202, 503, 12，这不仅增加分词数量，还模糊了进行稳健时间推理所需的结构。本研究（1）提出了一种简单易懂的指标——日期碎片化比率，用于衡量分词器对多位数日期组件的保留程度；（2）发布了DateAugBench，一套包含6500个示例的基准测试套件，涵盖基于上下文的日期解析、格式不变性难题以及跨越历史、当代和未来时域的日期运算；（3）通过逐层探查和因果注意力跳跃分析，揭示了大型语言模型中一种新兴的日期抽象机制，可将月份、日期和年份的碎片组件重新组合用于时间推理。实验表明，过度碎片化会导致罕见日期（如历史和未来日期）的准确率下降多达10个百分点。此外，模型规模越大，修复日期碎片的抽象机制完成得越快。最后，我们发现大型语言模型在组装日期碎片时的推理路径通常与人类不同（年→月→日）。

> Modern BPE tokenizers often split calendar dates into meaningless fragments, e.g., 20250312 $\rightarrow$ 202, 503, 12, inflating token counts and obscuring the inherent structure needed for robust temporal reasoning. In this work, we (1) introduce a simple yet interpretable metric, termed date fragmentation ratio, that measures how faithfully a tokenizer preserves multi-digit date components; (2) release DateAugBench, a suite of 6500 examples spanning three temporal reasoning tasks: context-based date resolution, format-invariance puzzles, and date arithmetic across historical, contemporary, and future regimes; and (3) through layer-wise probing and causal attention-hop analyses, uncover an emergent date-abstraction mechanism whereby large language models stitch together the fragments of month, day, and year components for temporal reasoning. Our experiments show that excessive fragmentation correlates with accuracy drops of up to 10 points on uncommon dates like historical and futuristic dates. Further, we find that the larger the model, the faster the emergent date abstraction that heals date fragments is accomplished. Lastly, we observe a reasoning path that LLMs follow to assemble date fragments, typically differing from human interpretation (year $\rightarrow$ month $\rightarrow$ day).

[Arxiv](https://arxiv.org/abs/2505.16088)