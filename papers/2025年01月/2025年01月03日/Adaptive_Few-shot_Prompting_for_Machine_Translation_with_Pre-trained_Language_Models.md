# 基于预训练语言模型的自适应少样本提示机器翻译

发布时间：2025年01月03日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）在神经机器翻译领域的应用。具体来说，论文提出了一种自适应少样本提示（AFSP）框架，通过自动选择翻译示例来优化LLM的翻译能力。这涉及到LLM的嵌入层、检索模块以及生成和重新排序目标语言输出的过程。这些内容都属于LLM在实际应用中的优化和改进，因此归类为“LLM应用”。` `机器翻译`

> Adaptive Few-shot Prompting for Machine Translation with Pre-trained Language Models

# 摘要

> 最近，具备上下文学习能力的大型语言模型（LLMs）在神经机器翻译领域展现了巨大潜力。然而，现有研究表明，LLMs对提示词敏感，固定提示词难以适应所有输入，导致机器翻译效果欠佳。为此，我们提出了一种自适应少样本提示（AFSP）框架，能够自动为不同源输入句子选择合适的翻译示例，从而更好地激发LLM的翻译能力。首先，我们基于LLM的嵌入构建了一个翻译示例检索模块，从对齐的平行语料库中检索出前k个语义相似的翻译示例。与使用其他嵌入模型不同，我们基于部署的LLM的嵌入层构建了混合检索模块，以生成更优的输入表示，从而检索出更多语义相关的翻译示例。接着，为了确保源输入与目标输出之间的语义一致性，我们强制LLM在翻译示例的辅助下生成多个目标语言的输出候选，并对这些候选进行重新排序。此外，为了评估AFSP框架在最新语言上的效果并拓展神经机器翻译的研究边界，我们构建了一个高质量的外交中英平行数据集，包含5,528个中英平行句子。最后，在外交中英平行数据集和联合国平行语料库（中英部分）上的大量实验验证了AFSP框架的有效性和优越性。

> Recently, Large language models (LLMs) with in-context learning have demonstrated remarkable potential in handling neural machine translation. However, existing evidence shows that LLMs are prompt-sensitive and it is sub-optimal to apply the fixed prompt to any input for downstream machine translation tasks. To address this issue, we propose an adaptive few-shot prompting (AFSP) framework to automatically select suitable translation demonstrations for various source input sentences to further elicit the translation capability of an LLM for better machine translation. First, we build a translation demonstration retrieval module based on LLM's embedding to retrieve top-k semantic-similar translation demonstrations from aligned parallel translation corpus. Rather than using other embedding models for semantic demonstration retrieval, we build a hybrid demonstration retrieval module based on the embedding layer of the deployed LLM to build better input representation for retrieving more semantic-related translation demonstrations. Then, to ensure better semantic consistency between source inputs and target outputs, we force the deployed LLM itself to generate multiple output candidates in the target language with the help of translation demonstrations and rerank these candidates. Besides, to better evaluate the effectiveness of our AFSP framework on the latest language and extend the research boundary of neural machine translation, we construct a high-quality diplomatic Chinese-English parallel dataset that consists of 5,528 parallel Chinese-English sentences. Finally, extensive experiments on the proposed diplomatic Chinese-English parallel dataset and the United Nations Parallel Corpus (Chinese-English part) show the effectiveness and superiority of our proposed AFSP.

[Arxiv](https://arxiv.org/abs/2501.01679)