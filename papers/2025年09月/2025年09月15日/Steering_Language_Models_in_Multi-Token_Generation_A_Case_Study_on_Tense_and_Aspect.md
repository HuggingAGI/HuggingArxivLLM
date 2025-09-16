# 多 token 生成中的语言模型引导：时态与体的案例研究

发布时间：2025年09月15日

`LLM理论` `基础理论`

> Steering Language Models in Multi-Token Generation: A Case Study on Tense and Aspect

# 摘要

> 大型语言模型（LLMs）虽能生成语法规范的文本，但其内部如何编码句法知识仍是未解之谜。先前研究多聚焦二元语法对比，而本研究则针对动词时态与体貌这两种多维层级语法现象，通过线性判别分析在残差空间中识别出各自独特的正交方向，进而探究其表征与控制机制。随后，我们通过跨三个生成任务的概念引导，实现了对这两种语法特征的因果控制。接着，我们在案例研究中利用这些识别出的特征，探究了影响多token生成中有效引导的关键因素。研究发现，引导强度、位置和持续时间是降低主题偏移、文本退化等不良副作用的核心参数。综上，模型通过结构化、类人化的方式编码时态与体貌，但生成过程中对这些特征的有效控制受多种因素影响，需通过手动调整或自动优化实现。

> Large language models (LLMs) are able to generate grammatically well-formed text, but how do they encode their syntactic knowledge internally? While prior work has focused largely on binary grammatical contrasts, in this work, we study the representation and control of two multidimensional hierarchical grammar phenomena - verb tense and aspect - and for each, identify distinct, orthogonal directions in residual space using linear discriminant analysis. Next, we demonstrate causal control over both grammatical features through concept steering across three generation tasks. Then, we use these identified features in a case study to investigate factors influencing effective steering in multi-token generation. We find that steering strength, location, and duration are crucial parameters for reducing undesirable side effects such as topic shift and degeneration. Our findings suggest that models encode tense and aspect in structurally organized, human-like ways, but effective control of such features during generation is sensitive to multiple factors and requires manual tuning or automated optimization.

[Arxiv](https://arxiv.org/abs/2509.12065)