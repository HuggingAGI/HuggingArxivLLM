# 研究基于LLM的评估器在多语言自然语言生成评估中的能力探索

发布时间：2025年03月06日

`LLM应用` `多语言处理`

> Exploring the Multilingual NLG Evaluation Abilities of LLM-Based Evaluators

# 摘要

> 先前研究揭示了大型语言模型在多语言自然语言生成评估中的潜力，但现有研究尚未全面探索这些模型在不同语言中的评估能力差异。本研究对10个近期大型语言模型进行了全面分析，涵盖高资源与低资源语言，采用相关性分析、扰动攻击和微调方法。研究发现：1）排除参考答案并使用大参数模型的评估器能提升多语言性能；2）高资源语言的评估结果与人类判断更相关；3）对攻击敏感的语言也表现出更高的人类相关性；4）微调特定语言数据可普遍提升评估性能。研究结果凸显了大型语言模型在不同语言中评估能力的不平衡，强调了低资源语言场景的重要性，值得更多关注。

> Previous research has shown that LLMs have potential in multilingual NLG evaluation tasks. However, existing research has not fully explored the differences in the evaluation capabilities of LLMs across different languages. To this end, this study provides a comprehensive analysis of the multilingual evaluation performance of 10 recent LLMs, spanning high-resource and low-resource languages through correlation analysis, perturbation attacks, and fine-tuning. We found that 1) excluding the reference answer from the prompt and using large-parameter LLM-based evaluators leads to better performance across various languages; 2) most LLM-based evaluators show a higher correlation with human judgments in high-resource languages than in low-resource languages; 3) in the languages where they are most sensitive to such attacks, they also tend to exhibit the highest correlation with human judgments; and 4) fine-tuning with data from a particular language yields a broadly consistent enhancement in the model's evaluation performance across diverse languages. Our findings highlight the imbalance in LLMs'evaluation capabilities across different languages and suggest that low-resource language scenarios deserve more attention.

[Arxiv](https://arxiv.org/abs/2503.04360)