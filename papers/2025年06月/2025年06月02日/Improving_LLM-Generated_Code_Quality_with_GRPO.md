# 提升 LLM 生成代码质量的新方法：GRPO

发布时间：2025年06月02日

`LLM应用` `代码生成` `软件工程`

> Improving LLM-Generated Code Quality with GRPO

# 摘要

> 大型语言模型（LLMs）在代码生成领域得到了广泛应用。近期的训练方法采用了执行反馈作为奖励信号，通常侧重于代码的功能正确性，以单元测试通过率作为奖励信号。然而，这种奖励信号未能涵盖代码的可维护性、质量和安全性。我们针对这一尚未充分探索的领域，开发了一个全面的库来量化代码质量的各个方面，并将其作为GRPO的奖励。我们发现，根据这一衡量标准，GRPO提升了代码质量，这一结果得到了专家级匿名人工标注者的证实。

> Large Language Models (LLMs) are gaining widespread use for code generation. Recent training procedures use execution feedback as a reward signal, typically focusing on the functional correctness of the code, using unit test pass rate as a reward signal. However, this reward signal fails to capture notions of maintainability, quality and safety of the code produced. We address this under-explored area and develop a comprehensive library to quantify various aspects of code quality, and use it as a reward in GRPO. We find GRPO increases code quality according to this measure, which is confirmed by expert, blinded human annotators.

[Arxiv](https://arxiv.org/abs/2506.02211)