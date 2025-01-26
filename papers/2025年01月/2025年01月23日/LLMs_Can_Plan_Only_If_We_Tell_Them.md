# 大型语言模型（LLMs）只有在被明确指示时才能进行规划。

发布时间：2025年01月23日

`Agent

理由：这篇论文主要探讨了大型语言模型（LLMs）在自主规划能力方面的表现，并提出了AoT+增强版，旨在提升LLMs在规划任务中的自主性。这涉及到LLMs作为自主代理（Agent）在复杂任务中的表现和优化，因此归类为Agent。` `人工智能` `规划系统`

> LLMs Can Plan Only If We Tell Them

# 摘要

> 大型语言模型（LLMs）在自然语言处理和推理方面表现出色，但其自主规划能力仍存争议。现有研究虽已利用LLMs结合外部反馈或在受控环境中进行规划，但这些方法因需精心设计和迭代提示，往往耗费大量计算和开发资源。即便是GPT-4这样的顶尖LLMs，在无额外支持时，也难以在Blocksworld等标准规划基准上匹敌人类表现。本文探讨了LLMs能否独立生成媲美人类基线的长期规划。我们提出的AoT+增强版，在规划基准中实现了自主超越前人方法和人类基线的顶尖成果。

> Large language models (LLMs) have demonstrated significant capabilities in natural language processing and reasoning, yet their effectiveness in autonomous planning has been under debate. While existing studies have utilized LLMs with external feedback mechanisms or in controlled environments for planning, these approaches often involve substantial computational and development resources due to the requirement for careful design and iterative backprompting. Moreover, even the most advanced LLMs like GPT-4 struggle to match human performance on standard planning benchmarks, such as the Blocksworld, without additional support. This paper investigates whether LLMs can independently generate long-horizon plans that rival human baselines. Our novel enhancements to Algorithm-of-Thoughts (AoT), which we dub AoT+, help achieve state-of-the-art results in planning benchmarks out-competing prior methods and human baselines all autonomously.

[Arxiv](https://arxiv.org/abs/2501.13545)