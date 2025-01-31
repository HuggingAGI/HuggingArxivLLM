# 相关性幻觉：通过内容注入攻击欺骗检索器、重排序器及LLM法官

发布时间：2025年01月30日

`LLM应用

理由：这篇论文主要讨论了神经信息检索（IR）管道中的内容注入攻击问题，特别是针对检索嵌入模型、重排序器以及LLM相关性判断器的攻击。论文还探讨了防御策略，包括对抗性段落分类器、微调检索器以及提示LLM判断器等方法。这些内容涉及到LLM在实际应用中的安全性和鲁棒性问题，因此将其分类为LLM应用。` `信息安全` `信息检索`

> Illusions of Relevance: Using Content Injection Attacks to Deceive Retrievers, Rerankers, and LLM Judges

# 摘要

> 想象一下，用户搜索信息时，却遇到大量误导性或无关的文本。这一场景揭示了神经信息检索（IR）管道中的一个简单但强大的漏洞：内容注入攻击。我们发现，检索嵌入模型、重排序器以及LLM相关性判断器都容易受到此类攻击的影响，攻击者通过在段落中插入误导性文本来操纵模型判断。我们识别出两大威胁：（1）在段落中插入看似“相关”但实际上无关或有害的内容，（2）在段落中插入整个查询或关键查询词以提高其感知相关性。虽然第二种策略已有研究，但我们首次对第一种威胁进行了实证分析，展示了最先进模型如何被轻易误导。我们的研究系统考察了影响攻击成功的因素，如注入内容的位置及相关与非相关材料的平衡。此外，我们探索了多种防御策略，包括对抗性段落分类器、微调检索器以忽略被操纵内容，以及提示LLM判断器采取更谨慎的方法。然而，这些对策往往涉及权衡，牺牲有效性以换取攻击鲁棒性，有时还会误伤合法文档。我们的研究结果强调了需要更强的防御措施来应对这些不断演变的对抗策略，以维护IR系统的可信度。我们发布了代码和脚本，以促进进一步研究。

> Consider a scenario in which a user searches for information, only to encounter texts flooded with misleading or non-relevant content. This scenario exemplifies a simple yet potent vulnerability in neural Information Retrieval (IR) pipelines: content injection attacks. We find that embedding models for retrieval, rerankers, and large language model (LLM) relevance judges are vulnerable to these attacks, in which adversaries insert misleading text into passages to manipulate model judgements. We identify two primary threats: (1) inserting unrelated or harmful content within passages that still appear deceptively "relevant", and (2) inserting entire queries or key query terms into passages to boost their perceived relevance. While the second tactic has been explored in prior research, we present, to our knowledge, the first empirical analysis of the first threat, demonstrating how state-of-the-art models can be easily misled. Our study systematically examines the factors that influence an attack's success, such as the placement of injected content and the balance between relevant and non-relevant material. Additionally, we explore various defense strategies, including adversarial passage classifiers, retriever fine-tuning to discount manipulated content, and prompting LLM judges to adopt a more cautious approach. However, we find that these countermeasures often involve trade-offs, sacrificing effectiveness for attack robustness and sometimes penalizing legitimate documents in the process. Our findings highlight the need for stronger defenses against these evolving adversarial strategies to maintain the trustworthiness of IR systems. We release our code and scripts to facilitate further research.

[Arxiv](https://arxiv.org/abs/2501.18536)