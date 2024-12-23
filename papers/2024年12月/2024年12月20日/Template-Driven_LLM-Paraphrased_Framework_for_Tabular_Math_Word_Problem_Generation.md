# 用于表格数学文字问题生成的模板驱动的 LLM 改写框架

发布时间：2024年12月20日

`LLM应用`

> Template-Driven LLM-Paraphrased Framework for Tabular Math Word Problem Generation

# 摘要

> 解决表格数学文字问题（TMWPs）已成为评估大型语言模型（LLMs）数学推理能力的关键，通常需要大规模的 TMWP 样本用于 LLM 微调。然而，高质量 TMWP 数据集的收集既费钱又耗时，所以近期研究聚焦于自动生成 TMWP。但当前生成的样本往往在正确性或多样性上存在问题。本文提出了一个模板驱动的 LLM 改写（TeLL）框架，用于生成具有不同背景、准确的表格、问题、答案和解决方案的高质量 TMWP 样本。首先，从现有真实样本中提取模板生成初始问题，保证正确性。接着，利用 LLM 扩展模板并改写问题，获取多样的 TMWP 样本。另外，我们发现推理注释对解决 TMWPs 至关重要。因此，建议为每个解决方案增添具有说明性的推理步骤。通过这个框架，我们依照 TabMWP 数据集中的问题类型构建了高质量的数据集 TabMWP-TeLL，并在多种 LLM 上开展了大量实验，以证明 TabMWP-TeLL 在提升 TMWP 解决性能方面的有效性。本文的代码和数据可在：https://github.com/Jason8Kang/TELL 获取。

> Solving tabular math word problems (TMWPs) has become a critical role in evaluating the mathematical reasoning ability of large language models (LLMs), where large-scale TMWP samples are commonly required for LLM fine-tuning. Since the collection of high-quality TMWP datasets is costly and time-consuming, recent research has concentrated on automatic TMWP generation. However, current generated samples usually suffer from issues of either correctness or diversity. In this paper, we propose a Template-driven LLM-paraphrased (TeLL) framework for generating high-quality TMWP samples with diverse backgrounds and accurate tables, questions, answers, and solutions. To this end, we first extract templates from existing real samples to generate initial problems, ensuring correctness. Then, we adopt an LLM to extend templates and paraphrase problems, obtaining diverse TMWP samples. Furthermore, we find the reasoning annotation is important for solving TMWPs. Therefore, we propose to enrich each solution with illustrative reasoning steps. Through the proposed framework, we construct a high-quality dataset TabMWP-TeLL by adhering to the question types in the TabMWP dataset, and we conduct extensive experiments on a variety of LLMs to demonstrate the effectiveness of TabMWP-TeLL in improving TMWP solving performance. The code and data of this paper are available at: https://github.com/Jason8Kang/TELL.

[Arxiv](https://arxiv.org/abs/2412.15594)