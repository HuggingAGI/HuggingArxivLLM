# # 语言多样性对翻译任务中微调大型语言模型的影响
语言多样性在微调大型语言模型用于翻译任务时对模型性能有显著影响。

发布时间：2025年05月19日

`LLM理论` `机器翻译`

> The Effect of Language Diversity When Fine-Tuning Large Language Models for Translation

# 摘要

> 关于 LLM 微调中的语言多样性，先前研究结果不一：有的发现其优势，有的则未见显著效果。我们通过 132 个翻译方向的受控微调实验，系统性地解决了这一分歧。实验表明，增加微调过程中的语言多样性能够提升无监督和 -- 惊人的是 -- 有监督翻译对的翻译质量，尽管这些有监督翻译对本身语言多样性较低。然而，当语言多样性超过某个阈值时，优势会趋于平稳甚至下降。我们发现，语言多样性的增加能够生成更多语言无关的表示形式。这些表示形式的适应性变化有助于解释为何多样性更高的微调模型性能更佳。

> Prior research diverges on language diversity in LLM fine-tuning: Some studies report benefits while others find no advantages. Through controlled fine-tuning experiments across 132 translation directions, we systematically resolve these disparities. We find that expanding language diversity during fine-tuning improves translation quality for both unsupervised and -- surprisingly -- supervised pairs, despite less diverse models being fine-tuned exclusively on these supervised pairs. However, benefits plateau or decrease beyond a certain diversity threshold. We show that increased language diversity creates more language-agnostic representations. These representational adaptations help explain the improved performance in models fine-tuned with greater diversity.

[Arxiv](https://arxiv.org/abs/2505.13090)