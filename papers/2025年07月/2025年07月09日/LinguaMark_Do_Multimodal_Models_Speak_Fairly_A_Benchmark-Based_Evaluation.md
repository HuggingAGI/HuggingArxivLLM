# LinguaMark：多模态模型能否公平表达？基于基准的评估

发布时间：2025年07月09日

`LLM应用` `计算机视觉`

> LinguaMark: Do Multimodal Models Speak Fairly? A Benchmark-Based Evaluation

# 摘要

> 大规模多模态模型（LMMs）通常基于庞大的图像-文本数据集进行训练，但它们在语言覆盖范围上往往存在局限性，导致跨语言输出存在偏见和不公平现象。尽管先前的研究探讨了多模态评估，但对多语言能力的评估关注较少。在本研究中，我们引入了LinguaMark，这是一个旨在评估当前最先进的LMMs在多语言视觉问答（VQA）任务中表现的基准测试。我们的数据集包含6,875个涵盖11种语言和五种社会属性的图像-文本对。我们采用三个关键指标来评估模型：偏见、答案相关性和忠实性。研究发现，闭源模型通常表现出最高的整体性能。无论是闭源模型（GPT-4o和Gemini2.5）还是开源模型（Gemma3、Qwen2.5），在社会属性方面都表现出较强的竞争性，而Qwen2.5在多种语言间展现出强大的泛化能力。我们公开了基准测试和评估代码，以促进研究的可重复性和进一步发展。

> Large Multimodal Models (LMMs) are typically trained on vast corpora of image-text data but are often limited in linguistic coverage, leading to biased and unfair outputs across languages. While prior work has explored multimodal evaluation, less emphasis has been placed on assessing multilingual capabilities. In this work, we introduce LinguaMark, a benchmark designed to evaluate state-of-the-art LMMs on a multilingual Visual Question Answering (VQA) task. Our dataset comprises 6,875 image-text pairs spanning 11 languages and five social attributes. We evaluate models using three key metrics: Bias, Answer Relevancy, and Faithfulness. Our findings reveal that closed-source models generally achieve the highest overall performance. Both closed-source (GPT-4o and Gemini2.5) and open-source models (Gemma3, Qwen2.5) perform competitively across social attributes, and Qwen2.5 demonstrates strong generalization across multiple languages. We release our benchmark and evaluation code to encourage reproducibility and further research.

[Arxiv](https://arxiv.org/abs/2507.07274)