# Delta-KNN：优化阿尔茨海默病检测中的ICL演示选择

发布时间：2025年06月03日

`LLM应用`

> Delta-KNN: Improving Demonstration Selection in In-Context Learning for Alzheimer's Disease Detection

# 摘要

> 阿尔茨海默病（AD）是一种渐进性神经退行性疾病，导致痴呆症，早期干预可以通过分析语言异常获益。本研究中，我们探讨了大型语言模型（LLMs）作为健康助手，通过上下文学习（ICL）从患者生成文本中进行 AD 诊断的潜力，其中任务通过少量输入-输出示例定义。实证结果表明，传统 ICL 方法，如基于相似度的示例选择，在 AD 诊断中表现不佳，这可能归因于该任务的固有复杂性。为此，我们引入了 Delta-KNN，这是一种新型的示例选择策略，能够提升 ICL 的性能。我们的方法利用一个 delta 分数来评估每个训练示例的相对增益，并结合一个基于 KNN 的检索器，动态选择给定输入的最优“代表”。在两个 AD 检测数据集上，针对三个开源 LLM 的实验表明，Delta-KNN 一致优于现有的 ICL 基线。值得注意的是，使用 Llama-3.1 模型时，我们的方法实现了新的最先进结果，甚至超越了监督分类器。

> Alzheimer's Disease (AD) is a progressive neurodegenerative disorder that leads to dementia, and early intervention can greatly benefit from analyzing linguistic abnormalities. In this work, we explore the potential of Large Language Models (LLMs) as health assistants for AD diagnosis from patient-generated text using in-context learning (ICL), where tasks are defined through a few input-output examples. Empirical results reveal that conventional ICL methods, such as similarity-based selection, perform poorly for AD diagnosis, likely due to the inherent complexity of this task. To address this, we introduce Delta-KNN, a novel demonstration selection strategy that enhances ICL performance. Our method leverages a delta score to assess the relative gains of each training example, coupled with a KNN-based retriever that dynamically selects optimal "representatives" for a given input. Experiments on two AD detection datasets across three open-source LLMs demonstrate that Delta-KNN consistently outperforms existing ICL baselines. Notably, when using the Llama-3.1 model, our approach achieves new state-of-the-art results, surpassing even supervised classifiers.

[Arxiv](https://arxiv.org/abs/2506.03476)