# MLGym：助力AI研究代理的前沿探索的新框架与基准

发布时间：2025年02月20日

`Agent` `机器学习` `AI研究`

> MLGym: A New Framework and Benchmark for Advancing AI Research Agents

# 摘要

> 我们推出Meta MLGym和MLGym-Bench——首个专为机器学习任务设计的Gym环境，旨在评估和开发大型语言模型（LLM）代理在AI研究任务中的表现。MLGym-bench包含来自计算机视觉、自然语言处理、强化学习和博弈论等领域的13个多样化且开放性的研究任务，完成这些任务需要涵盖从数据处理到模型训练的完整AI研究技能。我们在Claude-3.5-Sonnet、Llama-3.1 405B、GPT-4o、o1-preview和Gemini-1.5 Pro等前沿模型上进行了基准测试，发现这些模型虽能通过优化超参数改进基线表现，但尚未具备生成全新假设或算法的能力。我们的MLGym框架开放了任务扩展、模型评估、合成数据生成及新算法开发等功能，助力未来研究进一步提升LLM代理的AI研究能力。

> We introduce Meta MLGym and MLGym-Bench, a new framework and benchmark for evaluating and developing LLM agents on AI research tasks. This is the first Gym environment for machine learning (ML) tasks, enabling research on reinforcement learning (RL) algorithms for training such agents. MLGym-bench consists of 13 diverse and open-ended AI research tasks from diverse domains such as computer vision, natural language processing, reinforcement learning, and game theory. Solving these tasks requires real-world AI research skills such as generating new ideas and hypotheses, creating and processing data, implementing ML methods, training models, running experiments, analyzing the results, and iterating through this process to improve on a given task. We evaluate a number of frontier large language models (LLMs) on our benchmarks such as Claude-3.5-Sonnet, Llama-3.1 405B, GPT-4o, o1-preview, and Gemini-1.5 Pro. Our MLGym framework makes it easy to add new tasks, integrate and evaluate models or agents, generate synthetic data at scale, as well as develop new learning algorithms for training agents on AI research tasks. We find that current frontier models can improve on the given baselines, usually by finding better hyperparameters, but do not generate novel hypotheses, algorithms, architectures, or substantial improvements. We open-source our framework and benchmark to facilitate future research in advancing the AI research capabilities of LLM agents.

[Arxiv](https://arxiv.org/abs/2502.14499)