# BriLLM：灵感源自大脑的大型语言模型

发布时间：2025年03月14日

`LLM理论` `人工智能` `脑科学`

> BriLLM: Brain-inspired Large Language Model

# 摘要

> 本文介绍了首个脑启发式大型语言模型（BriLLM），它是一款非Transformer、非GPT、非传统机器学习输入-输出控制的生成语言模型。该模型基于有向图中神经网络的Signal Fully-connected flowing（SiFu）定义，实现了整个模型图中所有节点的可解释性，而传统机器学习模型仅在输入和输出端具有有限的可解释性。在语言模型场景中，token被定义为图中的一个节点。一个随机形状或用户定义的信号流根据“最小阻力”原则在节点之间流动。待预测或生成的下一个token或节点是信号流的目标。作为语言模型，BriLLM在模型大小与输入和预测长度无关时，理论上支持无限长的【数学公式】模型。模型的工作信号流提供了类似于人类大脑认知模式的回忆激活和先天多模态支持的可能性。目前，我们发布了首个中文版BriLLM，拥有4000个token，32维节点宽度，16-token长序列预测能力，以及与GPT-1相当的语言模型预测性能。更多的计算能力将帮助我们探索上述无限的可能性。

> This paper reports the first brain-inspired large language model (BriLLM). This is a non-Transformer, non-GPT, non-traditional machine learning input-output controlled generative language model. The model is based on the Signal Fully-connected flowing (SiFu) definition on the directed graph in terms of the neural network, and has the interpretability of all nodes on the graph of the whole model, instead of the traditional machine learning model that only has limited interpretability at the input and output ends. In the language model scenario, the token is defined as a node in the graph. A randomly shaped or user-defined signal flow flows between nodes on the principle of "least resistance" along paths. The next token or node to be predicted or generated is the target of the signal flow. As a language model, BriLLM theoretically supports infinitely long $n$-gram models when the model size is independent of the input and predicted length of the model. The model's working signal flow provides the possibility of recall activation and innate multi-modal support similar to the cognitive patterns of the human brain. At present, we released the first BriLLM version in Chinese, with 4000 tokens, 32-dimensional node width, 16-token long sequence prediction ability, and language model prediction performance comparable to GPT-1. More computing power will help us explore the infinite possibilities depicted above.

[Arxiv](https://arxiv.org/abs/2503.11299)