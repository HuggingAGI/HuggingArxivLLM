# TransProQA：结合专业问答的基于 LLM 的文学翻译评估指标

发布时间：2025年05月08日

`LLM应用` `文学翻译` `文学评估`

> TransProQA: an LLM-based literary Translation evaluation metric with Professional Question Answering

# 摘要

> 大型语言模型 (LLMs) 的影响力已深入文学领域。然而，现有评估指标过分强调机械准确性，忽视了艺术表达的重要性，往往高估机器翻译 (MT) 超越专业人工翻译的能力。这种偏差若长期持续，可能导致翻译质量与文化真实性的永久性下滑。为应对开发专门文学评估指标的迫切需求，我们推出了 TransProQA —— 一个基于 LLM 的全新无参考问答 (QA) 框架，专为文学翻译评估设计。TransProQA 独特地整合了专业文学译者与研究人员的见解，聚焦于文学质量评估中的关键要素，包括文学手法、文化理解及作者语气。通过广泛评估，我们发现：尽管经过文学微调的 XCOMET-XL 有所改进，但 TransProQA 的表现远超现有指标，相关性 (ACC-EQ 和 Kendall's tau) 提升达 0.07，在充足性评估中领先最佳现先进 (SOTA) 指标 15 余分。将专业译者见解作为权重纳入，进一步提升了性能，凸显了译者输入的价值。值得注意的是，TransProQA 的评估表现已接近人类水平，可与受过训练的语言标注员相媲美。它广泛适用于开源模型如 LLaMA3.3-70b 和 Qwen2.5-32b，表明其作为便捷、无需训练的文学评估指标的潜力，以及在需要本地处理因版权或伦理考量文本时的宝贵工具价值。

> The impact of Large Language Models (LLMs) has extended into literary domains. However, existing evaluation metrics prioritize mechanical accuracy over artistic expression and tend to overrate machine translation (MT) as being superior to experienced professional human translation. In the long run, this bias could result in a permanent decline in translation quality and cultural authenticity. In response to the urgent need for a specialized literary evaluation metric, we introduce TransProQA, a novel, reference-free, LLM-based question-answering (QA) framework designed specifically for literary translation evaluation. TransProQA uniquely integrates insights from professional literary translators and researchers, focusing on critical elements in literary quality assessment such as literary devices, cultural understanding, and authorial voice. Our extensive evaluation shows that while literary-finetuned XCOMET-XL yields marginal gains, TransProQA substantially outperforms current metrics, achieving up to 0.07 gain in correlation (ACC-EQ and Kendall's tau) and surpassing the best state-of-the-art (SOTA) metrics by over 15 points in adequacy assessments. Incorporating professional translator insights as weights further improves performance, highlighting the value of translator inputs. Notably, TransProQA approaches human-level evaluation performance comparable to trained linguistic annotators. It demonstrates broad applicability to open-source models such as LLaMA3.3-70b and Qwen2.5-32b, indicating its potential as an accessible and training-free literary evaluation metric and a valuable tool for evaluating texts that require local processing due to copyright or ethical considerations.

[Arxiv](https://arxiv.org/abs/2505.05423)