# 暗黑 LLM：不对齐 AI 模型的威胁日益严峻

发布时间：2025年05月15日

`LLM理论

摘要讨论了大型语言模型（LLMs）的安全性和越狱攻击问题，深入分析了模型的内在机制和潜在漏洞，属于对LLMs理论层面的研究。` `AI安全` `网络安全`

> Dark LLMs: The Growing Threat of Unaligned AI Models

# 摘要

> 大型语言模型（LLMs）正在迅速重塑现代生活，从医疗到教育等众多领域都因此取得了显著进展。然而，与这些模型的强大能力相伴的，是一个不容忽视的威胁：它们极易受到越狱攻击。LLMs易受越狱攻击的根本原因在于其学习数据本身。只要训练数据包含未经筛选、存在问题或“黑暗”的内容，模型就可能学到不良模式或弱点，从而让用户能够绕过其设计的安全控制。我们的研究发现了一种普遍存在的越狱攻击方法，这种方法可以有效突破多个最先进的模型，使它们能够回答几乎所有问题，并在请求时生成有害输出。这种攻击的主要思路在七个多月前就已经在网上公开。然而，许多被测试的LLMs仍然容易受到此类攻击。尽管我们已负责任地披露了这一问题，但主要LLM供应商的回应往往不足，凸显了行业在AI安全实践中的显著差距。随着模型训练变得越来越容易和便宜，以及开源LLMs的普及，滥用的风险也在不断上升。如果没有果断的干预，LLMs可能会继续让危险知识的获取变得更加民主化，带来比预期更大的风险。

> Large Language Models (LLMs) rapidly reshape modern life, advancing fields from healthcare to education and beyond. However, alongside their remarkable capabilities lies a significant threat: the susceptibility of these models to jailbreaking. The fundamental vulnerability of LLMs to jailbreak attacks stems from the very data they learn from. As long as this training data includes unfiltered, problematic, or 'dark' content, the models can inherently learn undesirable patterns or weaknesses that allow users to circumvent their intended safety controls. Our research identifies the growing threat posed by dark LLMs models deliberately designed without ethical guardrails or modified through jailbreak techniques. In our research, we uncovered a universal jailbreak attack that effectively compromises multiple state-of-the-art models, enabling them to answer almost any question and produce harmful outputs upon request. The main idea of our attack was published online over seven months ago. However, many of the tested LLMs were still vulnerable to this attack. Despite our responsible disclosure efforts, responses from major LLM providers were often inadequate, highlighting a concerning gap in industry practices regarding AI safety. As model training becomes more accessible and cheaper, and as open-source LLMs proliferate, the risk of widespread misuse escalates. Without decisive intervention, LLMs may continue democratizing access to dangerous knowledge, posing greater risks than anticipated.

[Arxiv](https://arxiv.org/abs/2505.10066)