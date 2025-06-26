# JsDeObsBench：评估 LLMs 在 JavaScript 解混淆中的能力基准测试

发布时间：2025年06月25日

`LLM应用` `网络安全` `代码分析`

> JsDeObsBench: Measuring and Benchmarking LLMs for JavaScript Deobfuscation

# 摘要

> 去混淆JavaScript代码在网络安全领域是一个重大挑战，尤其是在混淆技术被广泛用于隐藏脚本中的恶意行为的情况下。尽管大型语言模型 (LLMs) 在自动化去混淆流程方面显示出巨大潜力，能够改变针对这些混淆威胁的检测和缓解策略，但系统性地量化其有效性和局限性的基准测试却一直缺失。为了解决这一空白，我们提出了JsDeObsBench，这是一个专门设计的基准测试框架，旨在严格评估LLMs在JS去混淆任务中的有效性。我们详细介绍了基准测试的方法论，涵盖了从基本的变量重命名到复杂的结构转换等多种混淆技术，为评估LLMs在现实场景中的性能提供了一个强大的框架。通过广泛的实验分析，我们研究了前沿LLMs（例如GPT-4o、Mixtral、Llama和DeepSeek-Coder）的表现，发现它们在代码简化方面表现出色，尽管在保持语法准确性和执行可靠性方面仍面临挑战，与基线方法相比仍有改进空间。我们进一步评估了JS恶意软件的去混淆效果，展示了LLMs在安全场景中的潜力。研究结果突显了LLMs在去混淆应用中的实用价值，并指出了未来改进的关键方向。

> Deobfuscating JavaScript (JS) code poses a significant challenge in web security, particularly as obfuscation techniques are frequently used to conceal malicious activities within scripts. While Large Language Models (LLMs) have recently shown promise in automating the deobfuscation process, transforming detection and mitigation strategies against these obfuscated threats, a systematic benchmark to quantify their effectiveness and limitations has been notably absent. To address this gap, we present JsDeObsBench, a dedicated benchmark designed to rigorously evaluate the effectiveness of LLMs in the context of JS deobfuscation. We detail our benchmarking methodology, which includes a wide range of obfuscation techniques ranging from basic variable renaming to sophisticated structure transformations, providing a robust framework for assessing LLM performance in real-world scenarios. Our extensive experimental analysis investigates the proficiency of cutting-edge LLMs, e.g., GPT-4o, Mixtral, Llama, and DeepSeek-Coder, revealing superior performance in code simplification despite challenges in maintaining syntax accuracy and execution reliability compared to baseline methods. We further evaluate the deobfuscation of JS malware to exhibit the potential of LLMs in security scenarios. The findings highlight the utility of LLMs in deobfuscation applications and pinpoint crucial areas for further improvement.

[Arxiv](https://arxiv.org/abs/2506.20170)