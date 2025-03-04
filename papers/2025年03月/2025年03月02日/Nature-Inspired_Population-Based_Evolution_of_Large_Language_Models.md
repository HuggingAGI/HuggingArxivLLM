# <翻译失败>

发布时间：2025年03月02日

`LLM应用` `人工智能` `进化算法`

> Nature-Inspired Population-Based Evolution of Large Language Models

# 摘要

> # 进化：驱动地球生命存续的引擎
进化，地球生命存续与繁衍的核心动力，以种群为单位进行繁殖。受此启发，本文正式定义了一个新兴问题——大型语言模型（LLMs）的种群进化，并提出了一种全新框架。该框架从一组初始的父代LLMs出发，通过四大核心操作推动种群进化：（i）交叉，融合不同父代模型的权重以生成子代LLMs；（ii）变异，对模型权重施加小规模随机变化以激发多样性；（iii）选择，优先保留高性能模型；（iv）传承，将父代的经验传递给子代LLMs。

仅需每项新任务200个样本，LLM种群即可快速适应当前任务，无需任何梯度计算。在12个数据集上的实验表明，我们的框架持续超越现有LLM融合与适应方法，相较于初始种群中最佳模型，准确率最高提升达54.8%。此外，我们的框架支持LLMs同时进化以适应多项新任务，有效扩展至40个模型规模的种群，并实现对未见过的预留任务的零样本泛化。

我们已在GitHub开源代码，并在HuggingFace上发布了从gemma-2-2b-it微调得到的10个父代LLMs权重，只需单张4090显卡（24GB显存）即可复现本框架，且性能无任何损失。

> Evolution, the engine behind the survival and growth of life on Earth, operates through the population-based process of reproduction. Inspired by this principle, this paper formally defines a newly emerging problem -- the population-based evolution of large language models (LLMs) -- and introduces a novel framework. Starting with a population of parent LLMs, our framework enables the population to evolve through four key operations: (i) crossover, merging the weights of different parents to create offspring LLMs, (ii) mutation, introducing small, random changes to model weights to foster diversity, (iii) selection, prioritizing high-performing models, and (iv) succession, transferring the learned experience from parent to offspring LLMs. With only 200 samples per new task, the LLM population evolves rapidly to adapt to the task at hand, without any gradients. Experiments on 12 datasets show that our framework consistently outperforms existing multi-LLM merging and adaptation methods, achieving accuracy gains of up to 54.8% over the best LLM in the initial population. Moreover, our framework allows for the evolution of LLMs across multiple new tasks simultaneously, scaling effectively with populations of up to 40 LLMs, and even zero-shot generalization to unseen held-out tasks. We have open-sourced the code on GitHub and released the weights of 10 parent LLMs, fine-tuned from gemma-2-2b-it, on HuggingFace$, enabling reproduction of our proposed framework using just a single 4090 GPU with 24GB memory, without any performance degradation.

[Arxiv](https://arxiv.org/abs/2503.01155)