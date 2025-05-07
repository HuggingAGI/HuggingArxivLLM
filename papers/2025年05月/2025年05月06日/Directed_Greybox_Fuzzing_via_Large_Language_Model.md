# # 基于大型语言模型的定向灰盒模糊测试

发布时间：2025年05月06日

`LLM应用

理由：这篇论文探讨了如何将大型语言模型（LLM）应用于定向灰盒模糊测试中，以提高漏洞检测和利用的效率。具体来说，HGFuzzer利用LLM生成针对特定路径的输入，从而减少不必要的探索路径，提高定向模糊测试的效率和精度。这项工作展示了LLM在实际应用中的有效性，特别是在漏洞检测和安全领域。因此，它属于LLM应用类别。` `软件安全` `软件工程`

> Directed Greybox Fuzzing via Large Language Model

# 摘要

> 定向灰盒模糊测试（DGF）专注于高效地达到特定程序位置或触发特定行为，使其成为漏洞检测和崩溃复现等任务中的重要工具。然而，现有方法通常面临路径爆炸和输入变异的随机性问题，导致在探索和利用目标路径时效率低下。本文中，我们提出了HGFuzzer，这是一个利用大型语言模型（LLM）来解决这些挑战的自动框架。HGFuzzer将路径约束问题转化为有针对性的代码生成任务，系统地生成测试框架和可达到的输入，从而显著减少不必要的探索路径。此外，我们实现了专门针对目标函数的自定义变异器，以最小化随机性并提高定向模糊测试的精度。我们在20个真实世界的漏洞上评估了HGFuzzer，成功触发了17个漏洞，其中11个在第一分钟内就被触发，与最先进的定向模糊器相比，速度提高了至少24.8倍。此外，HGFuzzer发现了9个之前未知的漏洞，所有这些漏洞都获得了CVE ID，这证明了我们在识别真实世界漏洞方面的有效性。

> Directed greybox fuzzing (DGF) focuses on efficiently reaching specific program locations or triggering particular behaviors, making it essential for tasks like vulnerability detection and crash reproduction. However, existing methods often suffer from path explosion and randomness in input mutation, leading to inefficiencies in exploring and exploiting target paths. In this paper, we propose HGFuzzer, an automatic framework that leverages the large language model (LLM) to address these challenges. HGFuzzer transforms path constraint problems into targeted code generation tasks, systematically generating test harnesses and reachable inputs to reduce unnecessary exploration paths significantly. Additionally, we implement custom mutators designed specifically for target functions, minimizing randomness and improving the precision of directed fuzzing. We evaluated HGFuzzer on 20 real-world vulnerabilities, successfully triggering 17, including 11 within the first minute, achieving a speedup of at least 24.8x compared to state-of-the-art directed fuzzers. Furthermore, HGFuzzer discovered 9 previously unknown vulnerabilities, all of which were assigned CVE IDs, demonstrating the effectiveness of our approach in identifying real-world vulnerabilities.

[Arxiv](https://arxiv.org/abs/2505.03425)