# SciReplicate-Bench：评估 LLMs 在基于研究论文的代理驱动算法复现中的性能

发布时间：2025年03月31日

`LLM应用` `代码生成`

> SciReplicate-Bench: Benchmarking LLMs in Agent-driven Algorithmic Reproduction from Research Papers

# 摘要

> 本研究旨在评估大型语言模型（LLMs）从近期自然语言处理（NLP）论文中生成代码的能力。该任务需要模型具备两项核心能力：一是准确理解算法的实现逻辑，二是熟练掌握代码实现的依赖关系和API调用。为此，我们提出了SciReplicate-Bench，这是一个包含2024年发表的36篇NLP论文中100个任务的基准测试集，每个任务都配有详细的标注和全面的测试用例。基于此基准，我们开发了Sci-Reproducer框架，该框架由两个智能体组成：Paper Agent负责从文献中解析算法概念，Code Agent负责从代码库中检索依赖项并生成解决方案。在评估模型能力时，我们引入了推理图准确率这一指标，通过比较生成推理图与基于代码注释和结构的参考推理图，量化模型对算法的理解深度。对于代码实现质量的评估，我们采用了执行准确率、CodeBLEU以及依赖项/API召回率三项指标。实验结果表明，即使是最先进的非推理LLMs和推理LLMs，在Sci-Reproducer框架下也仅能达到39%的执行准确率，充分体现了该基准的难度。进一步分析发现，算法描述的缺失或不一致是导致复现失败的主要原因。我们计划将基准和代码开源至https://github.com/xyzCS/SciReplicate-Bench，为研究社区提供一个开放的研究平台。

> This study evaluates large language models (LLMs) in generating code from algorithm descriptions from recent NLP papers. The task requires two key competencies: (1) algorithm comprehension: synthesizing information from papers and academic literature to understand implementation logic, and (2) coding expertise: identifying dependencies and correctly implementing necessary APIs. To facilitate rigorous evaluation, we introduce SciReplicate-Bench, a benchmark of 100 tasks from 36 NLP papers published in 2024, featuring detailed annotations and comprehensive test cases. Building on SciReplicate-Bench, we propose Sci-Reproducer, a multi-agent framework consisting of a Paper Agent that interprets algorithmic concepts from literature and a Code Agent that retrieves dependencies from repositories and implement solutions. To assess algorithm understanding, we introduce reasoning graph accuracy, which quantifies similarity between generated and reference reasoning graphs derived from code comments and structure. For evaluating implementation quality, we employ execution accuracy, CodeBLEU, and repository dependency/API recall metrics. In our experiments, we evaluate various powerful Non-Reasoning LLMs and Reasoning LLMs as foundational models. The best-performing LLM using Sci-Reproducer achieves only 39% execution accuracy, highlighting the benchmark's difficulty.Our analysis identifies missing or inconsistent algorithm descriptions as key barriers to successful reproduction. We will open-source our benchmark, and code at https://github.com/xyzCS/SciReplicate-Bench.

[Arxiv](https://arxiv.org/abs/2504.00255)