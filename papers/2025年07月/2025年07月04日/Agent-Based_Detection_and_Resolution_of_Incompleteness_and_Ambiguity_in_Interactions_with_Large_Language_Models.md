# 基于智能体的不完整性与歧义性检测及解决：与大型语言模型的交互研究

发布时间：2025年07月04日

`Agent` `问答系统`

> Agent-Based Detection and Resolution of Incompleteness and Ambiguity in Interactions with Large Language Models

# 摘要

> 如今，我们许多人将大型语言模型（LLMs）视为现代的预言者，几乎可以向它们提出任何问题。然而，咨询LLM并不一定是一次性的活动。如果只是通过推理来澄清上下文信息，冗长的多轮交互可能会变得乏味。本文探讨了使用基于代理的架构来增强LLM驱动的问答系统，赋予其额外的推理能力。我们研究了通过基于LLM代理实现的转换器来自动解决潜在的问题不完整性和模糊性。我们专注于几个已知包含不同程度这些缺陷的基准数据集。我们为不同的LLMs（GPT-3.5-Turbo 和 Llama-4-Scout）配备了代理，这些代理充当检测和解决不完整性和模糊性缺陷的专家。代理以零样本ReAct代理的形式实现。模型现在不是在一步中生成答案，而是从三个动作中选择：a) 分类 b) 解决 c) 回答。动作a) 决定问题是否不完整、模糊或正常。动作b) 确定是否可以解决已识别的任何缺陷。动作c) 回答已解决形式的问题。我们比较了使用和不使用这些组件的代理的LLMs的使用情况。我们的结果显示，使用带有转换器的代理有以下优势：1）与人类的交互长度缩短；2）答案质量提高；3）对问题中缺陷的可解释性解决。另一方面，我们发现虽然可能会导致额外的LLM调用，且在某些情况下增加延迟。但在测试的数据集上，除了问题本身已经具有足够上下文的情况外，优势超过了成本。这表明基于代理的方法可能是利用LLMs的力量来开发更 robust 问答系统的有用机制。

> Many of us now treat LLMs as modern-day oracles asking it almost any kind of question. However, consulting an LLM does not have to be a single turn activity. But long multi-turn interactions can get tedious if it is simply to clarify contextual information that can be arrived at through reasoning. In this paper, we examine the use of agent-based architecture to bolster LLM-based Question-Answering systems with additional reasoning capabilities. We examine the automatic resolution of potential incompleteness or ambiguities in questions by transducers implemented using LLM-based agents. We focus on several benchmark datasets that are known to contain questions with these deficiencies to varying degrees. We equip different LLMs (GPT-3.5-Turbo and Llama-4-Scout) with agents that act as specialists in detecting and resolving deficiencies of incompleteness and ambiguity. The agents are implemented as zero-shot ReAct agents. Rather than producing an answer in a single step, the model now decides between 3 actions a) classify b) resolve c) answer. Action a) decides if the question is incomplete, ambiguous, or normal. Action b) determines if any deficiencies identified can be resolved. Action c) answers the resolved form of the question. We compare the use of LLMs with and without the use of agents with these components. Our results show benefits of agents with transducer 1) A shortening of the length of interactions with human 2) An improvement in the answer quality and 3) Explainable resolution of deficiencies in the question. On the negative side we find while it may result in additional LLM invocations and in some cases, increased latency. But on tested datasets, the benefits outweigh the costs except when questions already have sufficient context. Suggesting the agent-based approach could be a useful mechanism to harness the power of LLMs to develop more robust QA systems.

[Arxiv](https://arxiv.org/abs/2507.03726)