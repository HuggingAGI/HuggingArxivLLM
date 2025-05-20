# Shadow-FT：基于 Base 的 Instruct 调整方法

发布时间：2025年05月19日

`LLM理论

摘要主要讨论了大型语言模型的微调方法，提出了一种新的框架Shadow-FT，用于优化模型训练，属于模型理论层面的探讨。` `软件工程` `人工智能`

> Shadow-FT: Tuning Instruct via Base

# 摘要

> 大型语言模型（LLMs）在各种任务上进行进一步微调时始终受益。然而，直接微调INSTRUCT模型通常只会带来微小改进，甚至导致性能下降。值得注意的是，与这些INSTRUCT变体对应的BASE模型具有高度相似的权重值（例如，Llama 3.1 8B的平均差异小于2%）。因此，我们提出了一种新型的Shadow-FT框架，通过利用对应的BASE模型来微调INSTRUCT模型。关键思想是先微调BASE模型，然后将学习到的权重更新直接移植到INSTRUCT模型中。我们的Shadow-FT框架不引入额外参数，易于实现，并显著提升性能。我们在主流LLMs（如Qwen 3和Llama 3系列）上进行了广泛的实验，并在涵盖编码、推理和数学任务的19个基准测试中进行评估。实验结果表明，Shadow-FT在大多数情况下优于传统的全参数和参数高效微调方法。进一步分析表明，Shadow-FT可以应用于多模态大型语言模型（MLLMs），并与其他优化方法（如直接偏好优化DPO）结合使用。代码和权重可在\href{https://github.com/wutaiqiang/Shadow-FT}{Github}获取。

> Large language models (LLMs) consistently benefit from further fine-tuning on various tasks. However, we observe that directly tuning the INSTRUCT (i.e., instruction tuned) models often leads to marginal improvements and even performance degeneration. Notably, paired BASE models, the foundation for these INSTRUCT variants, contain highly similar weight values (i.e., less than 2% on average for Llama 3.1 8B). Therefore, we propose a novel Shadow-FT framework to tune the INSTRUCT models by leveraging the corresponding BASE models. The key insight is to fine-tune the BASE model, and then directly graft the learned weight updates to the INSTRUCT model. Our proposed Shadow-FT introduces no additional parameters, is easy to implement, and significantly improves performance. We conduct extensive experiments on tuning mainstream LLMs, such as Qwen 3 and Llama 3 series, and evaluate them across 19 benchmarks covering coding, reasoning, and mathematical tasks. Experimental results demonstrate that Shadow-FT consistently outperforms conventional full-parameter and parameter-efficient tuning approaches. Further analyses indicate that Shadow-FT can be applied to multimodal large language models (MLLMs) and combined with direct preference optimization (DPO). Codes and weights are available at \href{https://github.com/wutaiqiang/Shadow-FT}{Github}.

[Arxiv](https://arxiv.org/abs/2505.12716)