# 对比研究：抽取式摘要模型在临床放射学报告中的性能分析

发布时间：2025年06月19日

`LLM应用` `文本摘要`

> Comparative Analysis of Abstractive Summarization Models for Clinical Radiology Reports

# 摘要

> 放射科报告的发现部分通常内容详尽且篇幅较长，而印象部分则更为简洁，提炼出关键诊断结论。本研究旨在探索利用先进的抽取式摘要模型，将放射科报告的发现部分转化为简洁的印象总结。我们采用了公开的MIMIC-CXR数据集，并对包括T5-base、BART-base、PEGASUS-x-base、ChatGPT-4、LLaMA-3-8B以及带覆盖机制的自定义指针生成网络在内的多款领先预训练开源大型语言模型进行了对比分析。为了确保全面评估，采用了ROUGE-1、ROUGE-2、ROUGE-L、METEOR和BERTScore等多种评价指标。通过分析这些模型的表现，本研究揭示了它们在医学文本摘要任务中的各自优势与局限性。本文的研究发现为医疗领域需要自动化摘要解决方案的医学专业人士提供了有价值的参考。


> The findings section of a radiology report is often detailed and lengthy, whereas the impression section is comparatively more compact and captures key diagnostic conclusions. This research explores the use of advanced abstractive summarization models to generate the concise impression from the findings section of a radiology report. We have used the publicly available MIMIC-CXR dataset. A comparative analysis is conducted on leading pre-trained and open-source large language models, including T5-base, BART-base, PEGASUS-x-base, ChatGPT-4, LLaMA-3-8B, and a custom Pointer Generator Network with a coverage mechanism. To ensure a thorough assessment, multiple evaluation metrics are employed, including ROUGE-1, ROUGE-2, ROUGE-L, METEOR, and BERTScore. By analyzing the performance of these models, this study identifies their respective strengths and limitations in the summarization of medical text. The findings of this paper provide helpful information for medical professionals who need automated summarization solutions in the healthcare sector.

[Arxiv](https://arxiv.org/abs/2506.16247)