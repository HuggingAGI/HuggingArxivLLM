# 嘘，别这么讲！LLMs的领域认证

发布时间：2025年02月26日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）在特定任务中的对抗性漏洞，特别是当模型生成超出预期领域范围的输出时的风险。研究者引入了领域认证的概念，并提出了一种名为VALID的方法，用于提供对抗性界限，以限制域外样本的概率。这些内容主要涉及LLMs的理论分析、潜在风险以及改进方法，因此归类为LLM理论。`

> Shh, don't say that! Domain Certification in LLMs

# 摘要

> 大型语言模型（LLMs）通常被部署用于执行受限任务，具有狭窄的领域范围。例如，可以在LLMs的基础上构建客服机器人，依靠其广泛的语言理解和能力来提升性能。然而，这些LLMs存在对抗性漏洞，可能生成超出预期领域范围的输出。为了正式化、评估并缓解这一风险，我们引入了领域认证；这是一种保证，能够准确描述语言模型的域外行为。随后，我们提出了一种简单而有效的方法，我们称之为VALID，它提供了一种作为认证的对抗性界限。最后，我们在多样化的数据集上评估了我们的方法，证明它能够生成有意义的认证，这些认证能够以最小的拒绝行为代价，紧密地限制域外样本的概率。

> Large language models (LLMs) are often deployed to perform constrained tasks, with narrow domains. For example, customer support bots can be built on top of LLMs, relying on their broad language understanding and capabilities to enhance performance. However, these LLMs are adversarially susceptible, potentially generating outputs outside the intended domain. To formalize, assess, and mitigate this risk, we introduce domain certification; a guarantee that accurately characterizes the out-of-domain behavior of language models. We then propose a simple yet effective approach, which we call VALID that provides adversarial bounds as a certificate. Finally, we evaluate our method across a diverse set of datasets, demonstrating that it yields meaningful certificates, which bound the probability of out-of-domain samples tightly with minimum penalty to refusal behavior.

[Arxiv](https://arxiv.org/abs/2502.19320)