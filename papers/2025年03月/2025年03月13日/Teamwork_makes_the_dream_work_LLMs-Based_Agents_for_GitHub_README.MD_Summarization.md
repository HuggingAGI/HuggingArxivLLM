# 齐心协力成就目标：基于LLMs的GitHub README.MD智能摘要

发布时间：2025年03月13日

`Agent` `软件工程` `人工智能`

> Teamwork makes the dream work: LLMs-Based Agents for GitHub README.MD Summarization

# 摘要

> 近年来，大型语言模型（LLMs）的普及引领了多个领域的广泛应用。这些经过海量多源数据训练的模型，能够胜任包括软件工程（SE）在内的多种任务。尽管它们已获得广泛应用，但LLMs的协同潜力尚未得到充分挖掘。本文提出了一种名为Metagente的新方法，旨在最大化各种LLMs的协同效应。Metagente是一个基于多智能体的框架，通过评估、反馈和专门化智能体间的协作实现系统的自我优化。该框架营造了一个环境，使多个智能体能够从不同角度反复精炼和优化提示。随后，一个教师智能体会对这些探索结果进行审查和聚合。为了验证其性能，我们采用软件工程中的README.MD文件总结任务对Metagente进行了评估，并将其与GitSum、LLaMA-2和GPT-4o三个成熟基线进行了对比。结果显示，Metagente不仅数据需求少，且准确度高，显著超越了基线。与最相关的基准GitSum相比，性能提升幅度高达27.63%至60.43%。尤为值得一提的是，相较于单一LLM，Metagente将准确率提升了数倍。

> The proliferation of Large Language Models (LLMs) in recent years has realized many applications in various domains. Being trained with a huge of amount of data coming from various sources, LLMs can be deployed to solve different tasks, including those in Software Engineering (SE). Though they have been widely adopted, the potential of using LLMs cooperatively has not been thoroughly investigated. In this paper, we proposed Metagente as a novel approach to amplify the synergy of various LLMs. Metagente is a Multi-Agent framework based on a series of LLMs to self-optimize the system through evaluation, feedback, and cooperation among specialized agents. Such a framework creates an environment where multiple agents iteratively refine and optimize prompts from various perspectives. The results of these explorations are then reviewed and aggregated by a teacher agent. To study its performance, we evaluated Metagente with an SE task, i.e., summarization of README.MD files, and compared it with three well-established baselines, i.e., GitSum, LLaMA-2, and GPT-4o. The results show that our proposed approach works efficiently and effectively, consuming a small amount of data for fine-tuning but still getting a high accuracy, thus substantially outperforming the baselines. The performance gain compared to GitSum, the most relevant benchmark, ranges from 27.63% to 60.43%. More importantly, compared to using only one LLM, Metagente boots up the accuracy to multiple folds.

[Arxiv](https://arxiv.org/abs/2503.10876)