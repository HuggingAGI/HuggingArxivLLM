# 互动学习：现实环境中自适应智能体的数据驱动框架

发布时间：2025年01月18日

`Agent

理由：这篇论文主要讨论了如何通过Learn-by-interact框架使LLM代理适应各种环境，并通过合成数据提升代理在多种任务中的表现。论文的核心关注点是LLM代理的自主性和适应性，特别是在不同环境中的交互和任务执行能力。因此，这篇论文应归类为Agent。` `自动化` `软件开发`

> Learn-by-interact: A Data-Centric Framework for Self-Adaptive Agents in Realistic Environments

# 摘要

> # 摘要
由大型语言模型（LLMs）驱动的自主代理有望增强人类能力，协助完成从发送邮件到数据分析等数字任务。然而，现有LLMs在这些任务中的表现常受限于缺乏高质量的环境交互数据。为此，我们提出了Learn-by-interact框架，无需人工标注即可使LLM代理适应任何环境。该框架基于文档合成代理-环境交互轨迹，并通过总结或抽象交互历史构建指令，这一过程称为反向构建。我们通过在训练和上下文学习（ICL）中使用这些合成数据评估其质量，并设计了针对代理优化的创新检索方法。在SWE-bench、WebArena、OSWorld和Spider2-V上的广泛实验表明，Learn-by-interact在编码、网络和桌面环境中的下游代理任务中表现出色——使用Claude-3.5的ICL基线结果提升了12.2%，使用Codestral-22B的训练结果提升了19.5%。反向构建在训练中贡献了高达14.0%的改进。消融实验进一步证明，我们的合成数据在ICL中高效，且检索管道优于传统检索增强生成（RAG）等方法。随着LLMs在现实环境中的广泛应用，Learn-by-interact有望成为代理数据合成的基石。

> Autonomous agents powered by large language models (LLMs) have the potential to enhance human capabilities, assisting with digital tasks from sending emails to performing data analysis. The abilities of existing LLMs at such tasks are often hindered by the lack of high-quality agent data from the corresponding environments they interact with. We propose Learn-by-interact, a data-centric framework to adapt LLM agents to any given environments without human annotations. Learn-by-interact synthesizes trajectories of agent-environment interactions based on documentations, and constructs instructions by summarizing or abstracting the interaction histories, a process called backward construction. We assess the quality of our synthetic data by using them in both training-based scenarios and training-free in-context learning (ICL), where we craft innovative retrieval approaches optimized for agents. Extensive experiments on SWE-bench, WebArena, OSWorld and Spider2-V spanning across realistic coding, web, and desktop environments show the effectiveness of Learn-by-interact in various downstream agentic tasks -- baseline results are improved by up to 12.2\% for ICL with Claude-3.5 and 19.5\% for training with Codestral-22B. We further demonstrate the critical role of backward construction, which provides up to 14.0\% improvement for training. Our ablation studies demonstrate the efficiency provided by our synthesized data in ICL and the superiority of our retrieval pipeline over alternative approaches like conventional retrieval-augmented generation (RAG). We expect that Learn-by-interact will serve as a foundation for agent data synthesis as LLMs are increasingly deployed at real-world environments.

[Arxiv](https://arxiv.org/abs/2501.10893)