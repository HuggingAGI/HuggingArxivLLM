# LLMs擅长文本变音符标注吗？以阿拉伯语和约鲁巴语为例

发布时间：2025年06月13日

`LLM应用` `多语言`

> Are LLMs Good Text Diacritizers? An Arabic and Yorùbá Case Study

# 摘要

> 我们研究了大型语言模型（LLMs）在阿拉伯语和约鲁巴语中的文本变音符号恢复效果。为进行严谨评估，我们引入了一个全新的多语言数据集MultiDiac，包含多样化的样本以捕捉各种变音符号歧义。我们评估了14种不同规模、可访问性和语言覆盖范围的LLMs，并与6种专用变音符号恢复模型进行了对比。此外，我们使用LoRA对四个小型开源模型进行了微调，用于约鲁巴语。结果显示，许多现成LLMs在阿拉伯语和约鲁巴语中优于专用模型，但较小模型易产生幻觉。在小型数据集上微调可提升性能并降低幻觉率。

> We investigate the effectiveness of large language models (LLMs) for text diacritization in two typologically distinct languages: Arabic and Yoruba. To enable a rigorous evaluation, we introduce a novel multilingual dataset MultiDiac, with diverse samples that capture a range of diacritic ambiguities. We evaluate 14 LLMs varying in size, accessibility, and language coverage, and benchmark them against 6 specialized diacritization models. Additionally, we fine-tune four small open-source models using LoRA for Yoruba. Our results show that many off-the-shelf LLMs outperform specialized diacritization models for both Arabic and Yoruba, but smaller models suffer from hallucinations. Fine-tuning on a small dataset can help improve diacritization performance and reduce hallucination rates.

[Arxiv](https://arxiv.org/abs/2506.11602)