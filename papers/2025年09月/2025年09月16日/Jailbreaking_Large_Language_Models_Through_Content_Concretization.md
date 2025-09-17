# 通过内容具体化实现大型语言模型的越狱

发布时间：2025年09月16日

`LLM应用` `基础理论`

> Jailbreaking Large Language Models Through Content Concretization

# 摘要

> 大型语言模型（LLMs）在任务自动化和内容生成领域的应用日益广泛，但其安全机制仍易被各类越狱技术绕过。本文提出	extit{内容具象化}（Content Concretization，CC）——一种新型越狱技术，能将抽象的恶意请求迭代转化为具体可执行的实现方案。CC采用两阶段流程：首先，利用低层级、安全过滤约束较弱的模型生成LLM初始响应；接着，通过高层级模型对初步输出和原始提示词进行协同处理，实现响应优化。我们通过350个网络安全特定提示词对该技术进行评估，结果显示越狱成功率（SR）大幅提升：从无优化时的7%升至三次迭代优化后的62%，而每个提示词的成本仅为7.5美分。通过九个不同LLM评估器的对比A/B测试进一步证实，经过额外优化步骤的输出在恶意程度和技术水平上均得到一致更高的评分。此外，手动代码分析表明，生成的输出只需少量修改即可执行，但最佳部署通常仍需针对特定目标进行微调。这些结果表明，随着有害代码生成能力的进一步增强，当前LLM安全框架存在重大漏洞。

> Large Language Models (LLMs) are increasingly deployed for task automation and content generation, yet their safety mechanisms remain vulnerable to circumvention through different jailbreaking techniques. In this paper, we introduce \textit{Content Concretization} (CC), a novel jailbreaking technique that iteratively transforms abstract malicious requests into concrete, executable implementations. CC is a two-stage process: first, generating initial LLM responses using lower-tier, less constrained safety filters models, then refining them through higher-tier models that process both the preliminary output and original prompt. We evaluate our technique using 350 cybersecurity-specific prompts, demonstrating substantial improvements in jailbreak Success Rates (SRs), increasing from 7\% (no refinements) to 62\% after three refinement iterations, while maintaining a cost of 7.5\textcent~per prompt. Comparative A/B testing across nine different LLM evaluators confirms that outputs from additional refinement steps are consistently rated as more malicious and technically superior. Moreover, manual code analysis reveals that generated outputs execute with minimal modification, although optimal deployment typically requires target-specific fine-tuning. With eventual improved harmful code generation, these results highlight critical vulnerabilities in current LLM safety frameworks.

[Arxiv](https://arxiv.org/abs/2509.12937)