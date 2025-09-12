# Jupiter：借助笔记本与推理时价值引导搜索提升LLM数据分析能力

发布时间：2025年09月11日

`Agent` `基础理论`

> Jupiter: Enhancing LLM Data Analysis Capabilities via Notebook and Inference-Time Value-Guided Search

# 摘要

> 大型语言模型（LLMs）在自动化数据科学工作流方面前景广阔，但现有模型在多步推理和工具使用上仍存在不足，限制了它们在复杂数据分析任务中的实际效果。为此，我们提出一种可扩展流水线，能从真实Jupyter笔记本及相关数据文件中提取高质量、基于工具的数据分析任务及其可执行多步解决方案。借助该流水线，我们构建了NbQA——一个大规模标准化任务-解决方案对数据集，真实反映了实际数据科学场景中的工具使用模式。为进一步增强多步推理能力，我们推出Jupiter框架，它将数据分析转化为搜索问题，并通过蒙特卡洛树搜索（MCTS）生成多样化解决方案轨迹，用于价值模型学习。推理时，Jupiter结合价值模型与节点访问计数，以最少搜索步骤高效生成可执行多步计划。实验显示，在NbQA上训练的Qwen2.5-7B和14B-Instruct模型在InfiAgent-DABench数据集上的任务解决率分别达77.82%和86.38%，性能匹配甚至超越GPT-4o及先进智能体框架。进一步评估表明，模型在各类多步推理任务中泛化能力更强，工具使用推理也更为出色。

> Large language models (LLMs) have shown great promise in automating data science workflows, but existing models still struggle with multi-step reasoning and tool use, which limits their effectiveness on complex data analysis tasks. To address this, we propose a scalable pipeline that extracts high-quality, tool-based data analysis tasks and their executable multi-step solutions from real-world Jupyter notebooks and associated data files. Using this pipeline, we introduce NbQA, a large-scale dataset of standardized task-solution pairs that reflect authentic tool-use patterns in practical data science scenarios. To further enhance multi-step reasoning, we present Jupiter, a framework that formulates data analysis as a search problem and applies Monte Carlo Tree Search (MCTS) to generate diverse solution trajectories for value model learning. During inference, Jupiter combines the value model and node visit counts to efficiently collect executable multi-step plans with minimal search steps. Experimental results show that Qwen2.5-7B and 14B-Instruct models on NbQA solve 77.82% and 86.38% of tasks on InfiAgent-DABench, respectively-matching or surpassing GPT-4o and advanced agent frameworks. Further evaluations demonstrate improved generalization and stronger tool-use reasoning across diverse multi-step reasoning tasks.

[Arxiv](https://arxiv.org/abs/2509.09245)