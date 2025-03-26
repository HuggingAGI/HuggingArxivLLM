# 大型语言模型输出的一致性和可重复性评估：基于多样化的财务与会计任务

发布时间：2025年03月21日

`LLM应用`

> Assessing Consistency and Reproducibility in the Outputs of Large Language Models: Evidence Across Diverse Finance and Accounting Tasks

# 摘要

> 本研究首次全面考察了大型语言模型 (LLM) 在金融与会计研究中的输出一致性与可重复性。通过大规模实验，我们在分类、情感分析、摘要、文本生成和预测等五项常见任务中进行了 50 次独立运行，评估 LLM 的输出一致性。使用 GPT-3.5-turbo、GPT-4o-mini 和 GPT-4o 三个 OpenAI 模型，从包括管理层讨论与分析、联邦公开市场委员会声明、财经新闻文章、 earnings call 会议纪要和财务报表在内的多样化财务数据源中，生成了超过 340 万的输出结果。

研究发现，LLM 的输出一致性显著但因任务而异：二元分类和情感分析实现了近乎完美的可重复性，而复杂任务的变异性较大。值得注意的是，更高级的模型并不总是表现出更好的一致性和可重复性，且呈现出任务特定的模式。在一致性方面，LLM 远超人工标注专家，并在人类专家意见分歧显著的情况下仍保持高度一致。通过 3-5 次运行的简单聚合策略，可显著提升输出的一致性。

模拟分析表明，尽管 LLM 输出存在可测量的不一致性，但下游统计推断仍表现出惊人的稳健性。这些发现回应了我们所谓的“G-hacking”担忧，即从多次生成式 AI 运行中选择性报告有利结果的风险在金融与会计任务中相对较低。

> This study provides the first comprehensive assessment of consistency and reproducibility in Large Language Model (LLM) outputs in finance and accounting research. We evaluate how consistently LLMs produce outputs given identical inputs through extensive experimentation with 50 independent runs across five common tasks: classification, sentiment analysis, summarization, text generation, and prediction. Using three OpenAI models (GPT-3.5-turbo, GPT-4o-mini, and GPT-4o), we generate over 3.4 million outputs from diverse financial source texts and data, covering MD&As, FOMC statements, finance news articles, earnings call transcripts, and financial statements. Our findings reveal substantial but task-dependent consistency, with binary classification and sentiment analysis achieving near-perfect reproducibility, while complex tasks show greater variability. More advanced models do not consistently demonstrate better consistency and reproducibility, with task-specific patterns emerging. LLMs significantly outperform expert human annotators in consistency and maintain high agreement even where human experts significantly disagree. We further find that simple aggregation strategies across 3-5 runs dramatically improve consistency. Simulation analysis reveals that despite measurable inconsistency in LLM outputs, downstream statistical inferences remain remarkably robust. These findings address concerns about what we term "G-hacking," the selective reporting of favorable outcomes from multiple Generative AI runs, by demonstrating that such risks are relatively low for finance and accounting tasks.

[Arxiv](https://arxiv.org/abs/2503.16974)