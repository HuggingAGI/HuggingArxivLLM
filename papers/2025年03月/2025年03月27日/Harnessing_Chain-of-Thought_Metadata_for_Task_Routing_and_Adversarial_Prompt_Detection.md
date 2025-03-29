# # 基于链式思维元数据的任务路由与对抗性提示检测

发布时间：2025年03月27日

`LLM应用` `人工智能` `模型安全`

> Harnessing Chain-of-Thought Metadata for Task Routing and Adversarial Prompt Detection

# 摘要

> 本研究提出了一种名为“思考次数”（NofT）的指标，用于评估任务预提示的难度，并为大型语言模型（LLMs）在生产环境中的应用提供支持。通过设定基于思考次数的阈值，该指标能够有效区分提示的难度，并优化提示路由策略。在使用具有17亿、70亿和140亿参数的Deepseek量化蒸馏版本处理MathInstruct数据集中的提示时，系统延迟降低了2%。此外，该指标在检测用于提示注入攻击的对抗性提示方面表现出色，支持的分类器在检测中达到了95%的准确率。我们的实验数据和代码已开源，可在GitHub页面获取：https://github.com/rymarinelli/Number_Of_Thoughts/tree/main。

> In this work, we propose a metric called Number of Thoughts (NofT) to determine the difficulty of tasks pre-prompting and support Large Language Models (LLMs) in production contexts. By setting thresholds based on the number of thoughts, this metric can discern the difficulty of prompts and support more effective prompt routing. A 2% decrease in latency is achieved when routing prompts from the MathInstruct dataset through quantized, distilled versions of Deepseek with 1.7 billion, 7 billion, and 14 billion parameters. Moreover, this metric can be used to detect adversarial prompts used in prompt injection attacks with high efficacy. The Number of Thoughts can inform a classifier that achieves 95% accuracy in adversarial prompt detection. Our experiments ad datasets used are available on our GitHub page: https://github.com/rymarinelli/Number_Of_Thoughts/tree/main.

[Arxiv](https://arxiv.org/abs/2503.21464)