# AutoLife：借助智能手机与大型语言模型（LLMs）实现的自动生活日志记录

发布时间：2024年12月20日

`LLM应用` `移动传感` `生活日志`

> AutoLife: Automatic Life Journaling with Smartphones and LLMs

# 摘要

> 这篇论文引入了一种全新的移动传感应用——生活日志，旨在为用户的日常生活生成语义描述。我们推出了 AutoLife，这是一个基于商用智能手机的自动生活日志系统。AutoLife 仅输入智能手机的低成本传感器数据（不含照片或音频），就能为用户自动生成全面的生活日志。为此，我们先从多模态传感器数据中得出时间、运动和位置等上下文信息，借助大型语言模型（LLMs）的零样本能力，并融入有关人类生活的常识知识，来解读各类上下文从而生成生活日志。为应对任务的复杂性和长时间的传感时长，提出了一个多层框架，它将任务分解，并把 LLMs 与其他用于生活日志的技术无缝融合。本研究构建了一个真实生活数据集作为基准，大量实验结果表明，AutoLife 生成的生活日志准确且可靠。

> This paper introduces a novel mobile sensing application - life journaling - designed to generate semantic descriptions of users' daily lives. We present AutoLife, an automatic life journaling system based on commercial smartphones. AutoLife only inputs low-cost sensor data (without photos or audio) from smartphones and can automatically generate comprehensive life journals for users. To achieve this, we first derive time, motion, and location contexts from multimodal sensor data, and harness the zero-shot capabilities of Large Language Models (LLMs), enriched with commonsense knowledge about human lives, to interpret diverse contexts and generate life journals. To manage the task complexity and long sensing duration, a multilayer framework is proposed, which decomposes tasks and seamlessly integrates LLMs with other techniques for life journaling. This study establishes a real-life dataset as a benchmark and extensive experiment results demonstrate that AutoLife produces accurate and reliable life journals.

[Arxiv](https://arxiv.org/abs/2412.15714)