# 关于 LLM、NMT 模型及其组合在波斯语 - 英语习语翻译中的比较研究

发布时间：2024年12月13日

`LLM应用` `机器翻译` `语言模型`

> A Comparative Study of LLMs, NMT Models, and Their Combination in Persian-English Idiom Translation

# 摘要

> 大型语言模型（LLMs）在比喻性语言的翻译上展现出了比神经机器翻译（NMT）系统更强的能力。然而，不同的提示方法以及LLM-NMT的组合对于习语翻译的影响尚未被深入探究。本文引入了两个并行的数据集，分别包含波斯语$ightarrow$英语和英语$ightarrow$波斯语的含习语表达的句子，其中波斯习语从我们的PersianIdioms资源中抽取，该资源集合了2200个习语及其释义。借助这些数据集，我们对各种开源和闭源的LLMs、NMT模型及其组合进行了评估。通过习语翻译的准确度和流畅度来衡量翻译质量。我们还发现，像LLM-as-a-judge、BLEU和BERTScore这类自动评估方法在比较模型性能的不同方面颇为有效。我们的实验显示，Claude-3.5-Sonnet在两个翻译方向上均成果斐然。对于英语$ightarrow$波斯语的翻译，将较弱的LLMs与谷歌翻译相结合能提升效果，而波斯语$ightarrow$英语的翻译中，简单模型受益于单一提示，高级模型则得益于复杂提示。

> Large language models (LLMs) have shown superior capabilities in translating figurative language compared to neural machine translation (NMT) systems. However, the impact of different prompting methods and LLM-NMT combinations on idiom translation has yet to be thoroughly investigated. This paper introduces two parallel datasets of sentences containing idiomatic expressions for Persian$\rightarrow$English and English$\rightarrow$Persian translations, with Persian idioms sampled from our PersianIdioms resource, a collection of 2,200 idioms and their meanings. Using these datasets, we evaluate various open- and closed-source LLMs, NMT models, and their combinations. Translation quality is assessed through idiom translation accuracy and fluency. We also find that automatic evaluation methods like LLM-as-a-judge, BLEU and BERTScore are effective for comparing different aspects of model performance. Our experiments reveal that Claude-3.5-Sonnet delivers outstanding results in both translation directions. For English$\rightarrow$Persian, combining weaker LLMs with Google Translate improves results, while Persian$\rightarrow$English translations benefit from single prompts for simpler models and complex prompts for advanced ones.

[Arxiv](https://arxiv.org/abs/2412.09993)