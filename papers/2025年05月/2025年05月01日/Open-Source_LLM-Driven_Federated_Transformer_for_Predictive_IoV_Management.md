# # 开源 LLM 驱动联邦变压器实现预测性车辆管理

发布时间：2025年05月01日

`LLM应用

理由：这篇论文探讨了将大型语言模型（LLMs）应用于车联网（IoV）管理的创新方法，具体涉及提示优化、联邦学习和合成数据生成，展示了LLMs在实际场景中的应用潜力。` `车联网` `智能交通系统`

> Open-Source LLM-Driven Federated Transformer for Predictive IoV Management

# 摘要

> 车联网（IoV）生态系统中联网车辆的普及带来了关键挑战，涉及可扩展性、实时性和隐私保护的交通管理。现有的集中式IoV解决方案通常面临高延迟、扩展性有限以及对专有AI模型的依赖，这些因素构成了大规模部署的重大障碍，尤其是在动态和隐私敏感的环境中。同时，将大型语言模型（LLMs）整合到车载系统中的研究尚不充分，特别是在提示优化和联邦环境下的有效利用方面。

为了解决这些问题，我们提出了联邦提示优化交通变压器（FPoTT），这是一个利用开源LLMs进行预测性IoV管理的新框架。FPoTT引入了一种动态提示优化机制，通过迭代优化文本提示来增强轨迹预测。该架构采用双层联邦学习范式，结合轻量级边缘模型进行实时推理，并与基于云的LLMs相结合以保持全局智能。此外，FPoTT集成了一个基于Transformer的合成数据生成器，通过生成多样化的、高保真的交通场景（采用下一代仿真（NGSIM）格式）来增强训练数据。

大量评估表明，FPoTT在使用EleutherAI Pythia-1B时，对真实世界数据的预测准确率达到99.86%，同时在合成数据集上也表现出色。这些结果凸显了开源LLMs在实现安全、适应性和可扩展性IoV管理方面的潜力，为智能移动生态系统中的专有解决方案提供了有前景的替代方案。


> The proliferation of connected vehicles within the Internet of Vehicles (IoV) ecosystem presents critical challenges in ensuring scalable, real-time, and privacy-preserving traffic management. Existing centralized IoV solutions often suffer from high latency, limited scalability, and reliance on proprietary Artificial Intelligence (AI) models, creating significant barriers to widespread deployment, particularly in dynamic and privacy-sensitive environments. Meanwhile, integrating Large Language Models (LLMs) in vehicular systems remains underexplored, especially concerning prompt optimization and effective utilization in federated contexts. To address these challenges, we propose the Federated Prompt-Optimized Traffic Transformer (FPoTT), a novel framework that leverages open-source LLMs for predictive IoV management. FPoTT introduces a dynamic prompt optimization mechanism that iteratively refines textual prompts to enhance trajectory prediction. The architecture employs a dual-layer federated learning paradigm, combining lightweight edge models for real-time inference with cloud-based LLMs to retain global intelligence. A Transformer-driven synthetic data generator is incorporated to augment training with diverse, high-fidelity traffic scenarios in the Next Generation Simulation (NGSIM) format. Extensive evaluations demonstrate that FPoTT, utilizing EleutherAI Pythia-1B, achieves 99.86% prediction accuracy on real-world data while maintaining high performance on synthetic datasets. These results underscore the potential of open-source LLMs in enabling secure, adaptive, and scalable IoV management, offering a promising alternative to proprietary solutions in smart mobility ecosystems.

[Arxiv](https://arxiv.org/abs/2505.00651)