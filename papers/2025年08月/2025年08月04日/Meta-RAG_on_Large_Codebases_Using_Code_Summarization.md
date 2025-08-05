# # 基于代码摘要的大型代码库上Meta-RAG方法研究

发布时间：2025年08月04日

`RAG` `软件开发` `代码库管理`

> Meta-RAG on Large Codebases Using Code Summarization

# 摘要

> 大型语言模型 (LLM) 在众多领域的人工智能研究中处于前沿，其中软件开发领域尤为突出。研究人员借助 LLM 代理推动了多项代码任务的自动化。软件开发不仅涉及代码实现，更是一个复杂的生态系统，涵盖代码维护等多方面。本文提出了一种基于信息检索和 LLM 的多智能体系统，用于在大型现有代码库中定位错误。我们的系统引入了创新的检索增强生成 (RAG) 方法——Meta-RAG，通过摘要将代码库平均压缩 79.8%，转化为紧凑、结构化的自然语言表示。随后，我们借助 LLM 智能体识别代码库中对错误解决至关重要的部分，即错误定位。通过与 SWE-bench Lite 数据集的对比评估，Meta-RAG 展现了其卓越的性能，在文件级别和函数级别正确定位率分别达到 84.67% 和 53.0%，达到了当前最先进的水平。

> Large Language Model (LLM) systems have been at the forefront of applied Artificial Intelligence (AI) research in a multitude of domains. One such domain is software development, where researchers have pushed the automation of a number of code tasks through LLM agents. Software development is a complex ecosystem, that stretches far beyond code implementation and well into the realm of code maintenance. In this paper, we propose a multi-agent system to localize bugs in large pre-existing codebases using information retrieval and LLMs. Our system introduces a novel Retrieval Augmented Generation (RAG) approach, Meta-RAG, where we utilize summaries to condense codebases by an average of 79.8\%, into a compact, structured, natural language representation. We then use an LLM agent to determine which parts of the codebase are critical for bug resolution, i.e. bug localization. We demonstrate the usefulness of Meta-RAG through evaluation with the SWE-bench Lite dataset. Meta-RAG scores 84.67 % and 53.0 % for file-level and function-level correct localization rates, respectively, achieving state-of-the-art performance.

[Arxiv](https://arxiv.org/abs/2508.02611)