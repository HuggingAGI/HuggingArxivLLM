# PipeSpec：一种打破阶段依赖的分层 LLM 解码方法

发布时间：2025年05月02日

`LLM应用` `分布式计算`

> PipeSpec: Breaking Stage Dependencies in Hierarchical LLM Decoding

# 摘要

> Speculative decoding加速大型语言模型推理，通过并行验证使用较小的草稿模型生成候选标记。然而，现有方法受限于流水线阶段的串行依赖，无法充分发挥硬件性能。我们提出PipeSpec框架，将speculative decoding推广到由【数学公式】个模型组成的层次化流水线，通过轻量级协调实现预测验证和回滚的异步执行。我们的分析模型刻画了流水线各阶段的标记生成速率，并证明与传统解码相比，在任何非零接受率下，吞吐量都有保证的提升。我们进一步推导了稳态验证概率的闭式表达式，解释了流水线深度的实际效益。实验结果表明，PipeSpec实现了高达【数学公式】倍的加速，同时超越了现有最优方法。我们通过LLaMA 2和3模型在文本摘要和代码生成任务上验证了PipeSpec，结果表明流水线效率随着模型深度的增加而提升，为加速多设备系统上的LLM推理提供了一种可扩展的方法。

> Speculative decoding accelerates large language model inference by using smaller draft models to generate candidate tokens for parallel verification. However, current approaches are limited by sequential stage dependencies that prevent full hardware utilization. We present PipeSpec, a framework that generalizes speculative decoding to $k$ models arranged in a hierarchical pipeline, enabling asynchronous execution with lightweight coordination for prediction verification and rollback. Our analytical model characterizes token generation rates across pipeline stages and proves guaranteed throughput improvements over traditional decoding for any non-zero acceptance rate. We further derive closed-form expressions for steady-state verification probabilities that explain the empirical benefits of pipeline depth. Experimental results show that PipeSpec achieves up to 2.54$\times$ speedup while outperforming state-of-the-art methods. We validate PipeSpec across text summarization and code generation tasks using LLaMA 2 and 3 models, demonstrating that pipeline efficiency increases with model depth, providing a scalable approach to accelerating LLM inference on multi-device systems.

[Arxiv](https://arxiv.org/abs/2505.01572)