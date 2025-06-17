# 最薄弱的环节：高级推理模型中的安全漏洞

发布时间：2025年06月16日

`LLM理论` `人工智能`

> Weakest Link in the Chain: Security Vulnerabilities in Advanced Reasoning Models

# 摘要

> 先进推理能力的引入显著提升了大型语言模型在数学和编程基准测试中的问题解决性能。然而，目前尚不清楚这些推理模型相较于不具备推理能力的模型，是否更容易或更难受到对抗性提示攻击的影响。本研究系统评估了在多种基于提示的攻击类别下，先进推理模型相较于不具备推理能力的类似模型的弱点。通过实验数据，我们发现总体而言，推理增强的模型比不具备推理能力的模型略显稳健（42.51% vs 45.53%的攻击成功率，数值越低越好）。然而，这一总体趋势掩盖了显著的类别特定差异：在某些攻击类型中，推理模型明显更易受到攻击（例如，在攻击树提示方面差达32个百分点），而在其他类型中则表现得更加稳健（例如，在跨站脚本注入方面好29.8个百分点）。我们的研究揭示了语言模型中先进推理的复杂安全影响，并强调了在多种对抗技术下进行安全压力测试的重要性。

> The introduction of advanced reasoning capabilities have improved the problem-solving performance of large language models, particularly on math and coding benchmarks. However, it remains unclear whether these reasoning models are more or less vulnerable to adversarial prompt attacks than their non-reasoning counterparts. In this work, we present a systematic evaluation of weaknesses in advanced reasoning models compared to similar non-reasoning models across a diverse set of prompt-based attack categories. Using experimental data, we find that on average the reasoning-augmented models are \emph{slightly more robust} than non-reasoning models (42.51\% vs 45.53\% attack success rate, lower is better). However, this overall trend masks significant category-specific differences: for certain attack types the reasoning models are substantially \emph{more vulnerable} (e.g., up to 32 percentage points worse on a tree-of-attacks prompt), while for others they are markedly \emph{more robust} (e.g., 29.8 points better on cross-site scripting injection). Our findings highlight the nuanced security implications of advanced reasoning in language models and emphasize the importance of stress-testing safety across diverse adversarial techniques.

[Arxiv](https://arxiv.org/abs/2506.13726)