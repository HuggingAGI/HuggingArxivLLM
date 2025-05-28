# Amulet：借助LLM评估，让复杂多轮对话接受考验

发布时间：2025年05月26日

`LLM应用` `对话系统`

> Amulet: Putting Complex Multi-Turn Conversations on the Stand with LLM Juries

# 摘要

> 如今，大型语言模型被广泛用作评估其他语言模型生成内容的裁判。因此，对这些LLM裁判进行基准测试并提升其在实际语言模型应用中的表现至关重要。典型的‘人-助理’对话往往冗长且话题多样，每一轮对话在主题、意图和需求上都显示出显著差异，例如社交互动、任务请求、反馈等。

我们提出了Amulet框架，该框架利用对话行为和礼貌准则的相关语言学概念，来提升LLM裁判在具有复杂多轮对话背景的偏好数据上的准确性。Amulet提供了关于（a）对话中存在的交流结构和意图（对话行为），以及（b）偏好回应对会话原则（礼貌准则）的满足情况的有价值的见解，并利用这些见解进行判断。

在四个具有挑战性的数据集上，Amulet表明（a）人类在对话的每一轮中经常（60%到70%的时间）改变他们的意图，以及（b）在75%的情况下，可以通过对话行为和/或礼貌准则区分偏好回应，这再次强调了后者在评估此类数据中的重要性。

Amulet可以作为单独的裁判使用，也可以集成到由不同LLM裁判组成的陪审团中；我们的裁判和陪审团在所有四个数据集的相关基准上都表现出显著改进。

> Today, large language models are widely used as judges to evaluate responses from other language models. Hence, it is imperative to benchmark and improve these LLM-judges on real-world language model usage: a typical human-assistant conversation is lengthy, and shows significant diversity in topics, intents, and requirements across turns, e.g. social interactions, task requests, feedback. We present Amulet, a framework that leverages pertinent linguistic concepts of dialog-acts and maxims to improve the accuracy of LLM-judges on preference data with complex, multi-turn conversational context. Amulet presents valuable insights about (a) the communicative structures and intents present in the conversation (dialog acts), and (b) the satisfaction of conversational principles (maxims) by the preference responses, and uses them to make judgments. On four challenging datasets, Amulet shows that (a) humans frequently (60 to 70 percent of the time) change their intents from one turn of the conversation to the next, and (b) in 75 percent of instances, the preference responses can be differentiated via dialog acts and/or maxims, reiterating the latter's significance in judging such data. Amulet can be used either as a judge by applying the framework to a single LLM, or integrated into a jury with different LLM judges; our judges and juries show strong improvements on relevant baselines for all four datasets.

[Arxiv](https://arxiv.org/abs/2505.20451)