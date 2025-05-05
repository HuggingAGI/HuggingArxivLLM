# # LLM预训练数据中的公共访问范围之外

发布时间：2025年04月24日

`LLM应用` `版权保护` `人工智能`

> Beyond Public Access in LLM Pre-Training Data

# 摘要

> 我们利用一个包含34本受版权保护O'Reilly Media书籍的合法数据集，采用DE-COP成员推断攻击方法，探究OpenAI的大型语言模型是否未经许可使用了受版权保护的内容进行训练。实验结果显示，GPT-4o（OpenAI最新且功能更强的模型）在识别付费墙保护的O'Reilly书籍内容方面表现出色（AUROC=82%），而早期的GPT-3.5 Turbo则在公开获取的O'Reilly书籍样本上表现更为突出。相比之下，作为规模较小的模型，GPT-4o Mini在测试中对公开或非公开的O'Reilly Media内容均无明显认知（AUROC≈50%）。通过在同一截止日期下测试多个模型，我们能够更准确地分析语言随时间变化可能带来的偏差，从而确保研究结果的客观性。这些发现强调了企业提高预训练数据来源透明度的重要性，这将有助于为AI内容训练制定正式的许可框架。

> Using a legally obtained dataset of 34 copyrighted O'Reilly Media books, we apply the DE-COP membership inference attack method to investigate whether OpenAI's large language models were trained on copyrighted content without consent. Our AUROC scores show that GPT-4o, OpenAI's more recent and capable model, demonstrates strong recognition of paywalled O'Reilly book content (AUROC = 82\%), compared to OpenAI's earlier model GPT-3.5 Turbo. In contrast, GPT-3.5 Turbo shows greater relative recognition of publicly accessible O'Reilly book samples. GPT-4o Mini, as a much smaller model, shows no knowledge of public or non-public O'Reilly Media content when tested (AUROC $\approx$ 50\%). Testing multiple models, with the same cutoff date, helps us account for potential language shifts over time that might bias our findings. These results highlight the urgent need for increased corporate transparency regarding pre-training data sources as a means to develop formal licensing frameworks for AI content training

[Arxiv](https://arxiv.org/abs/2505.00020)