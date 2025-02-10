# 基于分析、检索与推理的大型语言模型问答系统：ARR方法

发布时间：2025年02月07日

`LLM应用` `问答系统`

> ARR: Question Answering with Large Language Models via Analyzing, Retrieving, and Reasoning

# 摘要

> 大型语言模型（LLMs）在多项选择题问答（QA）这类高难度基准测试中表现优异。零样本链式思维（CoT）提示虽能提升LLMs的推理能力，但其提供的仅是模糊笼统的指导（如"一步一步地思考"）。本文提出了一种名为ARR的零样本提示方法，该方法直观且高效，明确整合了QA解答中的三大关键步骤：解析问题意图、检索相关信息、以及逐步推理。在各种高难度QA任务上的实验证明，ARR不仅显著优于传统基线（无ARR提示），更超越了CoT的表现。通过消融实验和案例分析，我们进一步证实了ARR各组件的积极贡献：解析、检索与推理。特别值得一提的是，意图解析在ARR中发挥着关键作用。此外，我们在不同模型规模、LLM系列及生成设置下进行了广泛评估，结果充分证明了ARR方法的有效性、稳定性和普适性。

> Large language models (LLMs) achieve remarkable performance on challenging benchmarks that are often structured as multiple-choice question-answering (QA) tasks. Zero-shot Chain-of-Thought (CoT) prompting enhances reasoning in LLMs but provides only vague and generic guidance ("think step by step"). This paper introduces ARR, an intuitive and effective zero-shot prompting method that explicitly incorporates three key steps in QA solving: analyzing the intent of the question, retrieving relevant information, and reasoning step by step. Comprehensive experiments across diverse and challenging QA tasks demonstrate that ARR consistently improves the Baseline (without ARR prompting) and outperforms CoT. Ablation and case studies further validate the positive contributions of each component: analyzing, retrieving, and reasoning. Notably, intent analysis plays a vital role in ARR. Additionally, extensive evaluations across various model sizes, LLM series, and generation settings solidify the effectiveness, robustness, and generalizability of ARR.

[Arxiv](https://arxiv.org/abs/2502.04689)