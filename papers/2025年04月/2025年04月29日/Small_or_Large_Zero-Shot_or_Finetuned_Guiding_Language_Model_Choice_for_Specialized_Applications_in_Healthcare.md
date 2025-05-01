# 小模型还是大模型？零样本还是微调？——在医疗领域选择专业应用的语言模型时的指南

发布时间：2025年04月29日

`LLM应用`

> Small or Large? Zero-Shot or Finetuned? Guiding Language Model Choice for Specialized Applications in Healthcare

# 摘要

> 本研究旨在通过以下四个关键问题指导语言模型的选择：1) 微调与零样本使用之间的必要性，2) 领域相邻模型与通用预训练模型的益处，3) 进一步领域特定预训练的价值，4) 小型语言模型（SLMs）与大型语言模型（LLMs）在特定任务中的持续相关性。研究使用来自不列颠哥伦比亚癌症登记处（BCCR）的电子病理报告，评估了三个难度和数据规模各不相同的分类场景。实验涵盖了多种SLMs和一个LLM。SLMs在零样本和微调两种情况下接受评估；LLM仅在零样本情况下进行评估。结果显示，与零样本结果相比，微调显著提升了SLMs在所有场景中的性能。零样本LLM的表现优于零样本SLMs，但始终逊色于微调后的SLMs。经过微调后，领域相邻的SLMs通常表现优于通用SLMs，尤其在更复杂的任务中。进一步的领域特定预训练在较简单的任务中带来了适度的提升，但在复杂且数据稀缺的任务中取得了显著改进。研究结果突显了微调在专业领域中对SLMs的重要性，使其能够在特定分类任务上超越零样本LLM的表现。在领域相邻或特定领域数据上的预训练提供了进一步的优势，特别是在复杂问题或有限微调数据的情况下。尽管LLMs提供了强大的零样本能力，但它们在这些特定任务上的表现并未达到适当微调的SLMs水平。在LLMs时代，SLMs仍然具有相关性和有效性，与LLMs相比，它们提供了可能更优的性能-资源权衡。

> This study aims to guide language model selection by investigating: 1) the necessity of finetuning versus zero-shot usage, 2) the benefits of domain-adjacent versus generic pretrained models, 3) the value of further domain-specific pretraining, and 4) the continued relevance of Small Language Models (SLMs) compared to Large Language Models (LLMs) for specific tasks. Using electronic pathology reports from the British Columbia Cancer Registry (BCCR), three classification scenarios with varying difficulty and data size are evaluated. Models include various SLMs and an LLM. SLMs are evaluated both zero-shot and finetuned; the LLM is evaluated zero-shot only. Finetuning significantly improved SLM performance across all scenarios compared to their zero-shot results. The zero-shot LLM outperformed zero-shot SLMs but was consistently outperformed by finetuned SLMs. Domain-adjacent SLMs generally performed better than the generic SLM after finetuning, especially on harder tasks. Further domain-specific pretraining yielded modest gains on easier tasks but significant improvements on the complex, data-scarce task. The results highlight the critical role of finetuning for SLMs in specialized domains, enabling them to surpass zero-shot LLM performance on targeted classification tasks. Pretraining on domain-adjacent or domain-specific data provides further advantages, particularly for complex problems or limited finetuning data. While LLMs offer strong zero-shot capabilities, their performance on these specific tasks did not match that of appropriately finetuned SLMs. In the era of LLMs, SLMs remain relevant and effective, offering a potentially superior performance-resource trade-off compared to LLMs.

[Arxiv](https://arxiv.org/abs/2504.21191)