# LightDefense: 通过偏移分词分布实现轻量级的不确定性驱动防御，有效对抗越狱攻击

发布时间：2025年04月02日

`LLM理论

摘要主要讨论了大型语言模型（LLMs）的安全性问题，特别是越狱提示攻击的防御机制。论文提出了一种新的轻量级防御方法，涉及模型内部的调整和策略，属于模型理论层面的改进。` `人工智能安全` `模型安全`

> LightDefense: A Lightweight Uncertainty-Driven Defense against Jailbreaks via Shifted Token Distribution

# 摘要

> 大型语言模型（LLMs）正面临越狱提示攻击的威胁。现有防御方法主要依赖辅助模型，但这些方法通常需要大量数据收集或训练。我们提出了一种轻量级防御机制——LightDefense，专为白盒模型设计。该机制通过安全导向方向调整词汇表中令牌的概率，使安全免责声明在按概率降序排列后出现在顶级令牌中。我们还创新性地利用LLM对提示的不确定性来衡量其危害性，并自适应地调整防御强度，有效平衡了安全性和有用性。LightDefense在防御2个目标LLM上的5种攻击方法时表现出色，同时未损害对良性用户查询的有用性，这凸显了其作为新型轻量级防御机制的潜力，有助于提升LLMs的安全性。

> Large Language Models (LLMs) face threats from jailbreak prompts. Existing methods for defending against jailbreak attacks are primarily based on auxiliary models. These strategies, however, often require extensive data collection or training. We propose LightDefense, a lightweight defense mechanism targeted at white-box models, which utilizes a safety-oriented direction to adjust the probabilities of tokens in the vocabulary, making safety disclaimers appear among the top tokens after sorting tokens by probability in descending order. We further innovatively leverage LLM's uncertainty about prompts to measure their harmfulness and adaptively adjust defense strength, effectively balancing safety and helpfulness. The effectiveness of LightDefense in defending against 5 attack methods across 2 target LLMs, without compromising helpfulness to benign user queries, highlights its potential as a novel and lightweight defense mechanism, enhancing security of LLMs.

[Arxiv](https://arxiv.org/abs/2504.01533)