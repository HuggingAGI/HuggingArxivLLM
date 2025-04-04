# MegaMath：探索开放数学语料库的无限可能

发布时间：2025年04月03日

`LLM应用` `数据科学`

> MegaMath: Pushing the Limits of Open Math Corpora

# 摘要

> 数学推理是人类智能的基石，也是衡量大型语言模型（LLMs）高级能力的重要标准。然而，目前研究界仍缺乏一个专门针对数学导向LLM预训练需求的开放、大规模、高质量语料库。为此，我们推出了MegaMath，一个通过以下方法从多样化数学资源中精心整理的开放数据集：

(1) 重新审视网络数据：我们优化了Common Crawl的数学相关内容提取流程，通过HTML优化、fasttext过滤和去重技术，确保从互联网获取更高质量的数学文档。

(2) 回顾数学代码数据：我们从Stack-V2等大型代码训练语料库中筛选出高质量的数学相关代码，进一步丰富了数据多样性。

(3) 探索合成数据：我们巧妙结合网络数据和代码数据，生成问答式文本、数学相关代码以及交错的文本-代码块。

通过整合这些创新策略，并经过大量实验验证，MegaMath最终打造出了一个拥有3710亿个代币的高质量数学预训练数据集，无论是规模还是质量都远超现有同类数据集。


> Mathematical reasoning is a cornerstone of human intelligence and a key benchmark for advanced capabilities in large language models (LLMs). However, the research community still lacks an open, large-scale, high-quality corpus tailored to the demands of math-centric LLM pre-training. We present MegaMath, an open dataset curated from diverse, math-focused sources through following practices: (1) Revisiting web data: We re-extracted mathematical documents from Common Crawl with math-oriented HTML optimizations, fasttext-based filtering and deduplication, all for acquiring higher-quality data on the Internet. (2) Recalling Math-related code data: We identified high quality math-related code from large code training corpus, Stack-V2, further enhancing data diversity. (3) Exploring Synthetic data: We synthesized QA-style text, math-related code, and interleaved text-code blocks from web data or code data. By integrating these strategies and validating their effectiveness through extensive ablations, MegaMath delivers 371B tokens with the largest quantity and top quality among existing open math pre-training datasets.

[Arxiv](https://arxiv.org/abs/2504.02807)