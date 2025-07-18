# 韩桥：通过汉字增强预训练消除韩语大语言模型的语义歧义

发布时间：2025年07月14日

`LLM应用

分类理由：这篇论文提出了一种新的技术（HanjaBridge）来解决大型语言模型在韩语处理中的问题，特别是同形词的语义消歧。该技术被集成到持续预训练框架中，并通过实验验证了其有效性，显著提升了模型在韩语任务中的表现。因此，这篇论文属于LLM应用类别，因为它专注于改进大型语言模型在特定语言和任务中的实际应用效果。` `语言技术`

> HanjaBridge: Resolving Semantic Ambiguity in Korean LLMs via Hanja-Augmented Pre-Training

# 摘要

> 大型语言模型在韩语等低资源语言中表现欠佳，部分原因在于韩语中存在发音相同但意义不同的汉字词无法区分的难题。为了解决这一语义模糊问题，我们提出了HanjaBridge——一种集成到持续预训练框架中的新型意义注入技术。与传统方法不同，HanjaBridge为同形词提供所有可能的汉字候选，引导模型学习上下文消歧。这一过程配合基于token的知识蒸馏，防止模型遗忘已有知识。实验表明，HanjaBridge显著提升了韩语理解能力，使KoBALT基准测试的相对提升了21%。通过共享汉字强化韩语与汉语的语义对齐，我们还观察到了强烈的跨语言迁移效果。值得注意的是，即使在推理时省略汉字增强，这些改进依然显著，确保了实际应用中的高效性与无额外运行成本。

> Large language models (LLMs) often show poor performance in low-resource languages like Korean, partly due to unique linguistic challenges such as homophonous Sino-Korean words that are indistinguishable in Hangul script. To address this semantic ambiguity, we propose HanjaBridge, a novel meaning-injection technique integrated into a continual pre-training (CPT) framework. Instead of deterministically mapping a word to a single Hanja (Chinese character), HanjaBridge presents the model with all possible Hanja candidates for a given homograph, encouraging the model to learn contextual disambiguation. This process is paired with token-level knowledge distillation to prevent catastrophic forgetting. Experimental results show that HanjaBridge significantly improves Korean language understanding, achieving a 21\% relative improvement on the KoBALT benchmark. Notably, by reinforcing semantic alignment between Korean and Chinese through shared Hanja, we observe a strong positive cross-lingual transfer. Furthermore, these gains persist even when Hanja augmentation is omitted at inference time, ensuring practical efficiency with no additional run-time cost.

[Arxiv](https://arxiv.org/abs/2507.10920)