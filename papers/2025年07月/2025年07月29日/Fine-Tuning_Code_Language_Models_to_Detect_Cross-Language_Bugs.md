# 微调代码语言模型，精准识别跨语言漏洞

发布时间：2025年07月29日

`LLM应用

理由：这篇论文探讨了预训练代码语言模型（CodeLMs）在检测跨语言缺陷（CLBs）中的应用。研究者们构建了一个跨语言缺陷数据集，分析了不同模型在微调后的性能表现。虽然涉及模型微调和性能分析，但核心是将LLM应用于具体的代码分析任务，属于LLM的应用研究。` `跨语言`

> Fine-Tuning Code Language Models to Detect Cross-Language Bugs

# 摘要

> 多语言编程因其优势而越来越普遍，但同时也带来了跨语言缺陷（CLBs）。本文研究了预训练代码语言模型（CodeLMs）在 CLB 检测中的潜力。我们开发了跨语言代码识别工具 CLCFinder，并构建了一个涉及三种语言组合及九种交互类型的 CLB 数据集。我们在该数据集上微调了 13 个 CodeLMs，分析了数据集大小、标记序列长度和代码注释的影响。结果显示，所有 CodeLMs 在微调前表现不佳，但微调后不同程度地提高了性能，其中 UniXcoder-base 达到了最佳 F1 分数（0.7407）。值得注意的是，微调后的较小规模 CodeLMs 通常表现优于大规模模型。在单一语言缺陷数据集上微调的 CodeLMs 在 CLB 检测中表现较差，表明 CLBs 与单一语言缺陷的不同。此外，增加微调数据集的大小显著提升了性能，而较长的标记序列并不一定改善模型表现。不同模型对代码注释的影响反应各异。某些微调后的 CodeLMs 性能提升，而另一些则表现下降。

> Multilingual programming, which involves using multiple programming languages (PLs) in a single project, is increasingly common due to its benefits. However, it introduces cross-language bugs (CLBs), which arise from interactions between different PLs and are difficult to detect by single-language bug detection tools. This paper investigates the potential of pre-trained code language models (CodeLMs) in CLB detection. We developed CLCFinder, a cross-language code identification tool, and constructed a CLB dataset involving three PL combinations (Python-C/C++, Java-C/C++, and Python-Java) with nine interaction types. We fine-tuned 13 CodeLMs on this dataset and evaluated their performance, analyzing the effects of dataset size, token sequence length, and code comments. Results show that all CodeLMs performed poorly before fine-tuning, but exhibited varying degrees of performance improvement after fine-tuning, with UniXcoder-base achieving the best F1 score (0.7407). Notably, small fine-tuned CodeLMs tended to performe better than large ones. CodeLMs fine-tuned on single-language bug datasets performed poorly on CLB detection, demonstrating the distinction between CLBs and single-language bugs. Additionally, increasing the fine-tuning dataset size significantly improved performance, while longer token sequences did not necessarily improve the model performance. The impact of code comments varied across models. Some fine-tuned CodeLMs' performance was improved, while others showed degraded performance.

[Arxiv](https://arxiv.org/abs/2507.21954)