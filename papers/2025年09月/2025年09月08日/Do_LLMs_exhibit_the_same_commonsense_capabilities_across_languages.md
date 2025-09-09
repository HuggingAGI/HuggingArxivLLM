# 大型语言模型（LLMs）跨语言是否具备相同的常识能力？

发布时间：2025年09月08日

`LLM应用` `基础理论`

> Do LLMs exhibit the same commonsense capabilities across languages?

# 摘要

> 本文研究了大型语言模型（LLMs）的多语言常识生成能力。为此，我们构建了全新基准MULTICOM，将COCOTEROS数据集扩展至英语、西班牙语、荷兰语和巴伦西亚语四种语言。该任务要求生成一个包含给定三元组词语的符合常识的句子。我们在这一基准上评估了LLaMA、Qwen、Gemma、EuroLLM和Salamandra等一系列开源LLM，评估方法结合了自动指标、LLM评判法（使用Prometheus和JudgeLM）及人工标注。结果一致表明，模型在英语上表现优异，而在资源较少的语言上表现明显逊色。尽管上下文支持的效果参差不齐，但它通常对代表性不足的语言有所助益。这些发现突显了当前LLM在多语言常识生成方面的局限性。该数据集可通过https://huggingface.co/datasets/gplsi/MULTICOM公开获取。

> This paper explores the multilingual commonsense generation abilities of Large Language Models (LLMs). To facilitate this investigation, we introduce MULTICOM, a novel benchmark that extends the COCOTEROS dataset to four languages: English, Spanish, Dutch, and Valencian. The task involves generating a commonsensical sentence that includes a given triplet of words. We evaluate a range of open-source LLMs, including LLaMA, Qwen, Gemma, EuroLLM, and Salamandra, on this benchmark. Our evaluation combines automatic metrics, LLM-as-a-judge approaches (using Prometheus and JudgeLM), and human annotations. Results consistently show superior performance in English, with significantly lower performance in less-resourced languages. While contextual support yields mixed results, it tends to benefit underrepresented languages. These findings underscore the current limitations of LLMs in multilingual commonsense generation. The dataset is publicly available at https://huggingface.co/datasets/gplsi/MULTICOM.

[Arxiv](https://arxiv.org/abs/2509.06401)