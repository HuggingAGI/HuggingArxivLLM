# 打造一个专为化学设计的科学推理模型

发布时间：2025年06月04日

`LLM应用`

> Training a Scientific Reasoning Model for Chemistry

# 摘要

> 推理模型是一种大型语言模型，在回答问题前会输出一长串的思考过程，不仅提供了更高的准确性，还展示了清晰的推理过程。一个主要问题是，语言模型的推理能力是否能超越数学、编程和逻辑等领域，这些领域是大多数先前研究的重点。我们展示了推理模型可以在不进行额外领域预训练的情况下，通过后训练适应化学领域，并且所需的数据量远低于当前领域特定模型。我们介绍了ether0，这是一个拥有240亿参数的大型语言模型（基于Mistral-Small-24B），能够以自然语言进行推理，并以化学结构形式给出回答。这个推理模型通过强化学习在640,730个实验验证的化学问题上进行训练，涵盖375个任务，从合成可行性到血脑屏障通透性，再到人类受体活性和气味。我们的模型在分子设计任务中超越了通用化学模型、前沿模型和人类专家，同时相较于专用模型也更为数据高效。我们预计这种方法可以用于训练高效的语言模型，使其专注于广泛科学领域的各种任务。

> Reasoning models are large language models that emit a long chain-of-thought before answering, providing both higher accuracy and explicit reasoning for their response. A major question has been whether language model reasoning generalizes beyond mathematics, programming, and logic, where most previous work has focused. We demonstrate that reasoning models can be post-trained for chemistry without additional domain pretraining, and require substantially less data compared to contemporary domain-specific models. We report ether0, a 24B parameter LLM (based on Mistral-Small-24B) that can reason in natural language and respond with chemical structures. This reasoning model was trained with reinforcement learning on 640,730 experimentally-grounded chemistry problems across 375 tasks ranging from synthesizability, to blood-brain barrier permeability, to human receptor activity, to scent. Our model exceeds general-purpose chemistry models, frontier models, and human experts on molecular design tasks. It is also more data efficient relative to specialized models. We anticipate that this method can be applied to train data-efficient language models specialized for tasks across a wide variety of scientific domains.

[Arxiv](https://arxiv.org/abs/2506.17238)