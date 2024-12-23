# “代码之树”：复杂任务处理中用于端到端代码生成与执行的树状结构探索框架

发布时间：2024年12月19日

`Agent` `智能体` `代码生成`

> Tree-of-Code: A Tree-Structured Exploring Framework for End-to-End Code Generation and Execution in Complex Task Handling

# 摘要

> 解决复杂推理任务是智能体在现实世界中的关键应用之一。得益于大型语言模型（LLMs）在代码数据上的预训练，诸如 CodeAct 之类的近期方法成功地将代码用作 LLM 智能体的行动，取得了不错的成果。然而，CodeAct 依赖碎片化的思路贪婪地生成下一个行动的代码块，致使出现不一致和不稳定的情况。此外，CodeAct 缺少与行动相关的真实值（GT），这使得其在多轮交互中的监督信号和终止条件存疑。为解决这些问题，我们首先引入了一种简单却有效的端到端代码生成范式——CodeProgram，它借助代码的系统逻辑与全局推理相契合，实现了具有凝聚力的问题解决。接着，我们提出了代码树（ToC），它基于代码的可执行性自生长 CodeProgram 节点，并在无真实值的场景中实现自我监督。在使用十个流行的零样本 LLM 的两个数据集上的实验结果显示，ToC 比 CodeAct 的准确率显著提高了近 20%，且轮数不到 1/4。有几个 LLM 在一轮 CodeProgram 上的表现甚至优于在多轮 CodeAct 上的表现。为进一步探究效率与效果之间的权衡，我们测试了不同的 ToC 树大小和探索机制。我们还凸显了 ToC 端到端数据生成在监督和强化微调方面的潜力。

> Solving complex reasoning tasks is a key real-world application of agents. Thanks to the pretraining of Large Language Models (LLMs) on code data, recent approaches like CodeAct successfully use code as LLM agents' action, achieving good results. However, CodeAct greedily generates the next action's code block by relying on fragmented thoughts, resulting in inconsistency and instability. Moreover, CodeAct lacks action-related ground-truth (GT), making its supervision signals and termination conditions questionable in multi-turn interactions. To address these issues, we first introduce a simple yet effective end-to-end code generation paradigm, CodeProgram, which leverages code's systematic logic to align with global reasoning and enable cohesive problem-solving. Then, we propose Tree-of-Code (ToC), which self-grows CodeProgram nodes based on the executable nature of the code and enables self-supervision in a GT-free scenario. Experimental results on two datasets using ten popular zero-shot LLMs show ToC remarkably boosts accuracy by nearly 20% over CodeAct with less than 1/4 turns. Several LLMs even perform better on one-turn CodeProgram than on multi-turn CodeAct. To further investigate the trade-off between efficacy and efficiency, we test different ToC tree sizes and exploration mechanisms. We also highlight the potential of ToC's end-to-end data generation for supervised and reinforced fine-tuning.

[Arxiv](https://arxiv.org/abs/2412.15305)