# 探索大型语言模型在数值翻译中的应用

发布时间：2025年01月08日

`LLM应用

**理由**：该论文主要关注LLM在机器翻译领域的应用，特别是数字翻译的可靠性问题。研究通过构建数据集和实验评估LLM在数字翻译中的表现，并提出了改进策略。这属于LLM在实际应用中的具体问题研究，因此分类为“LLM应用”。` `机器翻译` `数字处理`

> Investigating Numerical Translation with Large Language Models

# 摘要

> 数字翻译的误差可能引发严重的安全隐患，从财务损失到医疗失误。尽管LLMs在机器翻译领域取得了显著进展，但其数字翻译能力仍有待深入探索。本研究聚焦于评估LLM机器翻译系统在处理数字数据时的可靠性。为系统测试当前开源LLMs的数字翻译能力，我们基于真实业务数据构建了一个中英文数字翻译数据集，涵盖十种数字翻译类型。实验结果显示，数字翻译错误普遍存在，大多数开源LLMs在面对测试场景时表现欠佳。特别是涉及“百万”、“十亿”和“亿”等大单位时，即便是最新的llama3.1 8b模型，错误率也可能高达20%。最后，我们提出了三种潜在策略，以缓解大单位数字的误译问题。

> The inaccurate translation of numbers can lead to significant security issues, ranging from financial setbacks to medical inaccuracies. While large language models (LLMs) have made significant advancements in machine translation, their capacity for translating numbers has not been thoroughly explored. This study focuses on evaluating the reliability of LLM-based machine translation systems when handling numerical data. In order to systematically test the numerical translation capabilities of currently open source LLMs, we have constructed a numerical translation dataset between Chinese and English based on real business data, encompassing ten types of numerical translation. Experiments on the dataset indicate that errors in numerical translation are a common issue, with most open-source LLMs faltering when faced with our test scenarios. Especially when it comes to numerical types involving large units like ``million", ``billion", and "yi", even the latest llama3.1 8b model can have error rates as high as 20%. Finally, we introduce three potential strategies to mitigate the numerical mistranslations for large units.

[Arxiv](https://arxiv.org/abs/2501.04927)