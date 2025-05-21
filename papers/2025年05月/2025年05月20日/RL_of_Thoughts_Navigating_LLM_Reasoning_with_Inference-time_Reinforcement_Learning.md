# 思想的强化学习：通过推理时强化学习引导大型语言模型推理

发布时间：2025年05月20日

`LLM理论` `人工智能`

> RL of Thoughts: Navigating LLM Reasoning with Inference-time Reinforcement Learning

# 摘要

> 尽管大型语言模型（LLMs）发展迅速，但其基于token的自回归特性限制了其复杂推理能力。为了提升LLM的推理能力，包括链式/树式/图式思维链在内的推理时技术成功地提高了性能，因为它们通过复杂的逻辑结构引导推理，而无需修改LLMs的参数，成本效益显著。然而，这些手动预定义的、与任务无关的框架被统一应用于各种任务中，缺乏适应性。

为了改进这一点，我们提出了RL-of-Thoughts（RLoT）。其中，我们使用强化学习（RL）训练一个轻量级导航模型，以在推理时自适应地增强LLM的推理能力。具体来说，我们从人类认知的角度设计了五个基本逻辑块。在推理过程中，经过训练的RL导航器会根据问题特征动态选择合适的逻辑块，并将其组合成特定任务的逻辑结构。

在多个推理基准测试（AIME、MATH、GPQA等）以及多种LLM（GPT、Llama、Qwen和DeepSeek）上的实验结果表明，RLoT比现有的推理时技术高出13.4%。值得一提的是，仅需不到3K参数，我们的RL导航器就能使100亿参数规模以下的LLM与1000亿参数规模的模型相媲美。此外，RL导航器表现出强大的迁移能力：在一个特定的LLM-任务对上训练的模型可以有效推广到未见过的LLM和任务。

我们的代码已开源，地址为https://anonymous.4open.science/r/RL-LLM-Reasoning-1A30，以供复现。

> Despite rapid advancements in large language models (LLMs), the token-level autoregressive nature constrains their complex reasoning capabilities. To enhance LLM reasoning, inference-time techniques, including Chain/Tree/Graph-of-Thought(s), successfully improve the performance, as they are fairly cost-effective by guiding reasoning through sophisticated logical structures without modifying LLMs' parameters. However, these manually predefined, task-agnostic frameworks are applied uniformly across diverse tasks, lacking adaptability. To improve this, we propose RL-of-Thoughts (RLoT), where we train a lightweight navigator model with reinforcement learning (RL) to adaptively enhance LLM reasoning at inference time. Specifically, we design five basic logic blocks from the perspective of human cognition. During the reasoning process, the trained RL navigator dynamically selects the suitable logic blocks and combines them into task-specific logical structures according to problem characteristics. Experiments across multiple reasoning benchmarks (AIME, MATH, GPQA, etc.) with multiple LLMs (GPT, Llama, Qwen, and DeepSeek) illustrate that RLoT outperforms established inference-time techniques by up to 13.4%. Remarkably, with less than 3K parameters, our RL navigator is able to make sub-10B LLMs comparable to 100B-scale counterparts. Moreover, the RL navigator demonstrates strong transferability: a model trained on one specific LLM-task pair can effectively generalize to unseen LLMs and tasks. Our code is open-source at https://anonymous.4open.science/r/RL-LLM-Reasoning-1A30 for reproducibility.

[Arxiv](https://arxiv.org/abs/2505.14140)