# BED-LLM：基于大型语言模型与贝叶斯实验设计的智能信息收集

发布时间：2025年08月28日

`Agent` `基础理论`

> BED-LLM: Intelligent Information Gathering with LLMs and Bayesian Experimental Design

# 摘要

> 我们提出一种通用方法，借助序贯贝叶斯实验设计（BED）框架，提升大型语言模型（LLMs）从用户或其他外部来源智能、自适应收集信息的能力。这让LLMs能成为高效的多轮对话智能体，与外部环境进行交互式交互。我们将此方法命名为BED-LLM（基于大型语言模型的贝叶斯实验设计），它通过迭代选择问题或查询来实现——这些问题或查询能基于先前收集的响应，最大化关于目标任务的预期信息增益（EIG）。我们还展示了如何基于LLM的信念分布构建概率模型，从而以规范的方式定义EIG，并深入解析了其构建过程中的关键决策。此外，BED-LLM的成功还得益于多项具体创新，例如精心设计的EIG估计器、不完全依赖上下文内更新来处理历史响应，以及生成候选查询的针对性策略。实验结果表明，与直接提示LLM及其他自适应设计策略相比，BED-LLM在基于20问游戏的各类测试中，以及在利用LLM主动推断用户偏好的任务中，均实现了显著的性能提升。

> We propose a general-purpose approach for improving the ability of Large Language Models (LLMs) to intelligently and adaptively gather information from a user or other external source using the framework of sequential Bayesian experimental design (BED). This enables LLMs to act as effective multi-turn conversational agents and interactively interface with external environments. Our approach, which we call BED-LLM (Bayesian Experimental Design with Large Language Models), is based on iteratively choosing questions or queries that maximize the expected information gain (EIG) about the task of interest given the responses gathered previously. We show how this EIG can be formulated in a principled way using a probabilistic model derived from the LLM's belief distribution and provide detailed insights into key decisions in its construction. Further key to the success of BED-LLM are a number of specific innovations, such as a carefully designed estimator for the EIG, not solely relying on in-context updates for conditioning on previous responses, and a targeted strategy for proposing candidate queries. We find that BED-LLM achieves substantial gains in performance across a wide range of tests based on the 20-questions game and using the LLM to actively infer user preferences, compared to direct prompting of the LLM and other adaptive design strategies.

[Arxiv](https://arxiv.org/abs/2508.21184)