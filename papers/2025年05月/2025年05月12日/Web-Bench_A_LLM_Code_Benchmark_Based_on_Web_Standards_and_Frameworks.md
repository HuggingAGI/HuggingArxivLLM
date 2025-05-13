# Web-Bench：基于Web标准和框架的LLM代码基准

发布时间：2025年05月12日

`LLM应用` `Web开发`

> Web-Bench: A LLM Code Benchmark Based on Web Standards and Frameworks

# 摘要

> 大型语言模型（LLMs）在编码领域的应用正在经历飞速发展：从最初的代码助手，到如今的自主编码代理，再到通过自然语言生成完整项目。早期的LLM代码基准测试主要关注代码生成的准确性，但这些基准逐渐达到饱和状态，削弱了它们对LLMs的指导作用。例如，HumanEval Pass@1已达到99.4%，MBPP为94.2%。在解决基准饱和的各种尝试中，基于软件工程的方法脱颖而出，但现有软件工程基准的饱和程度正在迅速上升。

为此，我们提出了一种新的基准——Web-Bench。该基准包含50个项目，每个项目由20个具有顺序依赖关系的任务组成。这些任务依次实现项目功能，模拟真实世界中人类的开发工作流程。在设计Web-Bench时，我们力求涵盖Web开发的基础要素：Web标准和Web框架。鉴于这些项目是由具有5到10年经验的工程师设计的，其规模和复杂性使得每个项目都极具挑战性。平均而言，一个资深工程师完成单个项目需要4到8小时。

在我们的基准代理（Web-Agent）上，SOTA（Claude 3.7 Sonnet）仅实现了25.1%的Pass@1，显著低于SWE-Bench的Verified（65.4%）和Full（33.8%）得分。最后，我们讨论了在任何开发领域，标准和框架分别代表了基础知识和效率工具，因此LLMs需要针对它们进行优化。

> The application of large language models (LLMs) in the field of coding is evolving rapidly: from code assistants, to autonomous coding agents, and then to generating complete projects through natural language. Early LLM code benchmarks primarily focused on code generation accuracy, but these benchmarks have gradually become saturated. Benchmark saturation weakens their guiding role for LLMs. For example, HumanEval Pass@1 has reached 99.4% and MBPP 94.2%. Among various attempts to address benchmark saturation, approaches based on software engineering have stood out, but the saturation of existing software engineering benchmarks is rapidly increasing. To address this, we propose a new benchmark, Web-Bench, which contains 50 projects, each consisting of 20 tasks with sequential dependencies. The tasks implement project features in sequence, simulating real-world human development workflows. When designing Web-Bench, we aim to cover the foundational elements of Web development: Web Standards and Web Frameworks. Given the scale and complexity of these projects, which were designed by engineers with 5 to 10 years of experience, each presents a significant challenge. On average, a single project takes 4 to 8 hours for a senior engineer to complete. On our given benchmark agent (Web-Agent), SOTA (Claude 3.7 Sonnet) achieves only 25.1% Pass@1, significantly lower (better) than SWE-Bench's Verified (65.4%) and Full (33.8%) scores. Finally, we discuss that in any development field, Standards and Frameworks represent foundational knowledge and efficiency tools, respectively, and LLMs require optimization tailored to them.

[Arxiv](https://arxiv.org/abs/2505.07473)