# CRPE：增强大型语言模型的代码生成推理能力

发布时间：2025年05月15日

`LLM应用` `代码生成` `人工智能`

> CRPE: Expanding The Reasoning Capability of Large Language Model for Code Generation

# 摘要

> 我们推出CRPE（代码推理过程增强器），一个创新的三阶段框架，致力于提升大型语言模型（LLMs）的复杂代码推理能力。CRPE基于现有系统1模型，专注于解决LLMs在代码生成任务中的分析与逻辑处理难题。我们的框架不仅方法严谨，而且易于实施，为语言模型培养高级代码推理能力提供了有效途径。通过CRPE的实现，我们成功打造了性能更优的COT-Coder。在LiveCodeBench（20240701-20240901）的评测中，源自Qwen2.5-Coder-7B-Base的COT-Coder-7B-StepDPO表现卓越，pass@1准确率达到21.88%，超越同规模甚至更大模型。而基于Qwen2.5-Coder-32B-Base的COT-Coder-32B-StepDPO更以35.08%的pass@1准确率，领先于GPT4O。CRPE作为一个全面开源的解决方案，完整覆盖了从指令数据获取到专家代码推理数据合成的全流程，并最终构建了一个自主推理增强机制。

> We introduce CRPE (Code Reasoning Process Enhancer), an innovative three-stage framework for data synthesis and model training that advances the development of sophisticated code reasoning capabilities in large language models (LLMs). Building upon existing system-1 models, CRPE addresses the fundamental challenge of enhancing LLMs' analytical and logical processing in code generation tasks. Our framework presents a methodologically rigorous yet implementable approach to cultivating advanced code reasoning abilities in language models. Through the implementation of CRPE, we successfully develop an enhanced COT-Coder that demonstrates marked improvements in code generation tasks. Evaluation results on LiveCodeBench (20240701-20240901) demonstrate that our COT-Coder-7B-StepDPO, derived from Qwen2.5-Coder-7B-Base, with a pass@1 accuracy of 21.88, exceeds all models with similar or even larger sizes. Furthermore, our COT-Coder-32B-StepDPO, based on Qwen2.5-Coder-32B-Base, exhibits superior performance with a pass@1 accuracy of 35.08, outperforming GPT4O on the benchmark. Overall, CRPE represents a comprehensive, open-source method that encompasses the complete pipeline from instruction data acquisition through expert code reasoning data synthesis, culminating in an autonomous reasoning enhancement mechanism.

[Arxiv](https://arxiv.org/abs/2505.10594)