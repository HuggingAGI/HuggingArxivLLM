# OpenWebVoyager：借助迭代的真实世界探索、反馈与优化来构建多模态网络代理

发布时间：2024年10月25日

`Agent` `自主代理`

> OpenWebVoyager: Building Multimodal Web Agents via Iterative Real-World Exploration, Feedback and Optimization

# 摘要

> 大型语言和多模态模型发展迅猛，这使得人们对使用诸如 GPT-4o 之类的专有模型来开发能够应对网页导航等现实场景的自主代理产生了浓厚兴趣。尽管近期的开源工作尝试让代理拥有探索环境并持续改进的能力，但它们构建的是合成环境中的纯文本代理，其中奖励信号清晰明确。这类代理难以推广到需要多模态感知能力且缺乏真实信号的实际场景中。在本文中，我们引入了一个开源框架，旨在助力开发能够自主进行现实世界探索并自我提升的多模态网络代理。我们先是通过模仿学习训练基础模型以获取基本能力，接着让代理探索开放网络并收集其轨迹反馈，之后它通过向另一个通用模型判定的表现出色的轨迹学习来进一步优化其策略。这种探索 - 反馈 - 优化的循环可以持续多次迭代。实验结果显示，我们的网络代理在每次迭代后都能成功自我提升，在多个测试集中展现出强劲性能。

> The rapid development of large language and multimodal models has sparked significant interest in using proprietary models, such as GPT-4o, to develop autonomous agents capable of handling real-world scenarios like web navigation. Although recent open-source efforts have tried to equip agents with the ability to explore environments and continuously improve over time, they are building text-only agents in synthetic environments where the reward signals are clearly defined. Such agents struggle to generalize to realistic settings that require multimodal perception abilities and lack ground-truth signals. In this paper, we introduce an open-source framework designed to facilitate the development of multimodal web agent that can autonomously conduct real-world exploration and improve itself. We first train the base model with imitation learning to gain the basic abilities. We then let the agent explore the open web and collect feedback on its trajectories. After that, it further improves its policy by learning from well-performing trajectories judged by another general-purpose model. This exploration-feedback-optimization cycle can continue for several iterations. Experimental results show that our web agent successfully improves itself after each iteration, demonstrating strong performance across multiple test sets.

[Arxiv](https://arxiv.org/abs/2410.19609)