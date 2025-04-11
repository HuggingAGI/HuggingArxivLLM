# 基准测试大型语言模型的对抗鲁棒性：通过以LLM为裁判的可扩展自动化评估揭示偏见

发布时间：2025年04月10日

`LLM理论` `模型安全`

> Benchmarking Adversarial Robustness to Bias Elicitation in Large Language Models: Scalable Automated Assessment with LLM-as-a-Judge

# 摘要

> 大型语言模型（LLMs）彻底改变了人工智能领域，推动了机器翻译、文本摘要和对话智能体的进步。然而，随着它们越来越多地被整合到关键的社会领域，嵌入其中的偏见引发了人们的担忧，这些偏见可能会强化刻板印象并损害公平性。这些偏见来源于多个方面，包括训练数据中的历史不平等、语言不平衡以及对抗性操纵。尽管已经采取了一些缓解措施，但最近的研究表明，LLMs仍然容易受到旨在引发偏见响应的对抗性攻击。

本研究提出了一种可扩展的基准测试框架，用于评估LLMs在面对对抗性偏见提取时的鲁棒性。我们的方法包括以下三个部分：(i) 通过多任务方法系统性地探测模型，针对各种社会文化维度的偏见；(ii) 通过使用“LLM-as-a-Judge”方法对模型响应进行自动化评估，量化鲁棒性；(iii) 采用越狱技术来研究安全机制中的漏洞。

我们的分析考察了当前先进模型（从小型到大型）中普遍存在的偏见及其对模型安全的影响。此外，我们还评估了在关键领域（如医学）进行微调的领域特定模型的安全性。最后，我们发布了一个经过整理的与偏见相关的提示数据集CLEAR-Bias，以促进系统性漏洞基准测试。我们的研究发现揭示了模型规模与安全之间的关键权衡关系，有助于未来开发更加公平和稳健的语言模型。

> Large Language Models (LLMs) have revolutionized artificial intelligence, driving advancements in machine translation, summarization, and conversational agents. However, their increasing integration into critical societal domains has raised concerns about embedded biases, which can perpetuate stereotypes and compromise fairness. These biases stem from various sources, including historical inequalities in training data, linguistic imbalances, and adversarial manipulation. Despite mitigation efforts, recent studies indicate that LLMs remain vulnerable to adversarial attacks designed to elicit biased responses. This work proposes a scalable benchmarking framework to evaluate LLM robustness against adversarial bias elicitation. Our methodology involves (i) systematically probing models with a multi-task approach targeting biases across various sociocultural dimensions, (ii) quantifying robustness through safety scores using an LLM-as-a-Judge approach for automated assessment of model responses, and (iii) employing jailbreak techniques to investigate vulnerabilities in safety mechanisms. Our analysis examines prevalent biases in both small and large state-of-the-art models and their impact on model safety. Additionally, we assess the safety of domain-specific models fine-tuned for critical fields, such as medicine. Finally, we release a curated dataset of bias-related prompts, CLEAR-Bias, to facilitate systematic vulnerability benchmarking. Our findings reveal critical trade-offs between model size and safety, aiding the development of fairer and more robust future language models.

[Arxiv](https://arxiv.org/abs/2504.07887)