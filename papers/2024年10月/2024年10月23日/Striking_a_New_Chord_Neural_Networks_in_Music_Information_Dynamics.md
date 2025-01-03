# 谱写新篇章：神经网络在音乐信息动态中的创新应用

发布时间：2024年10月23日

`LLM应用

理由：这篇论文主要探讨了神经网络模型（包括LSTM、Transformer和GPT）在音乐事件预测中的应用，并与传统的统计模型进行了比较。虽然论文中提到了GPT模型，但重点在于这些模型在音乐序列建模中的实际应用，而不是对LLM理论的深入探讨或LLM作为Agent的应用。因此，将其归类为“LLM应用”更为合适。` `神经科学`

> Striking a New Chord: Neural Networks in Music Information Dynamics

# 摘要

> # 摘要
为了通过信息动力学的视角揭示音乐美学的复杂性，我们的研究深入探讨了音乐序列建模的领域，将音乐的顺序结构化特性与自然语言进行了类比。尽管神经网络模型在音乐信息检索（MIR）中普遍存在，但在音乐认知和音乐神经科学中，符号音乐事件的建模主要依赖于统计模型。在这篇“概念验证”论文中，我们提出了神经网络模型在预测音乐事件方面优于统计模型的观点。具体来说，我们比较了LSTM、Transformer和GPT模型与广泛使用的马尔可夫模型在预测一系列和弦后的和弦事件方面的表现。利用McGill Billboard数据集中的和弦序列，我们训练了每个模型以从给定的和弦序列中预测下一个和弦。我们发现，在我们的研究中，神经网络模型显著优于统计模型。具体来说，带有注意力机制的LSTM模型以0.85的准确率领先，其次是Transformer模型（0.58）、带有GPT头的Transformer模型（0.56）和标准LSTM模型（0.43）。可变阶马尔可夫模型和马尔可夫模型分别以0.31和0.23的准确率落后。受到这些结果的鼓舞，我们将研究扩展到多维建模，采用了多对一LSTM、带有注意力机制的LSTM、Transformer和GPT预测器。这些模型在CoCoPops Billboard数据集上使用和弦和旋律线作为二维数据进行训练，在预测下一个和弦时分别达到了0.21、0.56、0.39和0.24的准确率。

> Initiating a quest to unravel the complexities of musical aesthetics through the lens of information dynamics, our study delves into the realm of musical sequence modeling, drawing a parallel between the sequential structured nature of music and natural language.
  Despite the prevalence of neural network models in MIR, the modeling of symbolic music events as applied to music cognition and music neuroscience has largely relied on statistical models. In this "proof of concept" paper we posit the superiority of neural network models over statistical models for predicting musical events. Specifically, we compare LSTM, Transformer, and GPT models against a widely-used markov model to predict a chord event following a sequence of chords.
  Utilizing chord sequences from the McGill Billboard dataset, we trained each model to predict the next chord from a given sequence of chords. We found that neural models significantly outperformed statistical ones in our study. Specifically, the LSTM with attention model led with an accuracy of 0.85, followed by Transformer models at 0.58, Transformer with GPT head at 0.56, and standard LSTM at 0.43. Variable Order Markov and Markov trailed behind with accuracies of 0.31 and 0.23, respectively. Encouraged by these results, we extended our investigation to multidimensional modeling, employing a many-to-one LSTM, LSTM with attention, Transformer, and GPT predictors. These models were trained on both chord and melody lines as two-dimensional data using the CoCoPops Billboard dataset, achieving an accuracy of 0.21, 0.56, 0.39, and 0.24 respectively in predicting the next chord.

[Arxiv](https://arxiv.org/abs/2410.17989)