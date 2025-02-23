# 多样化思考，提升推理：LLM通过选项流实现更优推理能力

发布时间：2025年02月18日

`Agent` `机器学习` `AUTOML`

> Flow-of-Options: Diversified and Improved LLM Reasoning by Thinking Through Options

# 摘要

> 我们提出了一种名为选项流（Flow-of-Options，FoO）的新推理方法，旨在解决大型语言模型（LLMs）中的内在偏见问题。FoO使LLMs能够系统性地在推理过程中探索多样化的可能性，这一点通过一个基于FoO的智能体系统得到了验证，该系统能够自主解决机器学习任务（AutoML）。我们的框架超越了现有的先进基线，在标准数据科学任务上实现了38.2%至69.2%的性能提升，在治疗化学任务上则达到了37.4%至47.9%的提升。由于每项任务的总操作成本低于1美元，我们的框架非常适合成本敏感型应用场景。除了分类和回归任务外，我们还展示了基于FoO的智能体系统在强化学习和图像生成等任务中的更广泛应用。与当前最先进的AutoML智能体系统相比，我们的框架取得了显著的进步，这得益于FoO通过压缩、可解释的表示方式强制LLM解决方案多样化的能力，同时结合案例推理时还能支持长期记忆。

> We present a novel reasoning approach called Flow-of-Options (FoO), designed to address intrinsic biases in Large Language Models (LLMs). FoO enables LLMs to systematically explore a diverse range of possibilities in their reasoning, as demonstrated by an FoO-based agentic system for autonomously solving Machine Learning tasks (AutoML). Our framework outperforms state-of-the-art baselines, achieving improvements of 38.2% - 69.2% on standard data science tasks, and 37.4% - 47.9% on therapeutic chemistry tasks. With an overall operation cost under $1 per task, our framework is well-suited for cost-sensitive applications. Beyond classification and regression, we illustrate the broader applicability of our FoO-based agentic system to tasks such as reinforcement learning and image generation. Our framework presents significant advancements compared to current state-of-the-art agentic systems for AutoML, due to the benefits of FoO in enforcing diversity in LLM solutions through compressed, explainable representations that also support long-term memory when combined with case-based reasoning.

[Arxiv](https://arxiv.org/abs/2502.12929)