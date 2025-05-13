# 多维度约束框架：评估与优化大型语言模型的指令遵循能力

发布时间：2025年05月12日

`LLM应用` `人工智能`

> A Multi-Dimensional Constraint Framework for Evaluating and Improving Instruction Following in Large Language Models

# 摘要

> 指令遵循旨在评估大型语言模型生成符合用户定义约束输出的能力。然而，现有基准测试通常依赖于模板化的约束提示，这些提示缺乏真实使用场景的多样性，限制了对模型性能的精细评估。为填补这一空白，我们提出一个包含三种约束模式、四个约束类别和四个难度级别的多维约束框架。基于此框架，我们开发了一个自动指令生成管道，执行约束扩展、冲突检测和指令重写，生成了1,200个可验证的指令遵循测试样本。我们评估了七个模型家族中的19个LLM，并发现不同约束形式下的性能存在显著差异。例如，平均性能从I级的77.67%下降到IV级的32.96%。此外，我们通过使用该方法生成强化学习的数据，展示了其实用性，从而在不降低整体性能的情况下显著提升了指令遵循能力。深入分析表明，这些改进主要源于对模型注意力模块参数的修改，这增强了对约束的识别和遵守。代码和数据可在https://github.com/Junjie-Ye/MulDimIF获得。

> Instruction following evaluates large language models (LLMs) on their ability to generate outputs that adhere to user-defined constraints. However, existing benchmarks often rely on templated constraint prompts, which lack the diversity of real-world usage and limit fine-grained performance assessment. To fill this gap, we propose a multi-dimensional constraint framework encompassing three constraint patterns, four constraint categories, and four difficulty levels. Building on this framework, we develop an automated instruction generation pipeline that performs constraint expansion, conflict detection, and instruction rewriting, yielding 1,200 code-verifiable instruction-following test samples. We evaluate 19 LLMs across seven model families and uncover substantial variation in performance across constraint forms. For instance, average performance drops from 77.67% at Level I to 32.96% at Level IV. Furthermore, we demonstrate the utility of our approach by using it to generate data for reinforcement learning, achieving substantial gains in instruction following without degrading general performance. In-depth analysis indicates that these gains stem primarily from modifications in the model's attention modules parameters, which enhance constraint recognition and adherence. Code and data are available in https://github.com/Junjie-Ye/MulDimIF.

[Arxiv](https://arxiv.org/abs/2505.07591)