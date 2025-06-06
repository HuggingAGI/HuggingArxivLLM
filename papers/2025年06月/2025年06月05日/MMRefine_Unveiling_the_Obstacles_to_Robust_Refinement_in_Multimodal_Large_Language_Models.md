# MMRefine：多模态大语言模型稳健微调的障碍揭秘

发布时间：2025年06月05日

`LLM应用` `多模态模型` `模型优化`

> MMRefine: Unveiling the Obstacles to Robust Refinement in Multimodal Large Language Models

# 摘要

> 本文提出了一项名为MMRefine的多模态精调基准，专注于评估多模态大型语言模型（MLLMs）的错误精调能力。随着推理过程中增强推理能力成为关键，MMRefine提供了一个全面的评估框架，能够测试MLLMs在六种不同场景下检测和纠正错误的能力，而不仅仅是关注精调前后的准确度变化。此外，该基准通过将错误分类为六种类型，深入分析了精调性能的各个方面。通过对多种开放和封闭的MLLMs进行的实验，我们揭示了影响精调性能的瓶颈和关键因素，为提升模型推理能力提供了重要的改进方向。我们的代码和数据集已在GitHub上公开发布，地址为https://github.com/naver-ai/MMRefine。

> This paper introduces MMRefine, a MultiModal Refinement benchmark designed to evaluate the error refinement capabilities of Multimodal Large Language Models (MLLMs). As the emphasis shifts toward enhancing reasoning during inference, MMRefine provides a framework that evaluates MLLMs' abilities to detect and correct errors across six distinct scenarios beyond just comparing final accuracy before and after refinement. Furthermore, the benchmark analyzes the refinement performance by categorizing errors into six error types. Experiments with various open and closed MLLMs reveal bottlenecks and factors impeding refinement performance, highlighting areas for improvement in effective reasoning enhancement. Our code and dataset are publicly available at https://github.com/naver-ai/MMRefine.

[Arxiv](https://arxiv.org/abs/2506.04688)