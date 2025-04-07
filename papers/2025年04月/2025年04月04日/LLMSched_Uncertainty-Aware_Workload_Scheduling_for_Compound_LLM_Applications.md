# LLMSched：针对复合LLM应用的不确定性感知工作负载调度

发布时间：2025年04月04日

`LLM应用` `人工智能` `调度优化`

> LLMSched: Uncertainty-Aware Workload Scheduling for Compound LLM Applications

# 摘要

> 开发复合型大型语言模型 (LLM) 应用正日益成为解决现实问题的一种普遍方法。在这些应用中，LLM 与各种外部模块（包括API和其他LLM）协作，以实现复杂的智能服务。然而，我们发现复合型LLM应用中固有持续时间和结构不确定性为LLM服务提供商在高效服务和调度这些应用带来了巨大挑战。本文中，我们提出了LLMSched，一个针对新兴复合型LLM应用的不确定性感知调度框架。在LLMSched中，我们首先设计了一种新型的基于DAG的模型来描述具有不确定性的复合型LLM应用。然后，我们采用贝叶斯网络对复合型LLM应用进行全面分析，识别出能够降低不确定性的阶段，并结合基于熵的机制来量化这些阶段的不确定性降低程度。通过将不确定性降低策略与任务完成时间（JCT）优化方案相结合，我们进一步提出了一种高效的调度器以减少平均JCT。通过对多种具有代表性的复合型LLM应用进行仿真和实验测试，结果表明与现有的先进调度方案相比，LLMSched能够将平均任务完成时间降低14~79%。

> Developing compound Large Language Model (LLM) applications is becoming an increasingly prevalent approach to solving real-world problems. In these applications, an LLM collaborates with various external modules, including APIs and even other LLMs, to realize complex intelligent services. However, we reveal that the intrinsic duration and structural uncertainty in compound LLM applications pose great challenges for LLM service providers in serving and scheduling them efficiently. In this paper, we propose LLMSched, an uncertainty-aware scheduling framework for emerging compound LLM applications. In LLMSched, we first design a novel DAG-based model to describe the uncertain compound LLM applications. Then, we adopt the Bayesian network to comprehensively profile compound LLM applications and identify uncertainty-reducing stages, along with an entropy-based mechanism to quantify their uncertainty reduction. Combining an uncertainty reduction strategy and a job completion time (JCT)-efficient scheme, we further propose an efficient scheduler to reduce the average JCT. Evaluation of both simulation and testbed experiments on various representative compound LLM applications shows that compared to existing state-of-the-art scheduling schemes, LLMSched can reduce the average JCT by 14~79%.

[Arxiv](https://arxiv.org/abs/2504.03444)