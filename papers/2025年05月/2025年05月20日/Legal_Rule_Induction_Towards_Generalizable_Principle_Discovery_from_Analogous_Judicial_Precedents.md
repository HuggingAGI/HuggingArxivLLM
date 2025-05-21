# 法律规则归纳：从类似司法先例中发现可推广的原则

发布时间：2025年05月20日

`LLM应用` `法律规则归纳`

> Legal Rule Induction: Towards Generalizable Principle Discovery from Analogous Judicial Precedents

# 摘要

> 法律规则不仅涵盖成文法，还包括从先例中提炼出的隐含裁判原则，这些原则包含了自由裁量规范、社会道德和政策。尽管计算法律研究在将既定规则应用于具体案件方面取得了进展，但从司法决策中归纳法律规则的研究仍显不足，受限于模型推理效能和符号推理能力的局限。大型语言模型（LLMs）的出现为自动提取此类潜在原则提供了前所未有的机遇，然而，由于缺乏正式的任务定义、基准数据集和方法论，这一领域的进展受到阻碍。为填补这一空白，我们将法律规则归纳（LRI）形式化为从类比先例集中推导简洁、可推广的教义规则的任务，提炼出其共同的先决条件、规范行为和法律后果。我们引入了首个LRI基准，包含5,121个案例集（总计38,088个中文案例）用于模型调优，以及216个专家标注的黄金测试集。实验结果表明：1）最先进的LLMs在处理过度概括和幻觉方面仍存在困难；2）在我们的数据集上进行训练显著提升了LLMs捕捉相似案例中细微规则模式的能力。

> Legal rules encompass not only codified statutes but also implicit adjudicatory principles derived from precedents that contain discretionary norms, social morality, and policy. While computational legal research has advanced in applying established rules to cases, inducing legal rules from judicial decisions remains understudied, constrained by limitations in model inference efficacy and symbolic reasoning capability. The advent of Large Language Models (LLMs) offers unprecedented opportunities for automating the extraction of such latent principles, yet progress is stymied by the absence of formal task definitions, benchmark datasets, and methodologies. To address this gap, we formalize Legal Rule Induction (LRI) as the task of deriving concise, generalizable doctrinal rules from sets of analogous precedents, distilling their shared preconditions, normative behaviors, and legal consequences. We introduce the first LRI benchmark, comprising 5,121 case sets (38,088 Chinese cases in total) for model tuning and 216 expert-annotated gold test sets. Experimental results reveal that: 1) State-of-the-art LLMs struggle with over-generalization and hallucination; 2) Training on our dataset markedly enhances LLMs capabilities in capturing nuanced rule patterns across similar cases.

[Arxiv](https://arxiv.org/abs/2505.14104)