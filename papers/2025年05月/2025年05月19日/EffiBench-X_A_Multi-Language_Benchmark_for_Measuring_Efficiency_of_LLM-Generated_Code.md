# EffiBench-X：一个多语言基准测试，用于评估LLM生成代码的效率。

发布时间：2025年05月19日

`LLM应用` `代码生成` `软件工程`

> EffiBench-X: A Multi-Language Benchmark for Measuring Efficiency of LLM-Generated Code

# 摘要

> 现有的代码生成基准测试大多聚焦于功能正确性，对代码效率的关注较少，且通常局限于单一语言如Python。为填补这一空白，我们推出了EffiBench-X——首个专注于评估大语言模型生成代码效率的多语言基准测试。它支持包括Python、C++、Java、JavaScript、Ruby和Golang在内的多种编程语言，并通过竞争性编程任务和人类专家解决方案作为效率基准。评估结果显示，尽管当前最先进的大语言模型能生成功能正确的代码，但其效率普遍低于人类专家。即使是效率最高的模型（如Qwen3-32B），其代码效率也仅能达到人类专家的	extbf{62\%}左右，且不同语言间存在显著差异。例如，大语言模型在Python、Ruby和JavaScript中的表现优于在Java、C++和Golang中的表现，DeepSeek-R1的Python代码就比其Java代码高效得多。这些发现凸显了针对大语言模型优化技术的研究需求，以期提升跨多种语言的代码效率。EffiBench-X的数据集和评估基础设施已公开，可通过https://github.com/EffiBench/EffiBench-X.git和https://huggingface.co/datasets/EffiBench/effibench-x访问。


> Existing code generation benchmarks primarily evaluate functional correctness, with limited focus on code efficiency and often restricted to a single language like Python. To address this gap, we introduce EffiBench-X, the first multi-language benchmark designed to measure the efficiency of LLM-generated code. EffiBench-X supports Python, C++, Java, JavaScript, Ruby, and Golang. It comprises competitive programming tasks with human-expert solutions as efficiency baselines. Evaluating state-of-the-art LLMs on EffiBench-X reveals that while models generate functionally correct code, they consistently underperform human experts in efficiency. Even the most efficient LLM-generated solutions (Qwen3-32B) achieve only around \textbf{62\%} of human efficiency on average, with significant language-specific variations. LLMs show better efficiency in Python, Ruby, and JavaScript than in Java, C++, and Golang. For instance, DeepSeek-R1's Python code is significantly more efficient than its Java code. These results highlight the critical need for research into LLM optimization techniques to improve code efficiency across diverse languages. The dataset and evaluation infrastructure are submitted and available at https://github.com/EffiBench/EffiBench-X.git and https://huggingface.co/datasets/EffiBench/effibench-x.

[Arxiv](https://arxiv.org/abs/2505.13004)