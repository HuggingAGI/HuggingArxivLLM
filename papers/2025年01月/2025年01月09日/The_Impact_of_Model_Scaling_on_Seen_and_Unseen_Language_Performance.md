# 模型扩展对已知与未知语言表现的影响

发布时间：2025年01月09日

`LLM理论

理由：这篇论文主要关注的是多语言大型语言模型（LLMs）在不同语言和模型规模下的性能表现，特别是其在文本分类和机器翻译任务中的扩展行为。研究通过系统分析不同规模的模型家族在零-shot和少-shot设置下的表现，探讨了模型规模、资源水平等因素对性能的影响。这些内容属于对LLM的理论性研究和分析，旨在深入理解LLM在多语言环境下的行为和性能，因此应归类为LLM理论。` `多语言处理`

> The Impact of Model Scaling on Seen and Unseen Language Performance

# 摘要

> 大型语言模型（LLMs）的迅猛发展，尤其是基于多语言语料库训练的模型，使得深入理解其在多种语言和模型规模下的性能变得尤为重要。我们的研究聚焦于多语言LLMs在204种语言的文本分类和机器翻译任务中的表现与扩展行为。我们系统分析了不同规模的三个模型家族在零-shot和少-shot设置下对已见和未见语言的处理能力。研究发现，零-shot与两-shot场景下的扩展行为差异显著，已见与未见语言间的性能差距尤为突出。模型规模对零-shot性能影响甚微，性能基本持平；但在两-shot设置中，较大模型在多语言文本分类上展现出明显的线性提升。对于翻译任务，仅指令调优模型受益于规模扩展。此外，分析指出，总体资源水平而非预训练语言比例，更能预测模型性能，这为理解多语言LLM的有效性提供了新视角。

> The rapid advancement of Large Language Models (LLMs), particularly those trained on multilingual corpora, has intensified the need for a deeper understanding of their performance across a diverse range of languages and model sizes. Our research addresses this critical need by studying the performance and scaling behavior of multilingual LLMs in text classification and machine translation tasks across 204 languages. We systematically examine both seen and unseen languages across three model families of varying sizes in zero-shot and few-shot settings. Our findings show significant differences in scaling behavior between zero-shot and two-shot scenarios, with striking disparities in performance between seen and unseen languages. Model scale has little effect on zero-shot performance, which remains mostly flat. However, in two-shot settings, larger models show clear linear improvements in multilingual text classification. For translation tasks, however, only the instruction-tuned model showed clear benefits from scaling. Our analysis also suggests that overall resource levels, not just the proportions of pretraining languages, are better predictors of model performance, shedding light on what drives multilingual LLM effectiveness.

[Arxiv](https://arxiv.org/abs/2501.05629)