# 基于辩论驱动的多智能体LLM的钓鱼邮件检测

发布时间：2025年03月27日

`Agent` `网络安全` `反欺诈`

> Debate-Driven Multi-Agent LLMs for Phishing Email Detection

# 摘要

> # 摘要  
网络钓鱼攻击仍是关键的网络安全威胁。攻击者不断改进方法，使得钓鱼邮件更难被发现。传统检测方法，如基于规则的系统和监督式机器学习模型，要么依赖可被绕过的预定义模式（如黑名单），要么需要大量数据训练且仍可能误报漏报。本研究提出了一种多智能体大型语言模型（LLM）提示技术，通过模拟智能体间的辩论来检测邮件是否为钓鱼邮件。我们的方法使用两个LLM智能体分别支持或反对分类任务，并由裁判智能体根据推理质量做出最终裁决。这种辩论机制使模型能够批判性分析文本中的上下文线索和欺骗模式，从而提升分类准确率。框架在多个钓鱼邮件数据集上进行了评估，结果表明混合智能体配置始终优于同质配置。此外，辩论结构本身足以做出准确决策，无需额外提示策略。

> Phishing attacks remain a critical cybersecurity threat. Attackers constantly refine their methods, making phishing emails harder to detect. Traditional detection methods, including rule-based systems and supervised machine learning models, either rely on predefined patterns like blacklists, which can be bypassed with slight modifications, or require large datasets for training and still can generate false positives and false negatives. In this work, we propose a multi-agent large language model (LLM) prompting technique that simulates debates among agents to detect whether the content presented on an email is phishing. Our approach uses two LLM agents to present arguments for or against the classification task, with a judge agent adjudicating the final verdict based on the quality of reasoning provided. This debate mechanism enables the models to critically analyze contextual cue and deceptive patterns in text, which leads to improved classification accuracy. The proposed framework is evaluated on multiple phishing email datasets and demonstrate that mixed-agent configurations consistently outperform homogeneous configurations. Results also show that the debate structure itself is sufficient to yield accurate decisions without extra prompting strategies.

[Arxiv](https://arxiv.org/abs/2503.22038)