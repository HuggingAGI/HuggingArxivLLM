# 幻象导入：评估LLM包幻觉的脆弱性

发布时间：2025年01月31日

`LLM应用

**理由**：这篇论文主要探讨了大型语言模型（LLMs）在编程中的应用，特别是其在生成代码时可能产生的虚构包问题，并提出了防御策略。这属于LLM在实际应用中的问题，因此分类为LLM应用。` `软件工程` `网络安全`

> Importing Phantoms: Measuring LLM Package Hallucination Vulnerabilities

# 摘要

> 大型语言模型（LLMs）已成为程序员工具箱中的利器，但其生成虚构代码的倾向可能被恶意利用，从而在软件供应链中埋下隐患。本研究深入分析了LLMs在多种编程语言中的包虚构行为，涵盖现有包引用和虚构依赖项。通过这一分析，我们揭示了潜在攻击，并提出了防御策略。研究发现，包虚构率不仅受模型选择影响，还与编程语言、模型大小及编码任务的具体性密切相关。代码生成性能与包虚构之间的帕累托最优边界稀疏，表明编码模型在安全代码优化方面尚有不足。此外，包虚构率与HumanEval编码基准呈负相关，为评估模型虚构包倾向提供了启发。我们的指标、发现和分析为未来模型奠定了基础，助力AI辅助的软件开发工作流程抵御包供应链攻击。

> Large Language Models (LLMs) have become an essential tool in the programmer's toolkit, but their tendency to hallucinate code can be used by malicious actors to introduce vulnerabilities to broad swathes of the software supply chain. In this work, we analyze package hallucination behaviour in LLMs across popular programming languages examining both existing package references and fictional dependencies. By analyzing this package hallucination behaviour we find potential attacks and suggest defensive strategies to defend against these attacks. We discover that package hallucination rate is predicated not only on model choice, but also programming language, model size, and specificity of the coding task request. The Pareto optimality boundary between code generation performance and package hallucination is sparsely populated, suggesting that coding models are not being optimized for secure code. Additionally, we find an inverse correlation between package hallucination rate and the HumanEval coding benchmark, offering a heuristic for evaluating the propensity of a model to hallucinate packages. Our metrics, findings and analyses provide a base for future models, securing AI-assisted software development workflows against package supply chain attacks.

[Arxiv](https://arxiv.org/abs/2501.19012)