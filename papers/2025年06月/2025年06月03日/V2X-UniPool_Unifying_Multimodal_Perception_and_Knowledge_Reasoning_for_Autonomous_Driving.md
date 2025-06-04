# V2X-UniPool：统一多模态感知与知识推理，赋能自动驾驶

发布时间：2025年06月03日

`RAG` `自动驾驶` `智能交通`

> V2X-UniPool: Unifying Multimodal Perception and Knowledge Reasoning for Autonomous Driving

# 摘要

> 知识驱动的自动驾驶系统(ADs)虽然具备强大的推理能力，但面临两大关键挑战：单车传感器的短视导致的感知受限，以及缺乏实时环境 grounding 引发的幻觉问题。针对这些问题，本文提出了一种名为 V2X-UniPool 的统一框架，该框架将多模态车路协同(V2X)数据整合到基于时间和语言的知识池中。通过采用一种能够检索静态和动态知识的双查询增强生成机制(RAG)，我们的系统使 ADs 能够在静态环境和动态交通场景中进行准确且时间一致的推理。在真实世界的合作驾驶数据集上的实验结果表明，V2X-UniPool 显著提升了运动规划的准确性和推理能力。值得注意的是，即使对于零样本的车端模型，通过利用 V2X-UniPool 也能达到最先进的性能，同时与之前的 V2X 方法相比，传输成本降低了 99.9% 以上。

> Knowledge-driven autonomous driving systems(ADs) offer powerful reasoning capabilities, but face two critical challenges: limited perception due to the short-sightedness of single-vehicle sensors, and hallucination arising from the lack of real-time environmental grounding. To address these issues, this paper introduces V2X-UniPool, a unified framework that integrates multimodal Vehicle-to-Everything (V2X) data into a time-indexed and language-based knowledge pool. By leveraging a dual-query Retrieval-Augmented Generation (RAG) mechanism, which enables retrieval of both static and dynamic knowledge, our system enables ADs to perform accurate, temporally consistent reasoning over both static environment and dynamic traffic context. Experiments on a real-world cooperative driving dataset demonstrate that V2X-UniPool significantly enhances motion planning accuracy and reasoning capability. Remarkably, it enables even zero-shot vehicle-side models to achieve state-of-the-art performance by leveraging V2X-UniPool, while simultaneously reducing transmission cost by over 99.9\% compared to prior V2X methods.

[Arxiv](https://arxiv.org/abs/2506.02580)