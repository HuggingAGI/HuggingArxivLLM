# CodeARC：评估LLM代理在归纳程序合成中的推理能力基准测试

发布时间：2025年03月29日

`LLM应用` `软件工程` `程序合成`

> CodeARC: Benchmarking Reasoning Capabilities of LLM Agents for Inductive Program Synthesis

# 摘要

> 归纳程序合成（或编程以示例）要求从输入输出样例中合成能够推广到未见输入的函数。尽管大型语言模型代理在自然语言指导下进行编程任务方面显示出潜力，但其在归纳程序合成方面的表现尚未得到充分探索。现有评估协议依赖于静态示例集和保留测试，当合成函数不正确时无法提供反馈，也无法反映逆向工程等现实场景。

我们提出CodeARC（代码抽象与推理挑战），这是一个新的评估框架。在该框架中，代理通过用新输入查询隐藏的目标函数、合成候选函数，并使用差异测试预言机迭代优化其解决方案。这种交互式设置鼓励代理根据反馈进行函数调用和自我修正。我们构建了第一个大规模通用归纳程序合成基准，包含1114个函数。

在评估的18个模型中，o3-mini表现最佳，成功率为52.7%，凸显了该任务的难度。对LLaMA-3.1-8B-Instruct进行微调，使用经过整理的合成轨迹，可获得高达31%的相对性能提升。CodeARC为基于LLM的程序合成和归纳推理提供了一个更现实且具挑战性的测试平台。

> Inductive program synthesis, or programming by example, requires synthesizing functions from input-output examples that generalize to unseen inputs. While large language model agents have shown promise in programming tasks guided by natural language, their ability to perform inductive program synthesis is underexplored. Existing evaluation protocols rely on static sets of examples and held-out tests, offering no feedback when synthesized functions are incorrect and failing to reflect real-world scenarios such as reverse engineering. We propose CodeARC, the Code Abstraction and Reasoning Challenge, a new evaluation framework where agents interact with a hidden target function by querying it with new inputs, synthesizing candidate functions, and iteratively refining their solutions using a differential testing oracle. This interactive setting encourages agents to perform function calls and self-correction based on feedback. We construct the first large-scale benchmark for general-purpose inductive program synthesis, featuring 1114 functions. Among 18 models evaluated, o3-mini performs best with a success rate of 52.7%, highlighting the difficulty of this task. Fine-tuning LLaMA-3.1-8B-Instruct on curated synthesis traces yields up to a 31% relative performance gain. CodeARC provides a more realistic and challenging testbed for evaluating LLM-based program synthesis and inductive reasoning.

[Arxiv](https://arxiv.org/abs/2503.23145)