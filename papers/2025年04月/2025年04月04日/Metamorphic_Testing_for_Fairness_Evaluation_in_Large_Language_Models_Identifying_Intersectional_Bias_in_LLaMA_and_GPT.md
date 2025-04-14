# 变异测试在大型语言模型中的公平性评估：发现 LLaMA 和 GPT 中的交叉偏见

发布时间：2025年04月04日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在公平性方面的挑战，并提出了一种元形测试方法来系统地识别和缓解模型中的公平性漏洞。它专注于评估模型在不同人口统计学输入下的表现，并提供了一种结构化的方法来检测和缓解偏见，以提高模型在公平性敏感应用中的鲁棒性。因此，这篇论文属于LLM应用的范畴。` `公平性测试`

> Metamorphic Testing for Fairness Evaluation in Large Language Models: Identifying Intersectional Bias in LLaMA and GPT

# 摘要

> 大型语言模型（LLMs）在自然语言处理领域取得了显著进展，但公平性问题仍是一个挑战，这些问题源于其训练数据中的偏见。在医疗、金融和法律等敏感领域应用LLMs时，这些偏见可能带来风险。本文提出了一种元形测试方法，以系统地识别LLMs中的公平性漏洞。我们定义并应用了一组以公平性为导向的元形关系（MRs），用于评估最先进的LLM——LLaMA和GPT模型在不同人口统计学输入下的表现。我们的方法包括为每个MR生成源测试用例和后续测试用例，并分析模型响应以发现公平性违规。实验结果表明，元形测试在揭示偏见模式方面非常有效，尤其是在语气和情感方面，并突出了敏感属性的特定交集，这些交集经常暴露出公平性问题。这项研究改进了LLMs的公平性测试，提供了一种结构化的方法来检测和缓解偏见，从而提高模型在公平性敏感应用中的鲁棒性。

> Large Language Models (LLMs) have made significant strides in Natural Language Processing but remain vulnerable to fairness-related issues, often reflecting biases inherent in their training data. These biases pose risks, particularly when LLMs are deployed in sensitive areas such as healthcare, finance, and law. This paper introduces a metamorphic testing approach to systematically identify fairness bugs in LLMs. We define and apply a set of fairness-oriented metamorphic relations (MRs) to assess the LLaMA and GPT model, a state-of-the-art LLM, across diverse demographic inputs. Our methodology includes generating source and follow-up test cases for each MR and analyzing model responses for fairness violations. The results demonstrate the effectiveness of MT in exposing bias patterns, especially in relation to tone and sentiment, and highlight specific intersections of sensitive attributes that frequently reveal fairness faults. This research improves fairness testing in LLMs, providing a structured approach to detect and mitigate biases and improve model robustness in fairness-sensitive applications.

[Arxiv](https://arxiv.org/abs/2504.07982)