# 资源匮乏语言下LLMs的鲁棒性评估：基于代理模型的方法

发布时间：2025年06月09日

`LLM应用`

> Evaluating LLMs Robustness in Less Resourced Languages with Proxy Models

# 摘要

> 近年来，大型语言模型（LLMs）在各种自然语言处理（NLP）任务中表现卓越。然而，它们对越狱攻击和扰动的易感性要求我们必须进行额外的评估。尽管许多LLMs是多语言模型，但与安全相关的训练数据主要包含英语等高资源语言。这使得它们容易受到波兰语等低资源语言的扰动攻击。我们展示了如何通过仅修改几个字符并利用一个小型代理模型进行单词重要性计算，廉价地创建出令人惊讶的强大攻击。我们发现，这些字符和单词级别的攻击会显著改变不同LLMs的预测结果，暗示了潜在的漏洞，可能被用来绕过它们的内部安全机制。我们在低资源语言波兰语上验证了我们的攻击构建方法，并发现了LLMs在该语言中的潜在漏洞。此外，我们展示了如何将该方法扩展到其他语言。我们还发布了创建的数据集和代码，以支持进一步的研究。

> Large language models (LLMs) have demonstrated impressive capabilities across various natural language processing (NLP) tasks in recent years. However, their susceptibility to jailbreaks and perturbations necessitates additional evaluations. Many LLMs are multilingual, but safety-related training data contains mainly high-resource languages like English. This can leave them vulnerable to perturbations in low-resource languages such as Polish. We show how surprisingly strong attacks can be cheaply created by altering just a few characters and using a small proxy model for word importance calculation. We find that these character and word-level attacks drastically alter the predictions of different LLMs, suggesting a potential vulnerability that can be used to circumvent their internal safety mechanisms. We validate our attack construction methodology on Polish, a low-resource language, and find potential vulnerabilities of LLMs in this language. Additionally, we show how it can be extended to other languages. We release the created datasets and code for further research.

[Arxiv](https://arxiv.org/abs/2506.07645)