# 评测基准：基于GPT模型的安全代码生成提示工程技巧

发布时间：2025年02月09日

`LLM应用` `代码安全` `软件开发`

> Benchmarking Prompt Engineering Techniques for Secure Code Generation with GPT Models

# 摘要

> 提示工程能够有效减少大型语言模型（LLMs）中的推理错误，但在缓解LLM生成代码中的漏洞方面，其效果仍有待深入研究。为填补这一空白，我们开发了一个基准测试，用于自动评估不同提示工程策略对代码安全的影响。该基准测试基于两个经过同行评审的提示数据集，并借助静态扫描工具实现大规模代码安全性评估。我们对GPT-3.5-turbo、GPT-4o和GPT-4o-mini进行了多项提示工程技巧的测试。结果显示，对于GPT-4o和GPT-4o-mini，采用安全导向的提示前缀可将安全漏洞的发生率降低高达56%。此外，所有测试模型在使用迭代提示技术时，均能检测并修复之前生成代码中41.9%至68.7%的安全漏洞。最后，我们推出了一款“提示代理”，展示了如何将这些高效技术融入实际开发流程。

> Prompt engineering reduces reasoning mistakes in Large Language Models (LLMs). However, its effectiveness in mitigating vulnerabilities in LLM-generated code remains underexplored. To address this gap, we implemented a benchmark to automatically assess the impact of various prompt engineering strategies on code security. Our benchmark leverages two peer-reviewed prompt datasets and employs static scanners to evaluate code security at scale. We tested multiple prompt engineering techniques on GPT-3.5-turbo, GPT-4o, and GPT-4o-mini. Our results show that for GPT-4o and GPT-4o-mini, a security-focused prompt prefix can reduce the occurrence of security vulnerabilities by up to 56%. Additionally, all tested models demonstrated the ability to detect and repair between 41.9% and 68.7% of vulnerabilities in previously generated code when using iterative prompting techniques. Finally, we introduce a "prompt agent" that demonstrates how the most effective techniques can be applied in real-world development workflows.

[Arxiv](https://arxiv.org/abs/2502.06039)