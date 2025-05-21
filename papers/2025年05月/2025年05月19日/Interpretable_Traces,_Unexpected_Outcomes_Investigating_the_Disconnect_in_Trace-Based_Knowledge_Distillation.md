# 可解释的轨迹，意外的结果：探究基于轨迹知识蒸馏中的脱节现象

发布时间：2025年05月19日

`LLM应用

论文摘要：问答系统（QA）在当今的交互式对话系统（如ChatGPT、Perplexity、Microsoft Copilot等）时代面临双重挑战：用户既要求模型输出准确，又要求结果透明。小型语言模型（SLMs）虽然在计算效率上优于大型模型，但性能往往不尽如人意。为解决这一问题，知识蒸馏（KD）方法为优化小型模型提供了有效途径。

近期研究中，思维链（Chain-of-Thought, CoT）或推理模型（如DeepSeek R1）生成的中间标记或“推理”轨迹被引入作为训练信号。然而，这些推理轨迹常因冗长而难以解读和评估。本研究聚焦于这一问题，旨在探索如何评估这些推理轨迹的忠实性及其与最终性能的相关性。

我们采用了一种基于规则的问题分解的知识蒸馏方法。该方法通过将复杂查询分解为结构化的子问题，生成可解释的推理轨迹，其正确性甚至可以在推理过程中实时验证。以Open Book QA为例，我们将问题分解为分类和信息检索两个步骤，显著简化了轨迹评估过程。

实验结果令人深思：在CoTemp QA、Microsoft机器阅读理解QA和Facebook bAbI QA数据集上，即使推理轨迹正确，模型也不一定输出正确答案。同时，正确答案与中间推理轨迹的正确性之间相关性较低。这些发现挑战了利用推理轨迹提升小型模型性能的传统假设，为未来研究提供了重要启示。

LLM应用` `问答系统` `知识蒸馏`

> Interpretable Traces, Unexpected Outcomes: Investigating the Disconnect in Trace-Based Knowledge Distillation

# 摘要

> 问答系统（QA）在当今的交互式对话系统（如ChatGPT、Perplexity、Microsoft Copilot等）时代面临双重挑战：用户既要求模型输出准确，又要求结果透明。小型语言模型（SLMs）虽然在计算效率上优于大型模型，但性能往往不尽如人意。为解决这一问题，知识蒸馏（KD）方法为优化小型模型提供了有效途径。

近期研究中，思维链（Chain-of-Thought, CoT）或推理模型（如DeepSeek R1）生成的中间标记或“推理”轨迹被引入作为训练信号。然而，这些推理轨迹常因冗长而难以解读和评估。本研究聚焦于这一问题，旨在探索如何评估这些推理轨迹的忠实性及其与最终性能的相关性。

我们采用了一种基于规则的问题分解的知识蒸馏方法。该方法通过将复杂查询分解为结构化的子问题，生成可解释的推理轨迹，其正确性甚至可以在推理过程中实时验证。以Open Book QA为例，我们将问题分解为分类和信息检索两个步骤，显著简化了轨迹评估过程。

实验结果令人深思：在CoTemp QA、Microsoft机器阅读理解QA和Facebook bAbI QA数据集上，即使推理轨迹正确，模型也不一定输出正确答案。同时，正确答案与中间推理轨迹的正确性之间相关性较低。这些发现挑战了利用推理轨迹提升小型模型性能的传统假设，为未来研究提供了重要启示。


> Question Answering (QA) poses a challenging and critical problem, particularly in today's age of interactive dialogue systems such as ChatGPT, Perplexity, Microsoft Copilot, etc. where users demand both accuracy and transparency in the model's outputs. Since smaller language models (SLMs) are computationally more efficient but often under-perform compared to larger models, Knowledge Distillation (KD) methods allow for finetuning these smaller models to improve their final performance. Lately, the intermediate tokens or the so called `reasoning' traces produced by Chain-of-Thought (CoT) or by reasoning models such as DeepSeek R1 are used as a training signal for KD. However, these reasoning traces are often verbose and difficult to interpret or evaluate. In this work, we aim to address the challenge of evaluating the faithfulness of these reasoning traces and their correlation with the final performance. To this end, we employ a KD method leveraging rule-based problem decomposition. This approach allows us to break down complex queries into structured sub-problems, generating interpretable traces whose correctness can be readily evaluated, even at inference time. Specifically, we demonstrate this approach on Open Book QA, decomposing the problem into a Classification step and an Information Retrieval step, thereby simplifying trace evaluation. Our SFT experiments with correct and incorrect traces on the CoTemp QA, Microsoft Machine Reading Comprehension QA, and Facebook bAbI QA datasets reveal the striking finding that correct traces do not necessarily imply that the model outputs the correct final solution. Similarly, we find a low correlation between correct final solutions and intermediate trace correctness. These results challenge the implicit assumption behind utilizing reasoning traces for improving SLMs' final performance via KD.

[Arxiv](https://arxiv.org/abs/2505.13792)