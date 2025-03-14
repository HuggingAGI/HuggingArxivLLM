# 通过转化为符合性回归方法，为深度生成模型构建符合性预测集

发布时间：2025年03月13日

`LLM应用

理由：这篇论文探讨了如何通过黑盒深度生成模型（如大型语言模型）为给定输入生成有效且紧凑的预测集，并提出了一种名为GPS的算法。研究的重点在于模型的应用，特别是如何在代码生成和数学问题生成等任务中有效使用大型语言模型，因此属于LLM应用类别。` `软件工程`

> Conformal Prediction Sets for Deep Generative Models via Reduction to Conformal Regression

# 摘要

> 我们探讨如何通过从黑盒深度生成模型中采样输出（如软件代码和自然语言文本）为给定输入（如文本提示）生成有效且紧凑的预测集。预测集的有效性由用户自定义的二元可接受函数决定，具体取决于应用场景。例如，在代码生成任务中，要求预测集中至少有一个程序能够通过所有测试用例。为解决这一问题，我们提出了一种简单有效的符合性推断算法——生成预测集（GPS）。基于一组校准示例和对深度生成模型的黑盒访问权限，GPS能够生成具有可证明保证的预测集。GPS的核心思想是利用获得可接受输出所需的最小样本数量的分布中的内在结构，从而构建一种基于最小样本数量的简单符合性回归方法。实验结果表明，在使用不同大型语言模型进行代码和数学问题生成时，GPS在多个数据集上的表现显著优于现有方法。


> We consider the problem of generating valid and small prediction sets by sampling outputs (e.g., software code and natural language text) from a black-box deep generative model for a given input (e.g., textual prompt). The validity of a prediction set is determined by a user-defined binary admissibility function depending on the target application. For example, requiring at least one program in the set to pass all test cases in code generation application. To address this problem, we develop a simple and effective conformal inference algorithm referred to as Generative Prediction Sets (GPS). Given a set of calibration examples and black-box access to a deep generative model, GPS can generate prediction sets with provable guarantees. The key insight behind GPS is to exploit the inherent structure within the distribution over the minimum number of samples needed to obtain an admissible output to develop a simple conformal regression approach over the minimum number of samples. Experiments on multiple datasets for code and math word problems using different large language models demonstrate the efficacy of GPS over state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2503.10512)