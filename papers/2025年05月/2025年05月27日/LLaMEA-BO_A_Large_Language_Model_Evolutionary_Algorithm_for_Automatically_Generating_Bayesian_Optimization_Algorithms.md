# LLaMEA-BO：基于大型语言模型的进化算法，实现贝叶斯优化算法的自动生成

发布时间：2025年05月27日

`LLM应用` `机器学习` `人工智能`

> LLaMEA-BO: A Large Language Model Evolutionary Algorithm for Automatically Generating Bayesian Optimization Algorithms

# 摘要

> 贝叶斯优化（BO）是一类强大的算法，用于优化昂贵的黑盒函数，但设计有效的BO算法仍然是一个需要手动操作且依赖专业知识的任务。近期大型语言模型（LLMs）的进步为自动化科学研究开辟了新途径，包括优化算法的自动设计。尽管之前的工作将LLMs用于优化循环内部或生成非BO算法，我们却面临一个新挑战：利用LLMs自动生成完整的BO算法代码。我们的框架采用进化策略来引导LLM生成保留BO算法关键组件的Python代码：初始设计、代理模型和获取函数。我们提示LLM生成多个候选算法，并在来自COmparing Continuous Optimizers（COCO）平台的 established Black-Box Optimization Benchmarking（BBOB）测试套件上进行评估。根据性能表现，选择最优候选算法，通过受控提示变体进行组合和变异，从而实现迭代改进。尽管没有额外微调，LLM生成的算法在24个BBOB函数中的19个（维度为5）上优于现有的BO基线，并且很好地推广到更高维度和不同任务（来自Bayesmark框架）。这项工作表明，LLMs可以作为算法的共同设计者，为自动化BO开发提供新范式，并加速新型算法组合的发现。源代码可在https://github.com/Ewendawi/LLaMEA-BO获取。

> Bayesian optimization (BO) is a powerful class of algorithms for optimizing expensive black-box functions, but designing effective BO algorithms remains a manual, expertise-driven task. Recent advancements in Large Language Models (LLMs) have opened new avenues for automating scientific discovery, including the automatic design of optimization algorithms. While prior work has used LLMs within optimization loops or to generate non-BO algorithms, we tackle a new challenge: Using LLMs to automatically generate full BO algorithm code. Our framework uses an evolution strategy to guide an LLM in generating Python code that preserves the key components of BO algorithms: An initial design, a surrogate model, and an acquisition function. The LLM is prompted to produce multiple candidate algorithms, which are evaluated on the established Black-Box Optimization Benchmarking (BBOB) test suite from the COmparing Continuous Optimizers (COCO) platform. Based on their performance, top candidates are selected, combined, and mutated via controlled prompt variations, enabling iterative refinement. Despite no additional fine-tuning, the LLM-generated algorithms outperform state-of-the-art BO baselines in 19 (out of 24) BBOB functions in dimension 5 and generalize well to higher dimensions, and different tasks (from the Bayesmark framework). This work demonstrates that LLMs can serve as algorithmic co-designers, offering a new paradigm for automating BO development and accelerating the discovery of novel algorithmic combinations. The source code is provided at https://github.com/Ewendawi/LLaMEA-BO.

[Arxiv](https://arxiv.org/abs/2505.21034)