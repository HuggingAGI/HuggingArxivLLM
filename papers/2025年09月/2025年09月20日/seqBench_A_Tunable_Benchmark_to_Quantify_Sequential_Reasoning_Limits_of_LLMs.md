# seqBench：一种用于量化大型语言模型（LLMs）序列推理极限的可调基准测试

发布时间：2025年09月20日

`LLM理论` `基础理论`

> seqBench: A Tunable Benchmark to Quantify Sequential Reasoning Limits of LLMs

# 摘要

> 我们提出了seqBench——一个参数化基准测试，旨在通过对多个关键复杂度维度的精确、多维度控制，探究大型语言模型（LLMs）的序列推理极限。seqBench支持三个维度的系统性调整：（1）逻辑深度（定义为完成任务所需的连续操作步数）；（2）最优路径中的回溯步数（量化智能体为满足延迟前提条件而需重返先前状态的频率，例如遇到锁门后需返回取钥匙）；（3）噪声比（定义为环境中支持性事实与干扰性事实的比例）。对最先进LLM的评估显示，它们存在一种共性失效模式：一旦超过模型特有的逻辑深度，准确率便呈指数级骤降。与现有基准不同，seqBench的细粒度控制支持对推理失效的针对性分析，进而揭示通用缩放规律与统计极限——本文将详细说明其生成方法、评估指标及相关发现。研究发现，即便性能顶尖的模型，在seqBench的结构化推理任务中仍会系统性失效——尽管搜索复杂度极低，这暴露了它们在常识推理能力上的核心短板。seqBench数据集支持持续演进以适配模型发展，现已公开，旨在推动对LLM推理机制的深入科学探索，助力明确其在稳健实际应用中的真实潜力与当前边界。

> We introduce seqBench, a parametrized benchmark for probing sequential reasoning limits in Large Language Models (LLMs) through precise, multi-dimensional control over several key complexity dimensions. seqBench allows systematic variation of (1) the logical depth, defined as the number of sequential actions required to solve the task; (2) the number of backtracking steps along the optimal path, quantifying how often the agent must revisit prior states to satisfy deferred preconditions (e.g., retrieving a key after encountering a locked door); and (3) the noise ratio, defined as the ratio between supporting and distracting facts about the environment. Our evaluations on state-of-the-art LLMs reveal a universal failure pattern: accuracy collapses exponentially beyond a model-specific logical depth. Unlike existing benchmarks, seqBench's fine-grained control facilitates targeted analyses of these reasoning failures, illuminating universal scaling laws and statistical limits, as detailed in this paper alongside its generation methodology and evaluation metrics. We find that even top-performing models systematically fail on seqBench's structured reasoning tasks despite minimal search complexity, underscoring key limitations in their commonsense reasoning capabilities. Designed for future evolution to keep pace with advancing models, the seqBench datasets are publicly released to spur deeper scientific inquiry into LLM reasoning, aiming to establish a clearer understanding of their true potential and current boundaries for robust real-world application.

[Arxiv](https://arxiv.org/abs/2509.16866)