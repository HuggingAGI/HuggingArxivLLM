# MidPO：通过专家混合框架实现大型语言模型的安全性与 helpfulness 双重偏好优化

发布时间：2025年06月03日

`LLM应用` `大型语言模型`

> MidPO: Dual Preference Optimization for Safety and Helpfulness in Large Language Models via a Mixture of Experts Framework

# 摘要

> 随着大型语言模型 (LLMs) 在各领域的广泛应用，如何在保持模型的有用性的同时提升安全性成为重要挑战。现有研究主要通过安全约束的在线或离线偏好优化来解决这一问题，但在线方法常因过度强调安全而牺牲有用性，离线方法则在自适应平衡安全与有用性方面表现欠佳。为此，我们提出了一种用于安全与有用性双目标优化的专家混合（MoE）框架——MidPO。MidPO 首先通过单目标增强的直接偏好优化方法，将基础模型转化为安全与有用性两个独立专家，并分别对其进行优化微调。随后，MidPO 将这两个专家整合到 MoE 框架中，并设计动态路由机制，自适应地平衡两者贡献。我们在三个流行数据集上的实验表明，MidPO 在安全性和有用性方面均显著优于现有方法。代码与模型即将发布。

> As large language models (LLMs) are increasingly applied across various domains, enhancing safety while maintaining the helpfulness of LLMs has become a critical challenge. Recent studies solve this problem through safety-constrained online preference optimization or safety-constrained offline preference optimization. However, the safety-constrained online methods often suffer from excessive safety, which might reduce helpfulness, while the safety-constrained offline methods perform poorly in adaptively balancing safety and helpfulness. To address these limitations, we propose MidPO, a \textbf{\underline{Mi}}xture of Experts (MoE) framework for safety-helpfulness \textbf{\underline{d}}ual \textbf{\underline{P}}reference \textbf{\underline{O}}ptimization. Firstly, MidPO devises single-preference enhanced direct preference optimization approach to transform the base model into two independent experts, termed safety and helpfulness experts, and fine-tunes the two independent experts for optimal safety or helpfulness performance. Secondly, to achieve an effective balance between safety and helpfulness, MidPO incorporates the two experts into the MoE framework and designs a dynamic routing mechanism to allocate contributions from each expert adaptively. We conduct quantitative and qualitative experiments on three popular datasets to demonstrate the proposed MidPO significantly outperforms state-of-the-art approaches in both safety and helpfulness. The code and models will be released.

[Arxiv](https://arxiv.org/abs/2506.02460)