# Lachesis：借助推理路径的结构特性来预测 LLM 的推理准确性

发布时间：2024年12月11日

`LLM应用` `语言模型` `推理技术`

> Lachesis: Predicting LLM Inference Accuracy using Structural Properties of Reasoning Paths

# 摘要

> 大型语言模型日益用于构建代理，以执行更复杂的任务。当大型语言模型通过更长久的交互进行更复杂的推理时，自我一致性，也就是通过对多个独立推理进行抽样和边缘化所得答案更可能正确的这一理念，作为一种简便的验证技术备受关注。本文旨在依据推理路径样本的属性来预测通过自我一致性获取的答案的正确性，从而对这一直觉性假设进行实证验证。我们引入了 Lachesis，这是一个基于大型语言模型自我一致性推理的预测模型，并使用近期提出的基于大型语言模型的故障定位技术 AutoFL 作为运用自我一致性的目标技术对其进行了实证评估。Lachesis 利用专门设计的推理路径表示对从 AutoFL 收集的推理路径加以转换，并训练 LSTM 和 GCN 模型来预测给定的一组推理路径是否会得出正确答案。结果显示，Lachesis 预测答案正确性的精度可达 0.8136，凸显了训练一个能够提前终止不太可能成功的推理的预测模型的可能性。

> Large Language Models are increasingly used to build agents to perform more complex tasks. As LLMs perform more complicated reasoning through longer interactions, self-consistency, i.e., the idea that the answer obtained from sampling and marginalising a number of multiple independent inferences is more likely to be correct, has received much attention as a simple validation technique. This paper aims to empirically verify this intuitive hypothesis by predicting the correctness of answers obtained using self-consistency from properties of the samples of reasoning paths. We introduce Lachesis, a predictive model for self-consistency based LLM inferences, and empirically evaluate it using AutoFL, a recently proposed LLM-based fault localisation technique, as the target technique that uses self-consistency. Lachesis converts collected reasoning paths from AutoFL using specifically designed reasoning path representations, and trains LSTM and GCN models to predict whether a given set of reasoning paths would result in a correct answer. The results suggest that Lachesis can predict the correctness of answers with a precision of up to 0.8136, highlighting the possibility of training a predictive model that can allow early termination of inferences that are not likely to be successful.

[Arxiv](https://arxiv.org/abs/2412.08281)