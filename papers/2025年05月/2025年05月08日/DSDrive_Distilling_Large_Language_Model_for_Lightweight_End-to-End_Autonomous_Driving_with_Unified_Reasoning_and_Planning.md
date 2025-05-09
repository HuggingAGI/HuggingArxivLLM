# # **DSDrive：蒸馏大型语言模型，面向轻量级端到端自动驾驶的统一推理规划**

发布时间：2025年05月08日

`LLM应用` `自动驾驶` `智能驾驶`

> DSDrive: Distilling Large Language Model for Lightweight End-to-End Autonomous Driving with Unified Reasoning and Planning

# 摘要

> 我们提出了DSDrive，一个专为自动驾驶推理与规划设计的简明端到端框架。DSDrive采用紧凑型LLM，通过蒸馏方法继承了大型视觉语言模型（VLM）的推理能力。我们开发了基于航点的双头协调模块，同步数据集结构、优化目标及学习过程，实现任务对齐。DSDrive整合任务于统一框架，基于规划结果融合推理见解，提升可解释性和可靠性。在闭环仿真中，DSDrive表现优异，性能持平甚至超越基准模型，同时尺寸更小。此外，DSDrive的计算效率显著提升。这项工作展示了轻量化系统在自动驾驶中的巨大潜力，为实现高效可靠的解决方案提供了新思路。

> We present DSDrive, a streamlined end-to-end paradigm tailored for integrating the reasoning and planning of autonomous vehicles into a unified framework. DSDrive leverages a compact LLM that employs a distillation method to preserve the enhanced reasoning capabilities of a larger-sized vision language model (VLM). To effectively align the reasoning and planning tasks, a waypoint-driven dual-head coordination module is further developed, which synchronizes dataset structures, optimization objectives, and the learning process. By integrating these tasks into a unified framework, DSDrive anchors on the planning results while incorporating detailed reasoning insights, thereby enhancing the interpretability and reliability of the end-to-end pipeline. DSDrive has been thoroughly tested in closed-loop simulations, where it performs on par with benchmark models and even outperforms in many key metrics, all while being more compact in size. Additionally, the computational efficiency of DSDrive (as reflected in its time and memory requirements during inference) has been significantly enhanced. Evidently thus, this work brings promising aspects and underscores the potential of lightweight systems in delivering interpretable and efficient solutions for AD.

[Arxiv](https://arxiv.org/abs/2505.05360)