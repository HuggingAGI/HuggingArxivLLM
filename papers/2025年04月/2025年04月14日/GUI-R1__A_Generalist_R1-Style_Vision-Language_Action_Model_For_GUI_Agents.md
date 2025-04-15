# GUI-R1：一款专为GUI代理设计的通用R1风格视觉语言动作模型

发布时间：2025年04月14日

`LLM应用` `人工智能` `计算机图形学`

> GUI-R1 : A Generalist R1-Style Vision-Language Action Model For GUI Agents

# 摘要

> 目前构建图形用户界面（GUI）代理的努力主要依赖于对大型视觉-语言模型（LVLMs）进行监督微调。然而，这一方法不仅需要大量数据，还难以有效理解和泛化到新界面，严重限制了其在现实场景中的应用，尤其在高层次任务中。受大型推理模型（如DeepSeek-R1）中强化微调（RFT）的启发，我们提出了
ame——首个通过统一动作空间规则建模来增强LVLMs在真实场景中GUI能力的强化学习框架。通过跨多平台（Windows、Linux、MacOS、Android、Web）的少量高质量数据，并采用组相对策略优化（GRPO）等算法，
ame在仅使用0.02%数据（3K vs. 13M）的情况下，在八项跨平台（移动、桌面、网络）基准测试中优于现有方法OS-Atlas。这证明了基于统一动作空间规则建模的强化学习在提升LVLMs现实GUI任务执行能力方面的巨大潜力。


> Existing efforts in building Graphical User Interface (GUI) agents largely rely on the training paradigm of supervised fine-tuning on Large Vision-Language Models (LVLMs). However, this approach not only demands extensive amounts of training data but also struggles to effectively understand GUI screenshots and generalize to unseen interfaces. The issue significantly limits its application in real-world scenarios, especially for high-level tasks. Inspired by Reinforcement Fine-Tuning (RFT) in large reasoning models (e.g., DeepSeek-R1), which efficiently enhances the problem-solving capabilities of large language models in real-world settings, we propose \name, the first reinforcement learning framework designed to enhance the GUI capabilities of LVLMs in high-level real-world task scenarios, through unified action space rule modeling. By leveraging a small amount of carefully curated high-quality data across multiple platforms (including Windows, Linux, MacOS, Android, and Web) and employing policy optimization algorithms such as Group Relative Policy Optimization (GRPO) to update the model, \name achieves superior performance using only 0.02\% of the data (3K vs. 13M) compared to previous state-of-the-art methods like OS-Atlas across eight benchmarks spanning three different platforms (mobile, desktop, and web). These results demonstrate the immense potential of reinforcement learning based on unified action space rule modeling in improving the execution capabilities of LVLMs for real-world GUI agent tasks.

[Arxiv](https://arxiv.org/abs/2504.10458)