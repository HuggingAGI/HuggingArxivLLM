# 代码 Copilot 真的值得信赖吗？从代码安全视角评估大型语言模型

发布时间：2025年05月15日

`LLM应用` `代码安全` `软件工程`

> Can You Really Trust Code Copilots? Evaluating Large Language Models from a Code Security Perspective

# 摘要

> # 摘要
代码安全性和可用性对于各类由大型语言模型（LLMs）驱动的编码助手应用都至关重要。然而，现有的代码安全基准测试往往只关注单一的评估任务和范式，例如代码补全和生成，缺乏对安全代码生成、漏洞修复和鉴别等多维度的全面评估。本文中，我们提出了CoV-Eval，一个多任务基准测试，涵盖代码补全、漏洞修复、漏洞检测与分类等多种任务，以全面评估LLM的代码安全性。此外，我们还开发了VC-Judge，这是一个改进的判断模型，与人类专家高度契合，能够以更高效且可靠的方式审查LLM生成的程序是否存在漏洞。我们对20个专有和开源的LLM进行了全面评估。总体而言，尽管大多数LLM在识别漏洞代码方面表现良好，但它们仍然倾向于生成不安全的代码，并在识别特定漏洞类型和进行修复方面存在困难。通过广泛的实验和定性分析，我们揭示了关键挑战和优化方向，为未来LLM代码安全领域的研究提供了重要见解。

> Code security and usability are both essential for various coding assistant applications driven by large language models (LLMs). Current code security benchmarks focus solely on single evaluation task and paradigm, such as code completion and generation, lacking comprehensive assessment across dimensions like secure code generation, vulnerability repair and discrimination. In this paper, we first propose CoV-Eval, a multi-task benchmark covering various tasks such as code completion, vulnerability repair, vulnerability detection and classification, for comprehensive evaluation of LLM code security. Besides, we developed VC-Judge, an improved judgment model that aligns closely with human experts and can review LLM-generated programs for vulnerabilities in a more efficient and reliable way. We conduct a comprehensive evaluation of 20 proprietary and open-source LLMs. Overall, while most LLMs identify vulnerable codes well, they still tend to generate insecure codes and struggle with recognizing specific vulnerability types and performing repairs. Extensive experiments and qualitative analyses reveal key challenges and optimization directions, offering insights for future research in LLM code security.

[Arxiv](https://arxiv.org/abs/2505.10494)