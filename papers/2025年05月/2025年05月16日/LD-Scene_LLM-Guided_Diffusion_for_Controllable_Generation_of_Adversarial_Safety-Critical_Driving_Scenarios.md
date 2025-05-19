# LD-Scene：LLM引导的扩散生成方法，用于安全关键驾驶场景的可控对抗性生成

发布时间：2025年05月16日

`LLM应用` `自动驾驶` `智能驾驶`

> LD-Scene: LLM-Guided Diffusion for Controllable Generation of Adversarial Safety-Critical Driving Scenarios

# 摘要

> 自动驾驶系统的安全性和鲁棒性评估，离不开对安全关键场景的全面考察。然而，这些场景在真实驾驶数据中极为罕见，给自动驾驶汽车性能的评估带来了巨大挑战。现有方法通常面临可控性不足和用户不友好等问题，往往需要大量专业知识支撑。为此，我们提出了LD-Scene——一个融合大型语言模型（LLMs）与潜在扩散模型（LDMs）的创新框架，通过自然语言实现用户可控的对抗场景生成。我们的方案由两部分组成：捕获真实驾驶轨迹分布的LDM，以及将用户查询转化为对抗损失函数的LLM指导模块，确保生成场景与用户需求高度契合。此外，指导模块内置基于LLM的链式思维（CoT）代码生成器和代码调试器，显著提升了指导函数的可控性和可靠性。在nuScenes数据集上的大量实验表明，LD-Scene在生成现实、多样且有效的对抗场景方面表现卓越。更重要的是，我们的框架能够对对抗行为进行精细化控制，为特定驾驶场景的测试提供了强有力的支持。

> Ensuring the safety and robustness of autonomous driving systems necessitates a comprehensive evaluation in safety-critical scenarios. However, these safety-critical scenarios are rare and difficult to collect from real-world driving data, posing significant challenges to effectively assessing the performance of autonomous vehicles. Typical existing methods often suffer from limited controllability and lack user-friendliness, as extensive expert knowledge is essentially required. To address these challenges, we propose LD-Scene, a novel framework that integrates Large Language Models (LLMs) with Latent Diffusion Models (LDMs) for user-controllable adversarial scenario generation through natural language. Our approach comprises an LDM that captures realistic driving trajectory distributions and an LLM-based guidance module that translates user queries into adversarial loss functions, facilitating the generation of scenarios aligned with user queries. The guidance module integrates an LLM-based Chain-of-Thought (CoT) code generator and an LLM-based code debugger, enhancing the controllability and robustness in generating guidance functions. Extensive experiments conducted on the nuScenes dataset demonstrate that LD-Scene achieves state-of-the-art performance in generating realistic, diverse, and effective adversarial scenarios. Furthermore, our framework provides fine-grained control over adversarial behaviors, thereby facilitating more effective testing tailored to specific driving scenarios.

[Arxiv](https://arxiv.org/abs/2505.11247)