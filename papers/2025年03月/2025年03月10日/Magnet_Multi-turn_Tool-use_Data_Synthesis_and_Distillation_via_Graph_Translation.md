# Magnet: 基于图翻译的多轮工具使用数据合成与蒸馏

发布时间：2025年03月10日

`LLM应用` `人工智能`

> Magnet: Multi-turn Tool-use Data Synthesis and Distillation via Graph Translation

# 摘要

> 大型语言模型（LLMs）展现了有效利用外部工具处理用户查询的能力，但在复杂、多轮的用户与多个工具交互中，其性能可能受到限制。为解决这一问题，我们提出了一种名为Magnet的框架，通过生成高质量的训练轨迹，提升大型语言模型代理在与人类多轮对话中的函数调用能力。该框架基于自动迭代的函数签名路径到查询序列和可执行函数调用的转换。我们通过图模型刻画多轮场景中的复杂函数交互，并设计了新型节点操作构建可靠的签名路径。受上下文蒸馏启发，我们在使用教师模型生成正负轨迹时，将参考函数调用序列作为积极提示，错误函数调用作为消极提示。实验显示，通过监督微调和基于负轨迹的偏好优化，使用正轨迹训练的140亿参数模型Magnet-14B-mDPO在BFCL-v3和ToolQuery上分别取得68.01和73.30的优异成绩，显著超越了教师模型Gemini-1.5-pro-002的函数调用性能。

> Large language models (LLMs) have exhibited the ability to effectively utilize external tools to address user queries. However, their performance may be limited in complex, multi-turn interactions involving users and multiple tools. To address this, we propose Magnet, a principled framework for synthesizing high-quality training trajectories to enhance the function calling capability of large language model agents in multi-turn conversations with humans. The framework is based on automatic and iterative translations from a function signature path to a sequence of queries and executable function calls. We model the complicated function interactions in multi-turn cases with graph and design novel node operations to build reliable signature paths. Motivated by context distillation, when guiding the generation of positive and negative trajectories using a teacher model, we provide reference function call sequences as positive hints in context and contrastive, incorrect function calls as negative hints. Experiments show that training with the positive trajectories with supervised fine-tuning and preference optimization against negative trajectories, our 14B model, Magnet-14B-mDPO, obtains 68.01 on BFCL-v3 and 73.30 on ToolQuery, surpassing the performance of the teacher model Gemini-1.5-pro-002 by a large margin in function calling.

[Arxiv](https://arxiv.org/abs/2503.07826)