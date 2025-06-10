# TwinBreak：利用双提示破解LLM安全对齐

发布时间：2025年06月09日

`LLM应用` `人工智能`

> TwinBreak: Jailbreaking LLM Security Alignments based on Twin Prompts

# 摘要

> 机器学习正以前所未有的速度发展，其在翻译和代码生成等领域的应用已带来显著改进。由大型语言模型 (LLMs) 驱动的 ChatGPT 等模型正逐步融入我们的日常生活。然而，LLMs 在带来便利的同时也伴随着社会风险，恶意用户可能通过提交有害提示（如请求非法活动说明）来滥用这些模型。为此，模型通常内置安全机制，自动拦截此类有害提示。但这些机制可能被 LLM 越狱技术绕过。现有的越狱方法往往需要大量手动操作、高昂计算成本或导致模型功能严重退化。

我们推出了一种创新的安全对齐移除方法——TwinBreak。该方法基于安全机制类似于嵌入后门的假设，通过识别并移除负责此功能的参数来实现目标。TwinBreak 着重分析对模型效用和安全性至关重要的参数，并专注于最相关的模型层进行细粒度分析。它是首个通过分析具有高度结构和内容相似性的提示的中间输出来隔离安全参数的方法。我们还发布了 TwinPrompt 数据集，包含 100 个此类双提示。实验结果表明，TwinBreak 在来自五个供应商的 16 个 LLM 上实现了 89% 到 98% 的成功率，且计算资源消耗极低。


> Machine learning is advancing rapidly, with applications bringing notable benefits, such as improvements in translation and code generation. Models like ChatGPT, powered by Large Language Models (LLMs), are increasingly integrated into daily life. However, alongside these benefits, LLMs also introduce social risks. Malicious users can exploit LLMs by submitting harmful prompts, such as requesting instructions for illegal activities. To mitigate this, models often include a security mechanism that automatically rejects such harmful prompts. However, they can be bypassed through LLM jailbreaks. Current jailbreaks often require significant manual effort, high computational costs, or result in excessive model modifications that may degrade regular utility.
  We introduce TwinBreak, an innovative safety alignment removal method. Building on the idea that the safety mechanism operates like an embedded backdoor, TwinBreak identifies and prunes parameters responsible for this functionality. By focusing on the most relevant model layers, TwinBreak performs fine-grained analysis of parameters essential to model utility and safety. TwinBreak is the first method to analyze intermediate outputs from prompts with high structural and content similarity to isolate safety parameters. We present the TwinPrompt dataset containing 100 such twin prompts. Experiments confirm TwinBreak's effectiveness, achieving 89% to 98% success rates with minimal computational requirements across 16 LLMs from five vendors.

[Arxiv](https://arxiv.org/abs/2506.07596)