# 关于不完整性和模糊性在与大型语言模型交互中作用的经验研究

发布时间：2025年03月23日

`LLM应用` `人机交互` `问答系统`

> An Empirical Study of the Role of Incompleteness and Ambiguity in Interactions with Large Language Models

# 摘要

> 自然语言作为人机交互的媒介早已被期待，随着大型语言模型（LLMs）令人惊叹的语言处理和生成能力的出现，这一领域正经历翻天覆地的变化。如今，我们许多人将LLMs视为现代的预言者，几乎可以向它提出任何问题。与德尔斐神庙的神谕不同，与LLM的交流不必局限于单轮对话；与皮媞亚不同，人们普遍认为，通过提供额外的上下文，可以改进LLMs的回答。

本文旨在研究在什么情况下需要与LLMs进行多轮交互才能成功获得问题答案，或者确定问题不可解答。我们提出了一种神经符号框架，用于建模人与LLM代理之间的交互。通过该框架，我们将问题的不完整性和模糊性定义为可以从交互中交换的消息中推断出的属性，并提供了基准问题的结果，其中答案的正确性取决于问题是否表现出不完整或模糊性（根据我们识别的属性）。

我们的结果显示，对于不完整或模糊性问题比例较高的数据集，通常需要多轮交互；并且，增加交互长度可以减少不完整或模糊性。结果还表明，我们对不完整性和模糊性的度量可以作为表征与LLM在问答问题上进行交互的有用工具。

> Natural language as a medium for human-computer interaction has long been anticipated, has been undergoing a sea-change with the advent of Large Language Models (LLMs) with startling capacities for processing and generating language. Many of us now treat LLMs as modern-day oracles, asking it almost any kind of question. Unlike its Delphic predecessor, consulting an LLM does not have to be a single-turn activity (ask a question, receive an answer, leave); and -- also unlike the Pythia -- it is widely acknowledged that answers from LLMs can be improved with additional context. In this paper, we aim to study when we need multi-turn interactions with LLMs to successfully get a question answered; or conclude that a question is unanswerable. We present a neural symbolic framework that models the interactions between human and LLM agents. Through the proposed framework, we define incompleteness and ambiguity in the questions as properties deducible from the messages exchanged in the interaction, and provide results from benchmark problems, in which the answer-correctness is shown to depend on whether or not questions demonstrate the presence of incompleteness or ambiguity (according to the properties we identify). Our results show multi-turn interactions are usually required for datasets which have a high proportion of incompleteness or ambiguous questions; and that that increasing interaction length has the effect of reducing incompleteness or ambiguity. The results also suggest that our measures of incompleteness and ambiguity can be useful tools for characterising interactions with an LLM on question-answeringproblems

[Arxiv](https://arxiv.org/abs/2503.17936)