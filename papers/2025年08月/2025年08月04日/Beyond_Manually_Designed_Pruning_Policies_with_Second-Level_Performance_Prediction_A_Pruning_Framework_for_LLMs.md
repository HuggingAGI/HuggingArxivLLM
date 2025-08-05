# 超越传统手动设计：基于二级性能预测的大型语言模型剪枝框架

发布时间：2025年08月04日

`LLM应用

摘要中讨论了大语言模型的剪枝方法，特别是提出了一种新的框架PPF，用于优化模型的大小和性能，属于模型的应用和优化，因此归类为LLM应用。` `人工智能` `机器学习`

> Beyond Manually Designed Pruning Policies with Second-Level Performance Prediction: A Pruning Framework for LLMs

# 摘要

> 非均匀结构化网络剪枝方法能有效通过消除冗余通道或层来减小大语言模型的规模，相较于均匀策略，性能下降幅度更小。然而，现有非均匀方法严重依赖手动设计的剪枝策略（如层重要性和缩放因子），因而无法高效适应动态剪枝比例需求。此外，耗时的剪枝策略评估这一关键瓶颈进一步限制了迭代动态寻找最优策略的可行性。为解决这些限制，我们提出了PPF（预测剪枝框架），一种全新的大语言模型剪枝框架，通过二级性能预测消除手动设计依赖。PPF不仅支持动态剪枝比例下的实时决策，也适用于静态剪枝场景。它采用智能体生成自适应实时剪枝动作，同时一个轻量级性能预测器可在几秒内评估剪枝策略，大幅加速迭代优化过程。在Llama2-7B和Llama3-8B上的实验表明，PPF能生成动态/静态剪枝策略，并在现有方法基础上分别降低困惑度33.4%（动态剪枝）和84.78%（静态剪枝），超越手动设计策略。性能预测器实现高精度的二级性能预测（预测误差<0.0011），将平均评估延迟从分钟级（1分38.02秒的测试集评估方法）降至秒级（1.52秒），实现超过64倍加速。我们的代码将发布在https://github.com/Ma-zx/PPF。


> Non-uniform structured network pruning methods can effectively reduce Large Language Model (LLM) size by eliminating redundant channels or layers, offering lower performance degradation than uniform strategies. However, existing non-uniform methods rely heavily on manually designed pruning policies (e.g., layer importance and scaling factors), and therefore cannot efficiently adapt to scenarios with dynamic pruning ratio requirements. Additionly, a critical bottleneck -- the time-consuming evaluation of pruning policies -- further limits the feasibility of iteratively and dynamically finding optimal pruning policies. To address these limitations, we propose PPF (Predictive Pruning Framework), a novel pruning framework for LLMs that eliminates manual design dependencies via second-level performance prediction. PPF not only supports real-time pruning decisions under dynamic pruning ratios but is also applicable to static pruning scenarios. It employs an agent for producing adaptive and real-time pruning actions, while a lightweight performance predictor that can evaluate a pruning policy in seconds, significantly speeding up the iterative optimization process. Experiments on Llama2-7B and Llama3-8B show that PPF can generate dynamic/static pruning policies and it reduces perplexity by up to 33.4% (dynamic pruning) and 84.78% (static pruning) over existing methods, outperforming manually designed pruning policies. The performance predictor achieves second-level performance prediction with high accuracy (prediction error < 0.0011). It reduces the mean evaluation latency from minute-level (1 minute and 38.02 seconds of test-set evaluation methods) to second-level (1.52 second), achieving over 64 times speedup. Our code will be available at https://github.com/Ma-zx/PPF .

[Arxiv](https://arxiv.org/abs/2508.02381)