# InnerThoughts: 大型语言模型中的表示与预测解耦

发布时间：2025年01月29日

`LLM理论

理由：这篇论文主要探讨了如何通过改进大型语言模型（LLMs）的内部表示和预测机制来提升其性能。具体来说，它提出了一种新的方法，通过训练一个独立的神经网络预测模块来利用LLMs的隐藏状态，从而解耦表示能力和预测能力。这种研究属于对LLMs内部机制的理论探索和改进，因此归类为“LLM理论”。` `机器学习`

> InnerThoughts: Disentangling Representations and Predictions in Large Language Models

# 摘要

> 大型语言模型（LLMs）蕴含丰富的事实知识，通常通过多项选择题提示来提取。模型内部通过多层Transformer处理提示，在隐藏状态中构建问题的不同表示。然而，最终仅使用最后一层和标记位置的隐藏状态来预测答案标签。本研究提出了一种新方法：在训练问题集上学习一个独立的神经网络预测模块，该模块以最后一层所有时间位置的隐藏状态为输入，输出预测结果。这一框架将LLMs的表示能力与预测能力解耦。在多个高难度基准测试中，我们的方法显著提升了性能，有时甚至媲美监督微调，但计算成本却大幅降低。

> Large language models (LLMs) contain substantial factual knowledge which is commonly elicited by multiple-choice question-answering prompts. Internally, such models process the prompt through multiple transformer layers, building varying representations of the problem within its hidden states. Ultimately, however, only the hidden state corresponding to the final layer and token position are used to predict the answer label. In this work, we propose instead to learn a small separate neural network predictor module on a collection of training questions, that take the hidden states from all the layers at the last temporal position as input and outputs predictions. In effect, such a framework disentangles the representational abilities of LLMs from their predictive abilities. On a collection of hard benchmarks, our method achieves considerable improvements in performance, sometimes comparable to supervised fine-tuning procedures, but at a fraction of the computational cost.

[Arxiv](https://arxiv.org/abs/2501.17994)